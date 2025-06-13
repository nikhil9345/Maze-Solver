# 🧭 Maze Solver using OpenCV and A* Algorithm in Python

This project implements a **Maze Solver** using **Python**, **OpenCV**, and the **A\* (A-Star) Pathfinding Algorithm**. The program processes a maze image, identifies the start and end points, and uses the A\* algorithm to find and display the optimal path through the maze.

---

## 🚀 Features

- Load and process a maze image using OpenCV
- Convert the image into a binary grid
- Detect the start and end points of the maze
- Implement the A\* algorithm to find the shortest path
- Visualize the solution path on the original maze

---

## 🧠 How It Works

1. **A\* Algorithm**:
   - A heuristic-based search (using Manhattan or Euclidean distance)
   - Explores nodes based on the cost to reach them and an estimated cost to the goal
   - Guarantees the shortest path if the heuristic is admissible

2. **Visualization**:
   - Draws the calculated shortest path on the original maze image using OpenCV drawing functions

---

## 📁 Files

- `Maze Solver.ipynb` - Jupyter Notebook containing the complete implementation
- `maze.png` - (Optional) Sample maze image for testing

---

## 🛠️ Requirements

Install dependencies using:

```bash
pip install opencv-python numpy
