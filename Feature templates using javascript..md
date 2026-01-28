# To create tabular coloumn of backlinks in Empty notes.
Copy the below block of code and paste in empty node notes to see all linked notes. 
No need to open side panel to see the linked notes
```text
```dataview 
TABLE 
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
SORT file.name ASC
```

# To create folder structure tables that update with time
This code block is to be pasted in the notes that we plan to substitute for the canvas files as canvas files dont autoupdate by scanning the YAML tag for note status.




