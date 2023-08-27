The hard copy book has an Index of Subjects in Vol. 3 pp. 661-694.
The below subjects are only those I wish to highlight.

`````dataview
TABLE WITHOUT ID Subject, file.link AS Location
FROM #toc
WHERE subjects != null
FLATTEN subjects AS Subject
SORT Subject ASC, file.link ASC
`````