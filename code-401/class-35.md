# Graphs

## Vocabulary

- Vertex: or **node** is a data object that can have zero or more adjacent vertices
- Edge: a connection between two nodes or **vertices**
- Neighbor: adjacent nodes, connected via an **edge**
- Degree: the nubmer of edges connected to the vertex.
  
### Two kinds of graphs

- Directed: where the edges go in one single direction (like a linked list can only see what's in front of it, never what's behind it)
- Undirected: where the edges either don't go in any direction, or go in both directions.

### Complete vs Connected vs Disconnected

- Complete: graph where all nodes are connected to another node
- Connected: all verticies/nodes in graph have at least one edge (example: trees)
- Disconnected: where some verticies may not have edges. Contains some **islands** which are nodes without any edges/connections
  
### Acyclic vs Cyclic

- Acyclic: a directed graph that doesn't have **cycles** which is when there is a possible path where the node will eventually end up back at itself (like a *tree*)
- Cyclic: A graph that has cycles
  
### Graph representation

- Adjacency Matrix: 2 dimensional array. Uses '0' and '1' as the values at the juncture of rows and columns. If there is a connection between the vertices, it will be represented in the matrix by a value of 1, otherwise it will have a 0. *Sparse* graphs have very few connections (1's), while *dense* graphs have many connections.
- Adjacency List: collection of linked lists or array that lists all of the other vertices that are connected. Can be depicted by a linked list or by an array of arrays.

### Wighted Graphs

- A graph with numbers assigned to its edges.
- In a weight matrix, it would look similar to an adjacency matrix, but instead of 1's, it would contain the number that is assigned to the connection (or edge)
- In a weight list, it would look like a linked list or array of arrays, but instead of the node, it would contain the node as well as the weight of the edge.
  
## Traversals

  *Similar to traversals of trees.*

### Breadth First

- Similar to breadthFirst traversal of trees, except that it can be cyclic, which could leave you with an infinite loop. 
- Use of "flags" to indicate the node has been traversed already to prevent infinite loops.
-`BreadthFirst()` uses two methods: `Enqueue` that puts the node into the queue, `Dequeue` that removes the node from the queue.

### Depth First

- Set up to work with a stack rather than a queue
- Alrogithm is as follows: `Push` the root node onto the stack, start a while loop while the stack has a value in it, `Peek` at the top of the stack, if the top node has unvisited children, mark the top node as visited, and then `Push` any unvisited children onto the stack, if the top node does not have any unvisited children, `Pop` that node off the stack, and repeat until there are no more nodes.
- Examples of graphs in the real world: GPS and Mapping, also Netflix uses graphs for suggestions of products
