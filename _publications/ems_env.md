---
title: "EMS-env: A Reinforcement Learning Framework for Residential Energy Efficiency Recommendations"
collection: publications
category: conferences
permalink: /publication/ems_env
excerpt: 'Index Terms: **Deep Reinforcement Learning, Energy Optimization**'
date: 2024-01-10
venue: 'IEEE International Conference on Communications, Control, and Computing Technologies for Smart Grids (SmartGridComm)'
paperurl: 'http://gody10.github.io/files/ems_env.pdf'
citation: '2024, S. Chadoulos, O. Diamantopoulos, I. Koutsopoulos, G. Polyzos and N. Ipiotis, "EMS-env: A Reinforcement Learning framework for residential energy efficiency recommendations", IEEE SmartGridComm 2024, Accepted'
---
Personalized device-level energy consumption recommendations towards energy efficiency can have a notable
impact both on electricity bills and on the overall energy supplydemand balance. End-user behavior regarding device activation
is usually unknown a priori, thus giving rise to a highly dynamic
environment. Hence, Reinforcement Learning (RL) can be utilized for device scheduling and consumption recommendations
since it constitutes an Artificial Intelligence (AI) framework that
learns a control policy in a dynamic environment through trying
actions and observing incurred rewards. However, existing works
on energy consumption recommendations do not explicitly take
into account human feedback and preferences regarding the
issued recommendations, and they train a single RL agent per
device, hence missing the human behavior interdependencies in
using different devices. In addition, a flexible open-source RL
environment model that integrates user behavior in a Markov
Decision Process (MDP) model is missing. In this paper, we
propose an MDP-driven RL framework for energy efficiency
recommendations that jointly learns the user’s behavior for
multiple devices. The proposed model is wrapped as an opensource customizable Gymnasium environment, named EMS-env,
for multi-device energy efficiency recommendations. EMS-env can
simulate different types of consumer behavior profiles based on
the MDP model and supports different device types as well as user
feedback. Validation experiments demonstrate the framework’s
merits and hyperparameters for diverse use cases in terms of
user simulation models and RL training policies, resulting in
decreased energy costs while maintaining end-user satisfaction