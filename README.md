# Bidirectional-Search

## Overview

This repository contains an implementation of the Bidirectional Depth-First search (DFS) algorithm. Bidirectional DFS is a graph traversal algorithm that simultaneously explores a graph from both the start and goal nodes, meeting in the middle. This approach can be more efficient in certain scenarios than traditional DFS, especially when the graph is large or the goal node is known.

## Algorithm Description

Bidirectional DFS works by running two DFS searches concurrently:
1. One search starts from the initial node and explores forward.
2. The other search starts from the goal node and explores backward.

The algorithm terminates when the two searches meet at a common node, indicating that a path from the start to the goal has been found.


### Advantages
- **Efficiency**: Bidirectional DFS can be faster in many cases than traditional DFS, especially when the graph is large or the goal node is known.
- **Space Complexity**: It can reduce the space complexity compared to a unidirectional DFS, as the search space is divided between the two searches.

### Disadvantages
- **Implementation Complexity**: Implementing bidirectional DFS can be more complex than a standard DFS due to the need to manage two separate searches and ensure they meet correctly.
- **Graph Requirements**: The graph must be traversable in both directions (i.e., it must be undirected or have reverse edges available).




 **Clone the repository**:
   ```bash
   git clone https://github.com/Arka056/Bidirectional-Search.git
   cd Bidirectional-Search
   ```

   
