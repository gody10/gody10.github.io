---
title: "Deep Reinforcement Learning for Optimization of a Residential Energy Management"
excerpt: "This project was published in IEEE International Conference on Communications, Control, and Computing Technologies for Smart Grids. A Smart Home environment is created and a Deep Reinforcement Learning agent is developed with the goal of acting as a Residential Energy Manager which will adapt to the user's preferences and minimize costs [(github repository)](https://github.com/SpirosChadoulos/EMS-env): **Deep Reinforcement Learning** <br/><img src='/images/smart_home.jpg' width='700'>"
collection: portfolio
---

## EMS-env: A Reinforcement Learning framework for residential energy efficiency recommendations

### Description

This project serves as a comprehensive guide and resource hub for understanding, experimenting with, and implementing RL models in the context of household energy optimization.

_EMS-env_ is a custom Gymnasium environment for residential energy efficiency recommendations.

_EMS-env paper: S. Chadoulos, O. Diamantopoulos, I. Koutsopoulos, G.C. Polyzos, and N. Ipiotis. "EMS-env: A Reinforcement Learning Framework for Residential Energy Efficiency Recommendations" (Presented at the 2024 IEEE International Conference on Communications, Control, and Computing Technologies for Smart Grids, Oslo Nowray)._

### Implementation Details

This framework was built using Gymnasium to create the environment and Ray to execute and deploy different Deep Reinforcement Learning (DRL)algorithms. More specifically, the following algorithms were applied:
- e-greedy
- Actor 2 Critic
- A3C
- Proximal Policy Optimization

The environment supports an infinite number of different user's, who each have their own preferences and unique personalities. The DRL agent is tasked to, on the one hand, understand the user's behavioral patterns, on the other hand, schedule appliances for time frames that the electricity price is lower (example: night hours)

### Technologies Used

- **Deep Reinforcement Learning** – Leveraging advanced Deep-RL techniques for optimal decision-making.
- **Problem Modeling** – Structuring complex problems into solvable frameworks.
- **Cutting-Edge Libraries** – Utilizing Gymnasium and Ray for scalable and efficient RL environments.