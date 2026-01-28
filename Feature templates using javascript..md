# To create tabular coloumn of backlinks in Empty notes.
Copy the below block of code and paste in empty node notes to see all linked notes. 
No need to open side panel to see the linked files.
**Enclose the code block in thre
dataview 
  TABLE 
  file.folder as "Location/Subject",
  file.link as "File",
  status as "Status",
  choice(contains(lower(string(status)), "done") OR contains(lower(string(status)), "read"), "✅ " + dateformat(file.mtime, "yyyy-MM-dd"), "⏳ Pending") as "Completion Date"
FROM [[TAG]]        
SORT file.name ASC
```



