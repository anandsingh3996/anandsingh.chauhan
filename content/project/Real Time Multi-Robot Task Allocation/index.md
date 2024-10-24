---
title: Real-Time Multi Robot Task Allocation in Dynamic Warehouse Environment 
date: "2024-10-18T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2024-10-18T00:00:00Z"

tags:
  - Reinforcement Learning
  - Warehouse Management
  - Robot Navigation
---
<div style="text-align: justify;">
The project "MRTAgent" is a self-play-driven bi-level reinforcement learning framework, designed to address the growing complexity of task allocation and robot selection in dynamic warehouse environments. As warehouse automation becomes increasingly prevalent, optimizing the assignment of tasks to robots while accounting for practical constraints such as energy consumption, battery life, and avoiding collisions becomes crucial. MRTAgent was developed to minimize inefficiencies such as unnecessary travel distances and delays in task completion.
The framework utilizes a dual-agent approach, where one agent focuses on task selection and the other on robot selection. By separating these tasks and having one agent in evaluation mode while the other trains, MRTAgent ensures that real-time decisions can be made efficiently. This structure allows for continuous learning and adaptation in environments with constantly changing conditions. To support safe navigation, the system integrates a modified Linear Quadratic Regulator (LQR) for collision-free robot movement, accommodating physical constraints present in real-world scenarios. 
MRTAgent was rigorously tested across multiple datasets with varying environmental conditions, demonstrating substantial improvements in reducing operational costs and delays compared to traditional methods. This innovative framework enables more intelligent task management, helping warehouses run more smoothly while ensuring safety and efficiency.</div>

<!--more-->
