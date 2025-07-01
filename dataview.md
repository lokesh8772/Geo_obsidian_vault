```dataview
list
FROM ""
WHERE file.ctime >= date(today) - dur(1 days)
```