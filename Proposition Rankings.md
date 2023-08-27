This assumes that a greater level of effort was given to those propositions containing the most content.  PageCount is the number of pages given to a proposition in the hard copy of the book.  ObservationCount is the number of observations Peters made on the proposition.
NOTE: The hard copy book contains notes. The Kindle version does not.  I estimate that the notes consist of almost half the size of the book.

`````dataview
TABLE pagecount AS PageCount, observationcount AS ObservationCount
FROM #toc
SORT pagecount DESC, observationcount DESC
`````
