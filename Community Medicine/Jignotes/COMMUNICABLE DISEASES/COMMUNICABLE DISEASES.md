```dataview 
  TABLE WITHOUT ID
  file.folder as "Location/Subject",
  file.link as "File",
  status as "Status",
  choice(contains(lower(string(status)), "done") OR contains(lower(string(status)), "read"), "✅ " + dateformat(file.mtime, "yyyy-MM-dd"), "⏳ Pending") as "Completion Date"
FROM [[COMMUNICABLE DISEASES]]
SORT file.name ASC
```

