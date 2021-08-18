## `GRAPHS`

#### Introduction :
- A Graph is a `non-linear data structure` consisting of nodes and edges. The nodes are sometimes also referred to as vertices and the edges are lines or arcs that connect any two nodes in the graph
- The interconnected objects are represented by points termed as `vertices`, and the links that connect the vertices are called `edges`
- Data structure `Graph` is similar to tree , but differs from tree by having a **enclosed loop**.
- In simple words, graph is the collection of verticies and edges, but you can bring out the cycles or the loops.
                                   **All trees are graphs, but not all graphs can be trees**

##### Directed graph :
- It is a graph, i.e., a set of objects that are connected together, where all the `edges are directed` from one vertex to another .
- A directed graph is sometimes called as `Digraph` or `Directed Network`.  
- Nodes connected with edges, and also the edges are assigned with some particular direction or points a direction.

##### Undirected graph :
- An undirected graph is graph, i.e., a set of objects that are connected together, where all the `edges are bidirectional`.
- An undirected graph is sometimes called an `undirected network`
- Edges aren't assigned with any particular direction

**The connecting lines between two nodes in a graph has two different names, taking their nature into consideration**,
- **Directed Graph** will have an **Arc** and whereas `Undirected Graph` will have an `Edge`  

##### Weighted graph :
- A graph having a weight or a number, associated with each edge.
- In Weighted graph, each branch is given a numerical weight
- The term Weight refers to a factor or circumstance considered for taking the next step of action plan.
- Weighted graphs are used for applications where we need to take into account `some cost or measurement` between vertices of the graph.

##### Strongly Connected graph :
- A directed graph is called strongly connected if there is a path in each direction between each pair of vertices of the graph.
- If every vertex is reachable from every other vertex then it comes under Strongly connected graph.
- Every pair of points should be mutually reachable.
