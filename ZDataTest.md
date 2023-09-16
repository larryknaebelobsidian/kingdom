
`````dataview
TABLE pagecount AS PageCount, observationcount AS ObservationCount, completion AS Completion
FROM #toc
SORT pagecount + observationcount DESC
`````

