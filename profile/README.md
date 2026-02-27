# Cornerstone Swarm Drones

Autonomous multi-drone swarm systems combining Reinforcement Learning with Distributed Model Predictive Control for Intelligence, Surveillance & Reconnaissance (ISR) missions.

## Our Project

### [ISR-RL-DMPC](https://github.com/Cornerstone-swarm-drones/isr-rl-dmpc)

**Autonomous Multi-Drone Swarm System with Reinforcement Learning-Based Distributed Model Predictive Control**

A platform for grid-based ISR operations that fuses deep RL with CVXPY-backed DMPC to coordinate drone swarms in real time.

**Key Features**

- **Hybrid RL + DMPC Control** — Neural networks learn optimal DMPC cost function parameters while CVXPY enforces hard constraints
- **9 Integrated Modules** — Mission planning, formation control, sensor fusion, classification, threat assessment, task allocation, DMPC, attitude control, and online learning
- **Gymnasium-Compatible Environment** — `ISRGridEnv` with Dict observation spaces, multi-objective rewards, and vectorized training support
- **6-DOF Physics Simulation** — Rigid-body dynamics with wind disturbances, battery depletion, and collision detection
- **Configurable Mission Scenarios** — Area surveillance, threat response, and search-and-track with YAML-based configuration

**Mission Scenarios**

| Scenario | Area | Drones | Targets | Formation |
|---|---|---|---|---|
| Area Surveillance | 500 × 500 m | 4 | 0 | Grid |
| Threat Response | 300 × 300 m | 6 | 3 | Wedge |
| Search & Track | 800 × 800 m | 5 | 4 | Line |

**Technology Stack:** Python · PyTorch · Gymnasium · CVXPY · NumPy / SciPy

## Team

| Name | Email |
|---|---|
| Jivesh Kesar | jrb252026@iitd.ac.in |
| Harsh Mulodhia | jrb252049@iitd.ac.in |
| Rohit Shankar Sinha | jrb252051@iitd.ac.in |
