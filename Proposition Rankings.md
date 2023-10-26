A listing of the propositions ordered by my assumed level of effort made by Peters. This is another way for me to view these propositions (than their numbered order) and I am using this ranking view as the order of further completion of my note taking in Obsidian. 

This ranking assumes that a greater level of effort was given to those propositions containing the most content. Here propositions are shown in order of pagecount + observationcount.  
PageCount is the number of pages given to a proposition in the hard copy of the book.  ObservationCount is the number of observations Peters made on the proposition.
Completion is a number estimating how much of the proposition received notes by me in Obsidian (1=100%). Most of my notes are merely quotations from Peters work.
NOTE: The hard copy book contains notes. The Kindle version does not.  I estimate that the notes consist of almost half the size of the book.

`````dataview
TABLE pagecount AS PageCount, observationcount AS ObservationCount, completion AS Completion
FROM #toc
WHERE id != null
SORT pagecount + observationcount DESC, id 
`````

