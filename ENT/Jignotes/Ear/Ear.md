```dataview 
TABLE WITHOUT ID
  file.folder as "ENT",
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