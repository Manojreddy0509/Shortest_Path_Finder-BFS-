# Maze Pathfinding Visualization (Python + Curses)

This project is a **BFS (Breadth-First Search) maze solver** implemented in Python using the `curses` library for terminal-based visualization.

The program finds a path from a **start position (`O`)** to an **end position (`X`)** inside a maze, avoiding walls (`#`). The path is highlighted in **red** during visualization.

---

## 📸 Preview

When you run the program, you’ll see:
- **Blue walls and empty spaces**
- **Red path** showing the BFS search progress

---

## 🚀 Features
- **Breadth-First Search (BFS)** algorithm for shortest path finding
- **Terminal visualization** using `curses`
- **Step-by-step animation** of the search process
- Fully configurable maze layout

---

📦 Installation & Usage
1️⃣ Clone the Repository
bash
Copy
Edit
git clone https://github.com/Manojreddy0509/Shortest_Path_Finder(BFS).git
cd Shortest_Path_Finder(BFS)
2️⃣ Run the Program
bash
Copy
Edit
python3 path_finder.py
🎯 Controls
The visualization runs automatically step-by-step.

Press any key to exit once the path is found.

🛠 Requirements
Python 3.x

curses module (pre-installed in most Python distributions)

📚 How It Works
Find Start: Locates O in the maze.

BFS Search: Uses a queue to explore the maze level-by-level.

Path Tracking: Keeps track of visited cells and the current path.

Visualization: Updates the maze in the terminal every 0.4 seconds.
