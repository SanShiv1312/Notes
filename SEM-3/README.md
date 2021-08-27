#### Spanning Tree
- A tree T is a spanning tree of G if T is a spanning `sub-graph` of G.
- All the vertices will be covered with minimum possible number of edges
- Every spanning  tree of a connected n-node graph G has `(n-1)` arcs.
- By this definition, we can draw a conclusion that `every connected and undirected Graph` G has at least one spanning tree.
- A disconnected graph does not have any spanning tree, as it cannot be spanned to all its vertices.
- Spanning tree is basically used to find a `minimum path to connect all nodes in a graph`

#### General Properties of Spanning Tree :

- A connected graph G can have more than one spanning tree.
- All possible spanning trees of graph G, have the same number of edges and vertices.
- The spanning tree does not have any cycle (loops).
- Removing one edge from the spanning tree will make the graph disconnected, i.e. the spanning tree is minimally connected.
- Adding one edge to the spanning tree will create a circuit or loop, i.e. the spanning tree is maximally acyclic.

#### Mathematical Properties of Spanning Tree :

- Spanning tree has n-1 edges, where n is the number of nodes (vertices).
- From a complete graph, by removing maximum e - n + 1 edges, we can construct a spanning tree.
- A complete graph can have maximum nn-2 number of spanning trees.
- * Civil Network Planning, Computer Network Routing Protocol, Cluster Analysis are the basic applications of spanning tree.

### Minimum Spanning Tree (MST)
- Spanning tree of graph whose sum of `weights of edges is minimum`.
- Graph that connects all the vertices together, `without any cycles` and with the minimum possible total edge weight.
- A graph may have more than one minimum spanning trees(MST).
- For getting a MST for a given Spanning tree, we have two Algorithms and they are **KRUSKAL'S ALGORITHM** and **PRIM'S ALGORITHM**.

### `KRUSKAL'S ALGORITHM`
- Kruskal's algorithm finds a minimum spanning forest of an undirected edge-weighted graph.
### B

- `STEP-1 :` Remove all the loops and the parallel edges from the graph given and in case of removing the parallel edges, remove the one with high weight and remove the self loops, even if it has the least weight of the graph given.
- `STEP-2 :` Firstly chose the node with the least weight node and then arrange all the edges in increasing order of their edge weights and consider the prime rule that `cycles or loops shouldn't appear while joining the nodes that was chosen`
- `STEP-3 :` Repeat the step-2 until you reach  `n-1` edges.
