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

<img width="562" height="836" alt="Screenshot 2025-11-13 184516" src="https://github.com/user-attachments/assets/d166849f-4d21-4349-a053-164865f4f8d5" />

<img width="557" height="855" alt="Screenshot 2025-11-13 184538" src="https://github.com/user-attachments/assets/e9a177f4-4b30-4b16-be74-d359fbab5188" />

<img width="671" height="865" alt="Screenshot 2025-11-13 184602" src="https://github.com/user-attachments/assets/c19a420f-9307-4dcb-81c2-fc81bf44735f" />

<img width="556" height="829" alt="Screenshot 2025-11-13 184620" src="https://github.com/user-attachments/assets/1d76152e-9dc2-4e2a-9c02-5ac3b7a1d3eb" />
