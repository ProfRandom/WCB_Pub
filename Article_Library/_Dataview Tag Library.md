---
Aliases: [ "#math" ]
---


```dataview
TABLE WITHOUT ID tag AS "Tag"
FROM ""
FLATTEN file.tags AS tag
GROUP BY tag
SORT tag ASC
```

