# nhscharts
Automated  analysis and re-basing of  runcharts at scale.


Run charts  and SPC charts are used extensively in quality improvement within the UK NHS.

Run charts are simple to construct, and analyse using run chart rules.
However over time, a signal of improvement may require a run-chart median to be rebased. 

Rationale:

The analysis and re-basing of improvement medians quickly becomes labour intensive as the QI programme evolves - and though enterprise level database software can be used to store the raw data, their associated reporting systems are usually ill suited to the task of analysing QI data using run chart rules or SPC rules.


This package automatically creates rebased run charts, based on run chart rules commonly used in the UK healthcare.
This can be a single chart, or faceted small multiples. 
All sustained runs of improvement, in the desired direction, will be highlighted and the median re-phased, using the points that contributed to the run. 
Non useful observations (points on the median) are ignored for the purposes of identifying a sustained improvement and are not highlighted. 

 
 ![alt tag](https://user-images.githubusercontent.com/3278367/27238864-81353a30-52c6-11e7-8871-3ef950f90178.PNG)
