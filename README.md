# findMinCutGraph
Graphs is one of the popular structures and finds applications in various fields like networking, finding communities etc.
Here I have attempted to implement one of the algorithms used in graphs that is finding the min cut using the contraction algorithm approach.
The graph here is represented by an adjacency array.
Each line has a list of vertices starting from 1 to 200, and next to that is the list of vertices the graph is connected to.
This is a randomized algorithm which will randomly select two vertices and merge them, during the process of merging all self loops are eliminated. This is done till only two vertices are remaining and we count the number of edges between these two vertices to get the min cut in the given graph

From formal analysis of the contraction algorithm we do need to run n^2log(n) times random iteration to get atleast a one correct answer, here I was able to get the result for the graph in n iterations.




