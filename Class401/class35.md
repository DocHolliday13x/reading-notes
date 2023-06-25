# Class 35 Reading: Graphs

## Resources

- [Graphs](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-35/resources/graphs.html)

## Implementation: Graphs

To turn in your reading “Reply” to this discussion by teaching something that you learned. Then review what one of your classmates learned, and leave a comment.

Some ideas for how you might want to teach:

- Use an analogy
- Explain a detail in depth
- Use WHY, WHAT, HOW structure
- Tutorial / walk through an example
- Write a quiz
- Create a vocabulary/definition list
- Write a cheat sheet
- Create a diagram / visualization / cartoon of a topic
- Anthropomorphize the concepts, and write a conversation between them
- Build a map of the information
- Construct a fill-in-the-blank worksheet for the topic

## Graph Vocabulary

1. Vertex - A vertex, also called a “node”, is a data object that can have zero or more adjacent vertices.
2. Edge - An edge is a connection between two nodes.
3. Neighbor - The neighbors of a node are its adjacent nodes, i.e., are connected via an edge.
4. Degree - The degree of a vertex is the number of edges connected to that vertex.
5. Directed vs Undirected - A directed graph is a graph where each edge is directed. An undirected graph is a graph where each edge is undirected or bi-directional.
6. Complete vs Connected vs Disconnected - A complete graph is when all nodes are connected to all other nodes. A connected graph is graph that has all of vertices/nodes have at least one edge. A disconnected graph is a graph where some vertices may not have edges.
7. Acyclic vs Cyclic - An acyclic graph is a directed graph without cycles. A cycle is when a node can be traversed through and potentially end up back at itself. A Cyclic graph is a graph that has cycles.
8. Graph Representation:

    - Adjacency Matrix - An adjacency matrix is represented through a 2-dimensional array. If there are n vertices, then we are looking at an n x n Boolean matrix (all values are either true or false). The row represents the “from” vertex and the column represents the “to” vertex. The value stored in the matrix is true if there is an edge.
    - Adjacency List - An adjacency list is the most common way to represent graphs. An adjacency list is a collection of linked lists or array that lists all of the other vertices that are connected. Adjacency lists make it easy to view if one vertices connects to another.
9. Weighted Graphs - A weighted graph is a graph with numbers assigned to its edges. These numbers are called weights.
10. Graph Traversal:

    - Breadth First - Breadth first traversal iterates through the graph by going through each level of the graph node-by-node. In order to do this, we need to keep track of each node that we visit. The best way to track this is by using a Queue.
    - Depth First - Depth first traversal is when you traverse down the graph as far as you can go and then you backtrack until you find a new path to traverse. The best way to track this is through recursion.

### Thank You for Coming to My TED Talk on Graphs

![GIF](https://media.giphy.com/media/4qbCWW4WwDpoYtzj6S/giphy.gif)
