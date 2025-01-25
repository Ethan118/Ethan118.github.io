---
title: "UW Robosoccer"
date: "2024-09-01"
description: "Building small, autonomous humanoid robots to play soccer"
tags: ["In progress"]
layout: ../../layouts/ProjectLayout.astro
---

# UW Robosoccer

## Overview
Beginning in Sept 2024, I started a small team alongside 7 other students to build small humanoid robots to play 4v4 soccer. The goal of this project is to develop a team of 4 autonomous humanoid robots to play soccer in the 2026 international Humanoid Robocup competition (child size league) in South Korea.

- Robots are roughly 50cm tall, equipped with 2 cameras, 18 servos, and a Raspberry Pi 5
- Attempting to revolutionize the competition by using a deep reinforcement learning approach to control dynamic movements like walking, kicking, and dribbling
- Using MujoCo for simulation and Brax for parallel training
- Developing classical control algorithms for balance using Task Space Inverse Dynamics Control (TSID)

![Robot Render](/images/uwrobosoccer_robot.png)

## Progress
### Jan 2025
This month's goal is to read up on control theory and implement a simple balance controller for the robot.

### Dec 2024
This month's goal is to train some rudimentary skills like getting up, walking, and balance to get familiar with MuJoCo and Brax.

Set up MuJoco simulation environment by porting over an example humanoid environment from Brax
<video width="100%" height="auto" controls>
    <source src="/videos/mujoco-working.mp4" type="video/mp4">
    Your browser does not support the video tag.
</video>

Started training a simple get up policy using PPO and MoCap data (harder than originally thought)
<video width="100%" height="auto" controls>
    <source src="/videos/training.mp4" type="video/mp4">
    Your browser does not support the video tag.
</video>

Trained a running policy for fun in Colab using Brax
<video width="100%" height="auto" controls>
    <source src="/videos/running.mp4" type="video/mp4">
    Your browser does not support the video tag.
</video>

### Nov 2024
This month's goal is to wrap up research on the current state of the art in humanoid robot control and reinforcement learning.

Read a total of 10 papers and took notes to share with the team during weekly sync:
1. [Emergent Tool Use From Multi-Agent Autocurricula](https://arxiv.org/abs/1909.07528)
2. [Human-timescale adaptation in an open-ended task space](https://arxiv.org/abs/2301.07608)
3. [Between mdps and semi-mdps: A framework for temporal abstraction in reinforcement learning](https://doi.org/10.1016/S0004-3702(99)00052-1)
4. [SkillS: Adaptive Skill Sequencing for Efficient Temporally-Extended Exploration](https://arxiv.org/abs/2211.13743)
5. [Emergent Coordination Through Competition](https://arxiv.org/abs/1902.07151)
6. [Responsive Safety in Reinforcement Learning by PID Lagrangian Methods](https://arxiv.org/abs/2007.03964)
7. [Kickstarting Deep Reinforcement Learning](https://arxiv.org/abs/1803.03835)
8. [Information asymmetry in KL-regularized RL](https://arxiv.org/abs/1905.01240)
9. [Distral: Robust Multitask Reinforcement Learning](https://arxiv.org/abs/1707.04175)
10. [Overlapping layered learning notes](https://doi.org/10.1016/j.artint.2017.09.001)

### Oct 2024
This month's goal is to familiarize myself with reinformcement learning and finalize logistics for the team.

### Oct 2024
This month's goal is to familiarize myself with reinformcement learning and finalize logistics for the team.

Finished mini series on reinforcement learning
[![Reinforcement Learning by the Book](https://img.youtube.com/vi/NFo9v_yKQXA/0.jpg)](https://www.youtube.com/playlist?list=PLzvYlJMoZ02Dxtwe-MmH4nOB5jYlMGBjr)

Finished deepmind x UCL course on reinforcement learning
[![Deepmind x UCL Reinforcement Learning Course](https://img.youtube.com/vi/2pWv7GOvuf0/0.jpg)](https://www.youtube.com/playlist?list=PLqYmG7hTraZDM-OYHWgPebj2MfCFzFObQ)

### Sept 2024
We're officially a design team!! Design team number 42 to be exact. We're still in the process of recruiting members and setting up logistics.