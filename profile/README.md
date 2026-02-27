# Cornerstone Swarm Drones

**Autonomous Multi-Drone Swarm Research & Development**

We build intelligent, autonomous drone swarm systems that combine advanced control theory with modern machine learning. Our work focuses on real-world ISR (Intelligence, Surveillance & Reconnaissance) applications using distributed coordination and reinforcement learning.

---

## 🚁 Projects

### [isr-rl-dmpc](https://github.com/Cornerstone-swarm-drones/isr-rl-dmpc)

[![Python 3.8+](https://img.shields.io/badge/python-3.8%2B-blue.svg)](https://www.python.org/downloads/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://github.com/Cornerstone-swarm-drones/isr-rl-dmpc/blob/main/LICENSE)

**Intelligence, Surveillance & Reconnaissance Grid-Based Autonomous Swarm with RL-DMPC**

An autonomous ISR platform that combines **Reinforcement Learning (RL)** with **Distributed Model Predictive Control (DMPC)** for multi-drone swarm coordination. The system performs grid-based coverage planning, real-time target tracking, and threat assessment using a modular 9-component architecture with a Gymnasium-compatible RL environment.

**Highlights:**
- Hybrid RL + DMPC control — neural networks learn optimal DMPC cost function parameters while CVXPY ensures constraint satisfaction
- 9 integrated modules — mission planning, formation control, sensor fusion, classification, threat assessment, task allocation, DMPC, attitude control, and learning
- Gymnasium-compatible `ISRGridEnv` with Dict observation spaces, multi-objective rewards, and vectorized training support
- 6-DOF physics simulation with wind, battery depletion, and collision detection

**Mission Scenarios:**

| Scenario | Area | Drones | Targets | Formation |
|---|---|---|---|---|
| Area Surveillance | 500×500 m | 4 | 0 | Grid |
| Threat Response | 300×300 m | 6 | 3 | Wedge |
| Search & Track | 800×800 m | 5 | 4 | Line |

**Tech Stack:** Python · PyTorch · Gymnasium · CVXPY · NumPy · SciPy

---

## 🛠 Technology Focus

| Area | Technologies |
|---|---|
| Reinforcement Learning | Gymnasium, PyTorch, Actor-Critic |
| Control Systems | Distributed MPC, CVXPY, 6-DOF Dynamics |
| Swarm Coordination | Formation Control, Task Allocation, Hungarian Algorithm |
| Sensor Systems | Sensor Fusion, Target Tracking, Threat Assessment |
| Scientific Computing | NumPy, SciPy, scikit-learn, Matplotlib |

---

## 👥 Team

| Name | Email |
|---|---|
| Jivesh Kesar | jrb252026@iitd.ac.in |
| Harsh | jrb252049@iitd.ac.in |
| Rohit Shankar Sinha | jrb252051@iitd.ac.in |
