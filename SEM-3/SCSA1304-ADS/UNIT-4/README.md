#### Spanning Tree
- Given a connected and undirected graph, a spanning tree of that graph is a subgraph that is a tree and connects all, the vertices together.
- A spanning tree is a subset of Graph G, which has all the vertices covered with minimum possible number of edges.
##### Properties :
- A connected graph can contain more than one spanning tree.
-  The spanning trees which are minimally connected or we can say that the tree which is having a minimum total edge weight would be considered as the minimum spanning tree.
- All the possible spanning trees that can be created from the given graph G would have the same number of vertices, but the number of edges in the spanning tree would be equal to the number of vertices in the given graph minus 1.
- The spanning tree does not contain any loops and parallel edges.
- `*Loops*` refers to the edges that has the same start and ending vertex and `*parallel edges*` are the multiple edges between the same vertices.
- Each connected and undirected graph contains at least one spanning tree.
- The disconnected graph does not contain any spanning tree.

<p align="center">
<img src="https://i2.wp.com/algorithms.tutorialhorizon.com/files/2018/05/Minimum-Spanning-Tree-basics-1.png?ssl=1" />
</p>

#### `Minimum Spanning Tree (MST)`
- Spanning tree of graph whose sum of weights of edges is minimum.
- A graph can have more than one MST.
- For a Graph containing 'n' vertices, there will a MST with 'n' vertices and 'n-1' edges.
- MST is the one spanning tree that contains least weight when added combinedly.

### `Kruskal's Algorithm`
- Kruskal's algorithm finds a minimum spanning forest of an undirected edge-weighted graph.
- If the graph is connected, it finds a minimum spanning tree.
- In this algorithm, arrange all the edges in increasing order of their weights
#### Steps to be followed for finding the MST :
- `1)` Sort all the edges in non-decreasing order of their weight.
- `2)` Pick the smallest edge. Check if it forms a cycle with the spanning tree formed so far. If cycle is not formed, include this edge. Else, discard it.
- Proceed only if there are no loops(cycles) and parallel edges(multiple routes for a same destiny).
- In case of parallel edges, keep the one with the less weight.
- `3)` Repeat the above step (step-2) until there are (V-1) edges in the spanning tree where V is the number of vertices in the given graph.
- The term 'Loops' can also refer to the edges that start and end at the same vertex.
<p align='center'>
Sample demonstration for loops where 'a' is a vertex : <img src="https://upload.wikimedia.org/wikipedia/commons/b/b4/Self-loop.png" width="50" />
</p>
