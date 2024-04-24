Jack Lafond
Week 14 Reflection
CS 573
===

Link to Paper:
---
https://ieeexplore.ieee.org/document/7539669

Reflection:
---
In this paper the researchers develop a new technique for visualizing many-to-many geographic flow data sets, and use studies to test its effectiveness. The researchers explain that visualizing many-to-many flows can apply to a broad spectrum of industries, however, the nature of these datasets is often dense making it hard to crate effective visualizations that scale well. Often times people use a matrix approach called origin-destination matrix, that shows the total flow from source to destination in each cell. However, these visualizations lack the geographical information associated with locations, and in recent years people have used OD maps, whiich use two level treemaps and OD matrices to better display the geographic information. They explain that these OD maps have not been quantitatively studied anc hope to assess them in this paper. THey also introduce their own solution, MapTrix, which uses an OD matrix connected to the inflow and outlfow geographical maps via lines inorder to associate cells with their geographic location. This is similar to looking to the Flowstrates technique. The matrix is rotated 45 degrees so that both maps can be placed to the left of it and lines can be charted nearly, without crossing, to the associated in flow and outflow rows/columns. They introduce an algorithm for ordering the labels such that lines do not, or minimally cross when connected to the OD matrix. They also use some other simple elements like dot size to indicate the relative inflow/outlfow of a geographic area, and use a bar chart to compare the aggregations of each location's in and outflows. They then conducted a user study to evaluate their new visualizations performance against OD maps, and regular flow maps. They found that their visualization performed much better than regular flow maps and comparable to OD maps, with user preferring their new technique. 

Overall I really liked how they used some simple techniques to enhance the function of their new vis. For exmaple rotating the matrix so that both maps could be displayed to the left I found to make it look much more neat. I also realy liked that they included the dot size encoding and bar charts to make it easy to compare some useful aggragations. Another thing I liked was that they actually tested this new technique against others. Most of the papers I have read so far, when a new technique is created it is just tested against itself and the authors evaluate that. In this paper they tested it against other techniques to have a better comparison for how much value this new technique brings.
