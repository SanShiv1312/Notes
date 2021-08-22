## `GRAPHS`
<p align = center>
<img src="http://www.btechsmartclass.com/data_structures/ds_images/Graph%201.png" />
</p>

#### ->Introduction :
- A Graph is a `non-linear data structure` consisting of nodes and edges. The nodes are sometimes also referred to as vertices and the edges are lines or arcs that connect any two nodes in the graph.
- The interconnected objects are represented by points termed as `vertices`, and the links that connect the vertices are called `edges`.
- Data structure `Graph` is similar to tree , but differs from tree by having a **enclosed loop**.
- More than one path is allowed between two nodes.
- Any node of a graph can be a 'starting node'.   
- In simple words, graph is the collection of vertices and edges, but you can bring out the cycles or the loops.
-                                   **All trees are graphs, but not all graphs can be trees**

##### ->Directed graph :
- It is a graph, i.e., a set of objects that are connected together, where all the `edges are directed` and are `Undirected` from one vertex to another .
- A directed graph is sometimes called as `Digraph` or `Directed Network`.  
- Nodes connected with edges, and also the edges are assigned with some particular direction or points a direction.

<p align = center>
<img src="https://lh3.googleusercontent.com/proxy/b0KRKxKiaX9eMtqibc2MlKDpTpn2o71bHODtnI8h_ardthskZJx5rCHC8Qvy3vSs-FdUmS0QvbmuSsA7G31y4bCxNhycIEhv1AZZjzyrd-TlwepKEw" />
</p>

##### ->Undirected graph :
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
<img src="https://www.clipartmax.com/png/middle/97-979844_directed-weighted-ex1-directed-weighted-graph.png" width="30%" />
</p>

##### ->Strongly Connected graph :
- A directed graph is called strongly connected if there is a path in each direction between each pair of vertices of the graph.
- If every vertex is reachable from every other vertex then it comes under Strongly connected graph.
- Every pair of points should be mutually reachable.

#### -->Degree :
- Number of edges connected to a node.
- In an undirected graph, degree is just the count of lines(edges) around the nodes.

##### ->In-Degree :
- The number of edges coming into a vertex in a directed graph is termed as 'In-Degree'.
- If the In-Degree of a node is zero(0), then it is termed as `Source-node`.

##### ->Out-Degree :
- The number of arcs directed away from the vertex in a directed graph is termed as 'Out-Degree'.
- If the Out-Degree of a node is zero(0), then it is termed as `Sink-node`.

##### ->Sub-Graph :
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

#### -->`Representation of Graph` :
**Multi Dimensional Array - Adjacency Matrix / Sparse Matrix**
- Adjacency matrix is a sequential representation
- An adjacency matrix is a square matrix used to represent a finite graph.
- It is used to represent which nodes are adjacent to each other. i.e. is there any edge connecting nodes to a graph.
- In this representation, we have to construct a nXn matrix A. If there is any edge from a vertex i to vertex j, then the corresponding element of A, a^(i,j)= 1, otherwise a^(i,j)= 0
- Matrices that have the majority of their elements equal to zero are the Sparse Matrices.
