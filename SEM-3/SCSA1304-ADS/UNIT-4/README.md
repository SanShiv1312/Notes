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

- Just ensure that the graph shouldn't contain loops and parallel edges and select the edge with minimum weight, as we are following the greedy approach and moreover we're on our way for finding `MST` 😅

<p align='center'>
 <img src="https://aquarchitect.github.io/swift-algorithm-club/Minimum%20Spanning%20Tree/Images/kruskal.png" />
</p>


### `Prim's Algorithm`
 - Prim's Algorithm too follows the greedy approach for finding MST.
 - Prim's algorithm finds the subset of edges that includes every vertex of the graph such that the sum of the weights of the edges can be minimized.
 - Similar to kruskal's thing, we should ensure that there are no loops and parallel edges.
 - Choose any arbitrary vertex as root node and start checking all the possible connections.
 - Then choose the edge with minimum weight among the possible routes.
 - After reaching to one node(say B) from the other(say A), you have the check the possible minimum route from both the nodes(A and B).
 - If multiple routes of same path have the same weight, select any one of those.
 - Continue this process until the sub graph(MST) includes all vertices of given graph.
 <p align='center'>
  <img src="https://aquarchitect.github.io/swift-algorithm-club/Minimum%20Spanning%20Tree/Images/prim.png" />
 </p>


### `Sollins Algorithm or Boruvka’s Algorithm`
- Boruvka’s algorithm is also a Greedy algorithm just like the Kruskal's and the Prim's Algorithms.
- `1)` Input is a connected, weighted and un-directed graph.
- `2)` Initialize all vertices as individual components (or sets).
- `3)` Initialize MST as empty.
- `4)` While there are more than one components, do following
   for each component.
      a)  Find the closest weight edge that connects this
          component to any other component.
      b)  Add this closest edge to MST if not already added.  
- `5)` Return MST.  
