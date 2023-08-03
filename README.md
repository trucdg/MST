# 🌴 Minimum Spanning Tree
- A minimum spanning tree (MST) is a spanning tree with the smallest weight among all the possible spanning trees.
- To find MST in a graph, we can use 2 **greedy** algorithm:
  1. Kruskal's Algorithm
  2. Prim's Algorithm

## 🦉 Kruskal's Algorithm:
In Kruskal's algorithm, sort all edges of the given graph in increasing order of their weight. Then keeps on adding new edges and nodes into the MST if the newly added adge doesn't form a cycle. It picks the minimum weighted edge at first and the maximum weighted edge at last.
