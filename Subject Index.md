
`````dataview
TABLE WITHOUT ID Subject, file.link AS Location
FROM #toc
WHERE subjects != null
FLATTEN subjects AS Subject
SORT Subject ASC, file.link ASC
`````