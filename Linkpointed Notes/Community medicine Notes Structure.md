```dataviewjs
// Change this path to match your folder exactly
let sourceFolder = "/MBBS/Community medicine/Jignotes"

// Get all pages from that folder
let pages = dv.pages(`"${sourceFolder}"`)

// Group them by their Folder (which represents your Chapters)
let groups = pages.groupBy(p => p.file.folder.replace(sourceFolder + "/", ""))

// Loop through each Chapter group
for (let group of groups) {
    // 1. Create the Collapsible Header (The Chapter Name)
    // We use HTML <details> tags to create the collapse effect
    dv.paragraph(`
    <details>
    <summary>📂 <b>${group.key.replace(sourceFolder, "")}</b> (${group.rows.length} notes)</summary>
    `)

    // 2. Generate the Table INSIDE the collapsible section
    dv.table(
        ["Note", "Status", "Date"], 
        group.rows
            .sort(k => k.file.name, 'asc')
            .map(k => [
                k.file.link, 
                k.status,
                // Logic for the tick mark
                (k.status && (k.status.includes("done") || k.status.includes("read"))) 
                ? "✅ " + (k.file.mtime.toFormat("yyyy-MM-dd")) 
                : "⏳"
            ])
    )
    
    // 3. Close the collapsible section
    dv.paragraph(`</details><hr>`)
}
```