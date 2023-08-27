The hard copy book has an Index of Subjects in Vol. 3 pp. 661-694.
The below subjects are a subset or complement of those in the Index of Subjects.

`````dataview
TABLE WITHOUT ID Subject, file.link AS Location
FROM #toc
WHERE subjects != null
FLATTEN subjects AS Subject
SORT Subject ASC, file.link ASC
`````