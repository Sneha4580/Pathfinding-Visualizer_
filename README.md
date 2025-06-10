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

![Screenshot 2025-06-10 122851](https://github.com/user-attachments/assets/4d78e59b-154c-4c0b-ab16-a43dbdd4eea1)






### BFS Algorithm in Action


![Screenshot 2025-06-09 233817](https://github.com/user-attachments/assets/8c6061fc-052b-4372-a83c-b76c3e9cb139)





### DFS Algorithm in Action


![Screenshot 2025-06-09 233939](https://github.com/user-attachments/assets/f271652b-606c-4552-948a-688d30fa85a1)




### Algorithm Selection Interface

The user interface allowing selection between Dijkstra's, BFS, and DFS algorithms.

![Screenshot 2025-06-10 122851](https://github.com/user-attachments/assets/e492d451-a677-446d-a0a7-7a7bb454688e)



---

## 🚀 Getting Started


### Prerequisites

You'll need to have [Node.js](https://nodejs.org/en/download/) and [npm](https://www.npmjs.com/get-npm) (Node Package Manager) installed on your machine.

* *Node.js:* Ensure you have a stable version (e.g., v16.x or v18.x recommended). Older versions might require setting NODE_OPTIONS (see below).
* *npm:* Comes bundled with Node.js.
