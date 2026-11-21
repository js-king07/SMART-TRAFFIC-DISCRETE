# GraphFlow – Smart Traffic Management System
### Design of a Smart Traffic Management System Using Discrete Graph Theory
Course: UBA0405 – Discrete Mathematics

A responsive, dark-themed static web application demonstrating:
- **Module 1 – Graph Modeling & Topology Construction:** intersections as vertices, roads as edges, adjacency list and weighted graph visualization.
- **Module 2 – Real-Time Traffic Flow & Dynamic Edge Weighting:** simulated congestion inputs dynamically change road weights.
- **Module 3 – Signal Phase Optimization & Route Guidance:** proportional green-time suggestion and Dijkstra shortest-path routing.
- Static vs dynamic route-cost comparison chart.

## Run locally
Open `index.html` in a modern browser. No installation, backend, database or API key is required.

## Deploy on Render
1. Create a GitHub repository, for example `smart-traffic-graph-theory`.
2. Upload `index.html`, `style.css`, `script.js`, and `README.md` directly to the repository root.
3. In Render, choose **New + → Static Site** and connect the repository.
4. Configure:
   - Branch: `main`
   - Root Directory: leave blank
   - Build Command: leave blank
   - Publish Directory: `.`
5. Click **Create Static Site**. Wait for the status to become **Live**, then open the `onrender.com` URL.

If you place the files in a subfolder instead, set Root Directory to that exact subfolder name and Publish Directory to `.`.

## Important scope note
This is an educational simulation using sample road topology and user-adjustable traffic levels. It does not ingest live traffic feeds, control real traffic lights, or provide certified transport advice. Real deployment would require validated traffic sensors/data, safety engineering, and authorization from traffic authorities.
