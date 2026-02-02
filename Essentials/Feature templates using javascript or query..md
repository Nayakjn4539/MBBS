# To create tabular coloumn of backlinks in Empty notes.
Copy the below block of code and paste in empty node notes to see all linked notes. 
No need to open side panel to see the linked notes
```text
```dataview 
TABLE WITHOUT ID
  file.folder as "Location/Subject",
  file.link as "File",
  status as "Status",
  choice(
    contains(lower(string(status)), "done") 
    OR contains(lower(string(status)), "read"), 
    "✅ " + dateformat(file.mtime, "yyyy-MM-dd"), 
    "⏳ Pending"
  ) as "Completion Date"
FROM [[BACK LINK WORD]]
SORT file.name ASC```
```

# To create folder structure tables that update with time
This code block is to be pasted in the notes that we plan to substitute for the canvas files as canvas files dont autoupdate by scanning the YAML tag for note status.
Save this file in the parent folder next to "Jignotes" for best use case.
```text
```dataviewjs
// 1. SETUP PATH
// Change this to your exact folder path!
let sourceFolder = "Community medicine/Jignotes" 

// 2. GET NOTES
let pages = dv.pages(`"${sourceFolder}"`)

// 3. GROUP BY FOLDER
let groups = pages.groupBy(p => p.file.folder)

// 4. SORT THE FOLDERS (GROUPS)
// Logic: Find the smallest "up" number in each folder and use that to order the folders
let sortedGroups = groups.sort(group => {
    let upValues = group.rows.map(n => Number(n.up)).filter(n => !isNaN(n));
    // If a folder has numbers, use the smallest one. If not, push it to the end (999999).
    return upValues.length > 0 ? Math.min(...upValues) : 999999;
}, 'asc');

// 5. LOOP AND GENERATE HTML
for (let group of sortedGroups) {
    let folderName = group.key.split("/").pop();
    
    // Start the HTML Block
    let htmlBlock = `<details style="border: 1px solid var(--background-modifier-border); padding: 10px; border-radius: 5px; margin-bottom: 10px;">
    <summary style="cursor: pointer; font-weight: bold; font-size: 1.1em;">📂 ${folderName} <span style="font-weight: normal; opacity: 0.7;">(${group.rows.length})</span></summary>
    <br>
    <table style="width: 100%;">
        <thead>
            <tr>
                <th style="width: 10%; text-align: left;">No.</th>
                <th style="text-align: left;">Note</th>
                <th style="text-align: left;">Status</th>
                <th style="text-align: left;">Date</th>
            </tr>
        </thead>
        <tbody>`;

    // 6. SORT THE NOTES (ROWS)
    // Logic: Sort strictly by the 'up' number
    let sortedRows = group.rows.sort(k => Number(k.up) || 999999, 'asc');
    
    for (let page of sortedRows) {
        // Status Logic
        let statusText = page.status ? String(page.status) : "";
        let isDone = statusText.toLowerCase().includes("done") || statusText.toLowerCase().includes("read");
        let displayDate = isDone ? page.file.mtime.toFormat("yyyy-MM-dd") : "";
        let displayIcon = isDone ? "✅" : "⏳";
        
        // Serial Number Logic (Show '-' if 'up' is missing)
        let serialNum = page.up !== undefined ? page.up : "-"; 

        htmlBlock += `
            <tr>
                <td style="font-weight: bold; color: var(--text-muted);">${serialNum}</td>
                <td><a href="${page.file.path}" class="internal-link">${page.file.name}</a></td>
                <td>${statusText}</td>
                <td>${displayIcon} ${displayDate}</td>
            </tr>`;
    }

    htmlBlock += `</tbody></table></details>`;
    dv.paragraph(htmlBlock);
}```

```

# Template to add at the top of new notes(YAML data)
```text
---
status: pending
tags:
  - Tag 1
  - Tag 2
subject: [Subject Folder Name ]
topic: COMMUNICABLE DISEASES
up:
  - - [serial number can be decimal to insert in between]
---
```