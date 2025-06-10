# Pathfinding Visualizer

An interactive web application built with React to visualize the mechanics of various pathfinding algorithms on a grid. This tool allows users to set start and end points, add walls, and observe how different algorithms find a path from the start to the finish node.

---

## ✨ Features

* *Algorithm Visualization:* Watch algorithms explore the grid step-by-step.
* *Multiple Algorithms:* Includes implementations for:
    * *Dijkstra's Algorithm:* Finds the shortest path on a weighted or unweighted graph. (Treats all unblocked cells as weight 1 for simplicity in this visualizer).
    * *Breadth-First Search (BFS):* Finds the shortest path on an unweighted graph.
    * *Depth-First Search (DFS):* Explores as far as possible along each branch before backtracking. (Does not guarantee the shortest path).
* *Interactive Grid:*
    * Toggle walls on the grid by clicking and dragging your mouse.
    * Clear the grid to start a new visualization.
* *Real-time Animation:* See the pathfinding process unfold with animations.

---

## 📸 Screenshots

Witness the visualizer in action, showcasing pathfinding and algorithm selection:

### Dijkstra's Algorithm in Action

A clear path found using Dijkstra's algorithm, showing visited nodes and the shortest path.

(https://github.com/user-attachments/assets/c3917ce2-4d0b-4ce6-acf2-6b7b83336fef)




### BFS Algorithm in Action

A clear path found using BFS algorithm, showing visited nodes and the shortest path.

(https://github.com/user-attachments/assets/ba5ade5d-e159-4aba-954b-bd2c630ad7f7)



### DFS Algorithm in Action

A clear path found using DFS algorithm, showing visited nodes and the shortest path.

![Dijkstra's Algorithm Visualization](images/Screenshot%202025-06-09%20233817.png)



### Algorithm Selection Interface

The user interface allowing selection between Dijkstra's, BFS, and DFS algorithms.

(https://github.com/user-attachments/assets/df9214df-387f-46a3-964e-77a02aaef4a5)



---

## 🚀 Getting Started


### Prerequisites

You'll need to have [Node.js](https://nodejs.org/en/download/) and [npm](https://www.npmjs.com/get-npm) (Node Package Manager) installed on your machine.

* *Node.js:* Ensure you have a stable version (e.g., v16.x or v18.x recommended). Older versions might require setting NODE_OPTIONS (see below).
* *npm:* Comes bundled with Node.js.
