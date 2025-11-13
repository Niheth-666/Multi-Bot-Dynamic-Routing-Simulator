# 🤖 Multi-Bot Dynamic Routing Simulator

A C++ simulation that visualizes **multiple autonomous bots** navigating a warehouse grid using **Dijkstra’s algorithm** for dynamic routing.  
Each bot independently finds and follows the shortest path while avoiding collisions, waiting when blocked, and dynamically re-planning routes.

---

## ✨ Features

-  **Dynamic Path Planning** — Dijkstra’s shortest path algorithm  
-  **Random Obstacle Generation** — realistic warehouse setup  
-  **Multiple Bots** — each with unique start and goal positions  
-  **Re-planning & Waiting Logic** when conflicts occur  
-  **Color-Coded Visualization** — terminal-based live animation  
-  Customizable **grid size** and **number of bots**

---

## Example Simulation

Each frame displays a grid:
- `#` → obstacle  
- `.` → free space  
- `W` → start  
- `G` → goal  
- `A`, `B`, `C`... → bots in motion

Example terminal output:

