---
title: "Reinforcement Learning Battlesnake"
date: "2023-08"
description: "Training an autonomous agent to play Battlesnake using PPO"
tags: ["machine learning", "python", "reinforcement learning"]
layout: ../../layouts/ProjectLayout.astro
---

# Reinforcement Learning Battlesnake

## Overview
During my internship at RBC, I collaborated with another student to develop an autonomous agent for the RBC Battlesnake competition. Our approach stood out by being the only entry to utilize deep reinforcement learning, specifically implementing OpenAI's PPO (Proximal Policy Optimization) algorithm.

## The Project
[Battlesnake](https://play.battlesnake.com/) is a competitive programming challenge where developers create autonomous agents to play a multiplayer version of the classic game Snake. Players must navigate to collect food while avoiding collisions with walls, other snakes, and themselves.

![Training Progress](/images/lone-learner.png)

## Technical Implementation

### Reinforcement Learning Approach
- Implemented PPO (Proximal Policy Optimization) algorithm for training
- Designed a custom reward function incorporating survival time, food collection, and spatial efficiency

### Hybrid Control System
- Developed a supervisor system using Minimax algorithm to:
  - Validate moves proposed by the RL model
  - Identify immediate winning conditions
  - Prevent obvious fatal mistakes
- Implemented state-space pruning to optimize decision-making speed

## Results
- Only RL-based agent in the RBC competition
- Achieved 8th place globally on international leaderboards within one month of deployment
- Demonstrated the viability of reinforcement learning in competitive programming

## Code
The project is open source and available on GitHub: [bs-lindor](https://github.com/Nathan13888/bs-lindor)

## Key Learnings
- Practical implementation of PPO in a competitive environment
- Importance of hybrid approaches combining learning-based and traditional algorithms
- Techniques for optimizing real-time decision-making in game environments
