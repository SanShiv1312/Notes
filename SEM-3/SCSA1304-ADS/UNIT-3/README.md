## `GRAPHS`
<p align = center>
<img src="https://media.geeksforgeeks.org/wp-content/cdn-uploads/undirectedgraph.png" width="45%" />
</p>

#### ->Introduction :
- A Graph is a `non-linear data structure` consisting of nodes and edges. The nodes are sometimes also referred to as vertices and the edges are lines or arcs that connect any two nodes in the graph.
- The interconnected objects are represented by points termed as `vertices`, and the links that connect the vertices are called `edges`.
- Data structure `Graph` is similar to tree , but differs from tree by having a **enclosed loop**.
- More than one path is allowed between two nodes.
- Any node of a graph can be a 'starting node'.   
- In simple words, graph is the collection of vertices and edges, but you can bring out the cycles or the loops.
-                                   **All trees are graphs, but not all graphs can be trees**

#### ->Directed graph :
- It is a graph, i.e., a set of objects that are connected together, where all the `edges are directed` and are `Undirected` from one vertex to another .
- A directed graph is sometimes called as `Digraph` or `Directed Network`.  
- Nodes connected with edges, and also the edges are assigned with some particular direction or points a direction.

<p align = center>
<img src="https://www.researchgate.net/profile/Hakan-Terelius/publication/265428782/figure/fig4/AS:669498856185861@1536632374551/A-directed-graph-with-7-nodes-and-9-edges.png" width="30%" />
</p>

#### ->Undirected graph :
- An undirected graph is graph, i.e., a set of objects that are connected together, where all the `edges are bidirectional`.
- An undirected graph is sometimes called an `undirected network`.
- Edges aren't assigned with any particular direction.

<p align = center>
<img src="https://www.techiedelight.com/wp-content/uploads/undirected-graph.png" />
</p>

**The connecting lines between two nodes in a graph has two different names, taking their nature into consideration**,
- **Directed Graph** will have an **Arc** and whereas `Undirected Graph` will have an `Edge`.  

#### -->Weighted graph :
- A graph having a weight or a number, associated with each edge.
- In Weighted graph, each branch is given a numerical weight.
- Used to compute the shortest path.
- The term 'Weight' refers to a factor or circumstance considered for taking the next step of action plan.
- Weighted graphs are used for applications where we need to take into account `some cost or measurement` between vertices of the graph.

<p align = center>
<img src="https://media.geeksforgeeks.org/wp-content/uploads/20210629004403/aTlYgNBLmuaKFgKV.png" width="30%" />
</p>

#### ->Strongly Connected graph :
- A directed graph is called strongly connected if there is a path in each direction between each pair of vertices of the graph.
- If every vertex is reachable from every other vertex then it comes under Strongly connected graph.
- Every pair of points should be mutually reachable.

<p align = center>
<img src="https://media.geeksforgeeks.org/wp-content/cdn-uploads/connectivity3-300x172.png" width="30%" />
</p>


#### -->Degree :
- Number of edges connected to a node.
- In an undirected graph, degree is just the count of lines(edges) around the nodes.

#### ->In-Degree :
- The number of edges coming into a vertex in a directed graph is termed as 'In-Degree'.
- If the In-Degree of a node is zero(0), then it is termed as `Source-node`.


<p align = center>
<img src="https://1.bp.blogspot.com/-UhB6yekFdGc/XPer-_GfGAI/AAAAAAAAAXY/hNn0TZZ1ZSAP79tyTtc2pz5fREq-OPT9gCLcBGAs/s1600/indegree_outdegree_node_centrality.png" />
</p>


#### ->Out-Degree :
- The number of arcs directed away from the vertex in a directed graph is termed as 'Out-Degree'.
- If the Out-Degree of a node is zero(0), then it is termed as `Sink-node`.

#### ->Sub-Graph :
- A graph whose vertices and edges are subsets of another graph.
- Considering graph G = (V, E) , then the Graph G' =(V', E') is considered as a Sub-Graph of G if V' ⊆ V and E' ⊆ E
- V refers to `Vertices` and E refers to `Edges` and '⊆' refers to `Subset`.

#### -->Cycle/Cyclic-Graph :
- A Cyclic graph is a graph containing at least one graph cycle.
- A Cycle in a directed graph is a directed path that originates and terminates at same node.
- A Cyclic graph is a directed graph that contains a path from at least one node back to itself.
- One which is not cyclic is termed as `Acyclic`  
- Generally a tree is stated as 'Connected Acyclic Graph'.
- Tree can also be stated as 'Directed Acyclic Graph' (DAG).

<p align = center>
<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRk_RUyWnrklp8gemrscPMZmV7u470ZkKyFDv2jRZnFj2AiXTLkRzFZl3BzPKB8kggQ5RY&usqp=CAU" />
</p>

### `REPRESENTATION OF GRAPHS`
#### --> **Multi Dimensional Array - Adjacency Matrix / Sparse Matrix**
- Adjacency matrix is a sequential representation
- An adjacency matrix is a square matrix used to represent a finite graph.
- It is used to represent which nodes are adjacent to each other. i.e. is there any edge connecting nodes to a graph.
- In this representation, we have to construct a nXn matrix A. If there is any edge from a vertex i to vertex j, then the corresponding element of A,   a^(i,j)= 1, otherwise a^(i,j)= 0
- Matrices that have the majority of their elements equal to zero are the Sparse Matrices.
- If there's no connection between two nodes, it will be marked as 'zero(0)' in the matrix.
- Similarly a connection between any two nodes, will be marked as 'one(1)' in the corresponding matrix.

<p align = center>
<img src="https://1.bp.blogspot.com/-tSAmvx42pII/Ux5EQxZukcI/AAAAAAAACLo/dPccUjxqb5o/s1600/Adjacency+Matrix+Representation+of+Directed+Graph.JPG" width="50%" />
</p>

#### --> **Incidence Matrix**
- Incidence matrix representation uses the concept of 'size of a matrix' and formulated as `IM = Total no. of Vertices / Total no. of Edges`
- For an example, if a graph has 4 vertices and 6 edges, then it can be represented using a matrix of (4X6) class.
Where,
i) columns = edges
ii) rows = vertices
- If a directed graph G consists of n vertices and m edges, then the incidence matrix is an n x m matrix C = [cij]  
- Incidence Matrix is generally used for Directed graphs
- This matrix is filled with either 0 or 1 or -1. Where,
0 is used to represent row edge which is `not connected` to column vertex.
1 is used to represent row edge which is `connected as outgoing edge` to column vertex.
-1 is used to represent row edge which is `connected as incoming edge` to column vertex

<p align = center>
<img src="https://www.researchgate.net/profile/Anirban-Mitra-12/publication/272172339/figure/fig3/AS:392001062227983@1470471744915/Fig-5-i-Directed-Graph-G-ii-Oriented-Incidence-Matrix-IV-CRITERIA-FOR-GROUPING.png" width="50%" />
</p>

#### --> **Adjacency List**
- An Adjacency list is a collection of unordered lists used to represent a finite graph
- For each vertex in the graph, we maintain the list of its neighbor vertices.
- An array of lists is used and the size of the array is equal to the number of vertices.

<p align = center>
<img src="https://i.stack.imgur.com/8PQ2E.png" width ="50%" />
</p>


### `TRAVERSAL OF GRAPHS`
- Visiting every node in a graph (only once) is generally termed as 'Traversing'.
- The process of visiting (checking and/or updating) each vertex in a graph.
- Such traversals are classified by the order in which the vertices are visited.
- Tree traversal is a special case of graph traversal.
