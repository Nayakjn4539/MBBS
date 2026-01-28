```dataview
TABLE file.folder as "Topic"
FROM [[COMMUNICABLE DISEASES]]
WHERE contains(file.content, 
"#[[COMMUNICABLE DISEASES]]")
```

