# Treasure Hunt Game: Deep Q-Learning Pathfinding

This project is all about training an AI pirate to find a treasure in an 8x8 maze using Deep Q-learning. The goal is to teach the pirate to figure out the best path through the maze, learning from experience and making smart decisions based on rewards and penalties.

## Overview

The game simulates a pathfinding problem where the pirate agent starts at a random position in the maze and needs to get to the treasure at the bottom-right corner. The maze has free cells and obstacles, and the agent learns to avoid obstacles while taking the most efficient route possible. The Deep Q-learning approach uses a neural network to estimate Q-values for different actions, helping the pirate decide which way to go.

The training process involves balancing exploration (trying out new paths) and exploitation (using what it’s learned so far), and the agent gets better at finding the treasure over time through trial and error.

## Features

- **Deep Q-Learning**: The algorithm uses a neural network to predict Q-values, helping the agent learn the best actions to take.
- **Experience Replay**: The agent learns from past experiences, which are stored and replayed to improve learning.
- **Exploration vs. Exploitation**: The training balances random exploration with choosing the best-known action to optimize the agent’s learning.
- **Maze Visualization**: See the maze with the pirate’s path, obstacles, and the treasure during training and testing.
