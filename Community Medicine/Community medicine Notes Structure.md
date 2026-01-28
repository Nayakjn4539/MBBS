```dataviewjs
// 1. SETUP PATH
let sourceFolder = "Community Medicine/Jignotes"

// 2. GET NOTES
let pages = dv.pages(`"${sourceFolder}"`)
let groups = pages.groupBy(p => p.file.folder)

// 3. LOOP AND GENERATE HTML
for (let group of groups) {
    let folderName = group.key.split("/").pop();
    
    // Start the HTML Block for this chapter
    let htmlBlock = `<details style="border: 1px solid var(--background-modifier-border); padding: 10px; border-radius: 5px; margin-bottom: 10px;">
    <summary style="cursor: pointer; font-weight: bold; font-size: 1.1em;">📂 ${folderName} <span style="font-weight: normal; opacity: 0.7;">(${group.rows.length})</span></summary>
    <br>
    <table style="width: 100%;">
        <thead>
            <tr>
                <th style="text-align: left;">Note</th>
                <th style="text-align: left;">Status</th>
                <th style="text-align: left;">Date</th>
            </tr>
        </thead>
        <tbody>`;

    // Add rows to the HTML table
    let sortedRows = group.rows.sort(k => k.file.name, 'asc');
    
    for (let page of sortedRows) {
        // Calculate Status Logic
        let statusText = page.status ? String(page.status) : "";
        let isDone = statusText.toLowerCase().includes("done") || statusText.toLowerCase().includes("read");
        let displayDate = isDone ? page.file.mtime.toFormat("yyyy-MM-dd") : "";
        let displayIcon = isDone ? "✅" : "⏳";
        
        // Add the row
        htmlBlock += `
            <tr>
                <td><a href="${page.file.path}" class="internal-link">${page.file.name}</a></td>
                <td>${statusText}</td>
                <td>${displayIcon} ${displayDate}</td>
            </tr>`;
    }

    // Close the block
    htmlBlock += `</tbody></table></details>`;

    // Render the whole block at once
    dv.paragraph(htmlBlock);
}

```