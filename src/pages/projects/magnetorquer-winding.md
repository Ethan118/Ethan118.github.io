---
title: "Automating Magnetorquer Manufacturing"
date: "2023-03"
description: "Building an automated winding mechanism for CubeSat magnetorquers"
tags: ["robotics", "space", "arduino"]
layout: ../../layouts/ProjectLayout.astro
---

# Automating Magnetorquer Manufacturing

## Overview
For the University of Waterloo's Orbital design team, I developed an automated winding mechanism to manufacture magnetorquers - electromagnetic actuators used for satellite attitude control. These devices generate torque by interacting with Earth's magnetic field, allowing precise orientation control of CubeSats in orbit.

## The Challenge
Traditionally, manufacturing magnetorquers involves manually winding hundreds of turns of thin copper wire around a core - a process that could take days and often resulted in inconsistent results. As part of the Attitude Determination and Control Systems (ADCS) sub-team, I was tasked with streamlining this process.

## Solution
I designed and built an automated winding mechanism that reduced manufacturing time from days to just a couple of hours. The system consists of:

- A Solidworks-designed mechanical frame and winding assembly
- An Arduino-controlled dual BLDC motor system with PID control
- Precision wire guidance mechanisms
- Real-time turn counting and monitoring

![Magnetorquer Winding Machine](/images/winding_mechanism.png)

## Results
The automated system achieved several key improvements:
- Reduced manufacturing time by approximately 90%
- Improved consistency in wire spacing and tension
- Enabled precise turn counting and quality control
- Reduced human error in the manufacturing process

## Technical Details
The winding mechanism uses an Arduino to control two BLDC motors, implementing PID control to maintain precise and synchronized rotation speeds. The system includes:

- Dual BLDC motors with closed-loop speed control
- PID controller ensuring synchronized motor speeds
- Automated wire guide to ensure even distribution
- Turn counting system for quality control
- Emergency stop and manual override capabilities

This project showcases how automation can significantly improve manufacturing processes in spacecraft component production, making satellite development more efficient and reliable.
