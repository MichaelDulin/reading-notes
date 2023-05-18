# Graphs

[Back to main](https://michaeldulin.github.io/reading-notes)

**Graphs Resources**
- [Graphs](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-35/resources/graphs.html)

****

**Common Terminology**
1. Vertex
  -  vertex, also called a “node”, is a data object that can have zero or more adjacent vertices.
2. Edge
  - An edge is a connection between two nodes.
3. Neighbor
  - The neighbors of a node are its adjacent nodes, i.e., are connected via an edge.
4. Degree
  - The degree of a vertex is the number of edges connected to that vertex.

****

**Directed vs Undirected**

1. Undirected Graphs
- Where each edge is undirected or bi-directional.
  - the undirected graph does not move in any direction

2. Directed Graphs
  - AKA Diagraph
  - Where every edge is directed
    - nodes have direction  


****

**Complete vs Connected vs Disconnected**
1. Complete
  - A complete graph is when all nodes are connected to all other nodes.

2. Connected
  - A connected graph is graph that has all of vertices/nodes have at least one edge.

3. Disconnected
  - A disconnected graph is a graph where some vertices may not have edges.


****

**Acyclic vs Cyclic**
1. Acyclic
  - An acyclic graph is a directed graph without cycles.
    - A cycle is when a node can be traversed through and potentially end up back at itself.
    - A directed acyclic graph is also called a DAG. This can also be represented as what we know as a tree.

2. Cyclic
  - A Cyclic graph is a graph that has cycles.
    - A cycle is defined as a path of a positive length that starts and ends at the same vertex

****

**Graph Representation**
- Graphs are represented through:


  1. Adjacency Matrix:
    - represented through a 2-dimensional array
    - if there are n vertices, then we are looking at an n x n Boolean matrix
    - Each row/col represents each vertex 
    - Elements in both the col and row must add up to 1 
      - if there is an edge that connects the two or zero if there isnt a connection
    - Spare graphs:
      - Few connections 
    - Dense graphs:
      - Many connections 

  2. Adjacency List:
    -  Most common way to represent graphs
    -  An adjacency list is a collection of linked lists or array that lists all of the other vertices that are connected
    -  Adjacency lists make it easy to view if one vertices connects to another
  
****

**Weighted Graphs**
- A graph with numbers assigned to its edges
  - These numbers are called weights 

****

**Traversing**
- Similar to Tree
  1. Breadth First:
    - Enqueue the declared start node into the Queue.
    - Create a loop that will run while the node still has nodes present.
    - Dequeue the first node from the queue
    - If the Dequeue‘d node has unvisited child nodes, add the unvisited children to visited set and insert them into the queue.
    
  2. Depth First:
    - Push the root node into the Stack and mark as visited.
    - Start a while loop that runs as long as the stack is not empty
    - Pop the top node off of the stack and check its neighbors
    - if a neightor hasnt been visited, push it onto the stack and mark as visited.
    - Repeat until the stack is empty

****

**Use Cases of Graphs**
1. GPS and Mapping
2. Driving Directions
3. Social Networks
4. Airline Traffic
5. Netflic uses graphs for suggestions of products




















