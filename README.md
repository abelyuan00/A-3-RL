This repository contains implementations of various reinforcement learning algorithms applied to a grid world environment. The grid world is a classic problem in reinforcement learning where an agent navigates a grid to reach a goal state, receiving rewards or penalties based on its actions. The following algorithms are implemented:

Q-learning: An off-policy, model-free algorithm that learns the value of the optimal policy by updating Q-values based on observed rewards and maximum future rewards.
SARSA: An on-policy algorithm that updates Q-values based on the action taken by the current policy, leading to more conservative updates compared to Q-learning.
Gradient Monte Carlo: A value-based algorithm that estimates the value function by updating weights based on the return of each state, using the entire episode for updates.
Semi-gradient TD(0): A value-based algorithm that updates the value function incrementally using the temporal difference error, balancing bias and variance in value estimates.
The environment is a 6x6 grid where the agent starts at the top-left corner and aims to reach the bottom-right corner, incurring a reward of -1 for each step and 0 upon reaching the goal.

Key Features
Epsilon-greedy Policy: Used for action selection to balance exploration and exploitation.
Parameter Settings: Learning rate, discount factor, and exploration rate can be adjusted.
Visualization: Value functions and policies are visualized to understand the learned strategies.
This code serves as a practical guide for understanding and implementing fundamental reinforcement learning algorithms in a simplified grid world environment.
