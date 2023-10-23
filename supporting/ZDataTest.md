
`````dataview
TABLE  pagecount AS PageCount, observationcount AS ObservationCount, completion AS Completion
FROM #toc
WHERE completion = 1
SORT pagecount + observationcount DESC
`````

