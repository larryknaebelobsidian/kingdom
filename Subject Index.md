The hard copy book has an Index of Subjects in Vol. 3 pp. 661-694.

The below subjects may not align with Peters and are ***only those I wish to highlight***.
### List of Subjects I Wish to Highlight
```dataview
TABLE WITHOUT ID Subject
FROM #toc
WHERE subjects != null
FLATTEN subjects AS Subject
SORT Subject ASC
GROUP BY Subject
```


`````dataview
TABLE WITHOUT ID Subject, file.link AS Location
FROM #toc
WHERE subjects != null
FLATTEN subjects AS Subject
SORT Subject ASC, file.link ASC
`````