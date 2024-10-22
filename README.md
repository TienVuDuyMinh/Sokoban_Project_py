# Training Sokoban Using Reinforcement Learning Algorithms

This project applies several reinforcement learning (RL) algorithms, including Q-learning, SARSA, and Monte Carlo, to train an agent to solve Sokoban puzzles. The goal is to optimize the agent's performance in pushing boxes to designated target positions across maps of varying complexity. Each algorithm is tested on different environments, and the results are compared to evaluate the strengths and weaknesses of each approach.

## Table of Contents
- [Project Description](#project-description)
- [Algorithms Implemented](#algorithms-implemented)
- [Results](#results)
- [How to Run the Code](#how-to-run-the-code)
- [Report, Slide and Presentation](#Report,-Slide-and-Presentation)
- [Future Work](#future-work)
- [References](#references)

## Project Description

Sokoban is a classic puzzle game where the player (agent) must push boxes (objects) to specific target locations. The challenge of Sokoban lies in the constraints, such as limited movement options and the need to minimize the number of steps to solve each map. This project implements three RL algorithms to teach the agent how to solve Sokoban efficiently.

## Algorithms Implemented
- **Q-learning**: An off-policy RL algorithm that learns the optimal action-value function to maximize the expected reward.
- **SARSA**: An on-policy algorithm where the agent updates the value of the action it actually took, focusing more on the agent's current policy.
- **Monte Carlo**: A method based on averaging rewards from multiple episodes to evaluate the expected return for state-action pairs.

## Results
The algorithms were tested across multiple Sokoban maps, and the results show that:
- **SARSA** outperformed Q-learning and Monte Carlo in more complex environments due to its on-policy nature.
- **Q-learning** performed well on simpler maps but struggled with increased complexity.
- **Monte Carlo** showed slower convergence due to its dependence on complete episodes.
- 
## Report, Slide and Presentation
- [Report](https://www.overleaf.com/project/67138cf223076647ac355df0)
- [Slide](https://docs.google.com/presentation/d/1d8rmVS76A6P2RxxKpUcQwt28pc14M2Ry/edit#slide=id.p1)
- [Presentation](https://youtu.be/Usfki-qBP5Y)

## How to Run the Code

To run the code, follow these steps:
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/sokoban-rl.git
