# Pathfinding and Maze Generation Visualizer

A graphical user interface built using the **React framework** to visualize and analyze classic **pathfinding algorithms** and **maze generation algorithms** on a grid.

This project goes beyond simple animations by providing **algorithm analytics** and a **step-by-step execution mode** to inspect how algorithms actually work internally.

Feel free to fork or download this project and use it as a base to create your own visualizer.

[🔗 Live Demo – Try the Visualizer](https://krishar01.github.io/pathfinding-visualizer/)


---

## 📽 Sample (Dijkstra's Algorithm with Recursive Division Maze)

<p align="center">
  <img src="sample.gif" width="880">
</p>

---

## 🔍 Pathfinding Algorithms
1. Dijkstra's Algorithm  
2. A* Algorithm  
3. Greedy Best First Search  
4. Bidirectional Greedy Search  
5. Breadth First Search (BFS)  
6. Depth First Search (DFS)  
7. Random Walk  

---

## 📊 Algorithm Analytics (Added Feature)

The visualizer tracks **real-time performance metrics** for selected algorithms:

- **Nodes Visited** – size of the explored search space  
- **Shortest Path Length** – number of nodes in the final path  
- **Execution Time (ms)** – algorithm runtime (excluding animation)

These analytics enable **direct comparison between Dijkstra, and A\*** on identical grids.

---

## 🧠 Step-by-Step Execution Mode (Added Feature)

A dedicated **Step Mode** is implemented for **Dijkstra’s Algorithm** to allow detailed inspection of the algorithm’s behavior.

### Step Mode Visualization States:
  
- 🟡 **Yellow** – nodes visited earlier (step reminder)  
- 💗 **Pink** – final shortest path  

### Why Step Mode Matters:
Unlike standard animations that replay a completed result, step mode:
- Reveals the **decision-making process** of the algorithm  
- Shows the exact **order of node expansion**  
- Helps understand *why* certain paths are chosen  

This transforms the project into an **algorithm inspection and learning tool**, not just a visual demo.

---

## 🧱 Maze Generation Algorithms
1. Random Maze  
2. Recursive Division Maze  
3. Vertical Division Maze  
4. Horizontal Division Maze  

---

## 🛠 Tech Stack
- React (JavaScript)
- HTML
- CSS

---
Additional features (step-mode,algorithm analytics) and enhancements implemented by Krishna Sharma.


## 🧪 Running the Project Locally

```bash
git clone https://github.com/<your-username>/pathfinding-visualizer.git
cd pathfinding-visualizer
npm install
npm start
