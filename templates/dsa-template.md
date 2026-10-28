# Breadth-First Search (BFS)

## 1. Definition

What is BFS?

## 2. Core Idea

Explain the algorithm in your own words.

## 3. Data Structure Used

Queue.

## 4. Algorithm

1. Add the starting node to the queue.
2. Mark it as visited.
3. Remove a node from the front of the queue.
4. Process its unvisited neighbours.
5. Mark each neighbour as visited and enqueue it.
6. Repeat until the queue is empty.

## 5. Java Implementation

Link to the Java solution.

## 6. Complexity

**Time:** O(V + E) using an adjacency-list representation.

**Space:** O(V) for the visited structure and queue in the usual implementation.

Here, V represents vertices and E represents edges.

## 7. When Should I Use BFS?

* Finding shortest paths in unweighted graphs.
* Level-order traversal.
* Finding connected components.
* Exploring states level by level.

## 8. Common Mistakes

* Forgetting to track visited nodes.
* Marking nodes as visited too late.
* Confusing BFS with DFS.
* Assuming BFS gives shortest paths in weighted graphs with arbitrary edge weights.

## 9. Interview Questions

* How does BFS work?
* Why does BFS find shortest paths in unweighted graphs?
* What is the difference between BFS and DFS?
* How can BFS be used to find connected components?

## 10. Revision Check

* [ ] Explain BFS without notes.
* [ ] Implement BFS independently.
* [ ] Analyse time and space complexity.
* [ ] Solve a new BFS problem.
