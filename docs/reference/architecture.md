# System Architecture

This page is a reference for how components connect.

![Architecture](../assets/system_architecture.png){ style="max-width: 100%; border-radius: 12px; box-shadow: 0 6px 18px rgba(0,0,0,0.35); display: block; margin: 22px auto;" }

---

## Components

- Phone (tracking + RGB-D)
- Compute node (mapping/planning)
- Controller (mission control)
- Web viewer (monitoring/replay)

---

## Data flows (high level)

- Phone → compute node: pose + RGB-D stream
- Compute node → controller: goals/waypoints
- Compute node → web server: map/telemetry
