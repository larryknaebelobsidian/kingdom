#`````dataview
LIST
FROM #toc
WHERE completion < 1 and completion != null
SORT id
#`````

`````dataview

LIST
FROM #toc
WHERE completion = 1 and completion != null
SORT id
`````














