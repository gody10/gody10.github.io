---
title: "Deep Reinforcement Learning for Optimization of a Residential Energy Management"
excerpt: "This project was published in the Simulation Modeling and Practice journal. We modeled a disaster scenario where UAVs have to optimize their path planning in order to collect as much data as they can to serve the citizents of the city [(github repository)](https://github.com/gody10/SIMPAT_BRAVE_2025): Multi-Agent Deep Reinforcement Learning, Game Theory <br/><img src='/images/SIMPAT_framework.jpg' width='700'>"
collection: portfolio
---

## EMS-env: A Reinforcement Learning framework for residential energy efficiency recommendations

### Description

This projecs explores the ability of UAVs to assist citizents in case of emergencies, like earthquakes. We model the data offloading of users using Submodular Games and train UAVs with Multi-Agent Deep Reinforcement Learning algorithms and compare the results.

_BRAVE paper: Odyssefs Diamantopoulos Pantaleon, Aisha B. Rahman, and E. E. Tsiropoulou, "BRAVE: Benefit-Aware Data Offloading in UAV Edge Computing Using Multi-Agent Reinforcement Learning", Simulation Modeling and Practice, Accepted ._

### Implementation Details

This framework was built using Gymnasium to create the environments (Single-Agent and Multi-Agent environments) and Jax to accelerate all the calculations needed for both the Reinforcement Learning algorithms and the Submodular games. The algorithms implemented in this project were:
- Q-Learning
- SARSA
- Multi-Agent Q-learning with shared table
- Stochastic Learning Automata
- Best Response Dynamics
- Greedy
- Dijkstra

### Technologies Used

- **Multi-Agent Deep Reinforcement Learning** – Leveraging advanced RL techniques for optimal decision-making.
- **Problem Modeling** – Structuring complex problems into solvable frameworks.
- **Cutting-Edge Libraries** – Utilizing Gymnasium and JAX for scalable and efficient RL environments.