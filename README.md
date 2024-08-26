# Maze Pathfinding Project

## Overview

This project is designed to implement and evaluate two different algorithms for finding the shortest path in a maze. The two algorithms compared are:

1. A classical search algorithm (BFS or DFS).
2. A reinforcement learning algorithm (Q-learning).

The primary objective is to navigate from a start point to a goal point while finding the shortest path.

## Algorithms

### Classical Search Algorithm

- **Algorithm Choice:** 
  - **Breadth-First Search (BFS):** Finds the shortest path in an unweighted maze by exploring all possible paths level by level.
  - **Depth-First Search (DFS):** Explores as far as possible along each branch before backtracking, which might not guarantee the shortest path.

- **Objective:** 
  - To find the shortest path using either a uniform search (BFS) or a non-uniform search strategy (DFS).

### Reinforcement Learning Algorithm

- **Algorithm Choice:** 
  - **Q-learning:** A model-free reinforcement learning algorithm that learns the optimal path by exploring the maze and updating Q-values based on rewards.

- **Objective:** 
  - To learn the optimal path through continuous exploration and exploitation of the maze environment.

## Test Cases

The performance of the algorithms is tested on three different maze configurations. The following metrics are used for evaluation:

- **Total Execution Time:** The time taken by the algorithm to find the path.
- **Steps Taken:** The number of steps required to reach the goal.
- **Nodes Expanded:** The number of nodes expanded during the search process.

## Visualizations

- **Maze Representation:** Visual plot of the empty maze.
- **Path Taken:** Visual plot showing the path taken by each algorithm to reach the goal.
- **Comparison Plots:** Graphical representation of the comparison metrics for the algorithms.


