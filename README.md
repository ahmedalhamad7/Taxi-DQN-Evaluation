# Taxi-DQN-Evaluation
A comparative evaluation of Deep Q-Learning (DQN) and Double DQN on the Taxi-v3 environment using Keras-RL2, highlighting the impact of overestimation bias and architectural improvements on agent performance.

## Overview

This project investigates how algorithmic enhancements (Double Q-Learning) and architectural improvements (deeper neural networks, slower epsilon decay, stable target updates) influence learning outcomes in a sparse-reward environment. The Taxi-v3 environment provides a discrete, deterministic gridworld setting that is ideal for studying value estimation behavior in reinforcement learning.

## Features

- Implementation of both basic and improved DQN and Double DQN agents
- One-hot state encoding via a custom Keras-RL processor
- Training and evaluation with detailed performance tracking
- Visualization of episode rewards across all model variants
- Summary of test-time rewards and success rates

## Usage

1. Clone the repository.
2. Install the required dependencies.
3. Run the notebook `DQN-vs-DDQN.ipynb` to train and evaluate the agents.
4. Compare reward trends and performance metrics from the final plots and tables.
