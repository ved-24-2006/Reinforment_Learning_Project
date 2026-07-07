# Battery-Aware Pathfinding using Q-Learning

This project implements a **Battery-Aware Pathfinding System** using **Q-Learning**, a reinforcement learning algorithm, in a simulated **GridWorld** environment. The agent learns to navigate from a start position to a goal while intelligently managing its limited battery, avoiding high-energy zones, and utilizing recharge stations whenever necessary.

The environment consists of:

* **Start (S)** and **Goal (G)** positions
* **High-Energy (H)** cells that consume additional battery power
* **Recharge (R)** cells that replenish the battery
* Battery constraints with penalties for inefficient energy usage or complete battery depletion

The Q-Learning agent learns an optimal navigation policy through repeated interactions with the environment, balancing path length, energy consumption, and charging opportunities to maximize cumulative rewards.

## Key Features

* Q-Learning-based reinforcement learning agent
* Battery-aware decision making
* Dynamic energy consumption and recharge mechanism
* Optimal path planning considering battery constraints
* Reward visualization across training episodes
* Animated simulation of the learned navigation policy

## Real-World Relevance

This project models several real-world challenges faced by **Electric Vehicles (EVs)**, including:

* Range anxiety due to limited battery capacity
* Intelligent utilization of charging stations
* Increased energy consumption caused by difficult terrain or road conditions
* Battery-efficient route optimization
* Adaptive navigation based on the current battery state

By combining reinforcement learning with energy-aware navigation, this project demonstrates how AI can be applied to develop smarter route planning and battery management strategies for future autonomous and electric mobility systems.
