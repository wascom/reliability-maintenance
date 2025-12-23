# reliability-maintenance
MATLAB implementation of reinforcement learning (R-learning/Q-learning) and Trend Renewal Process (TRP) algorithms for optimizing maintenance intervals.

# Reliability & Maintenance Optimization Scripts

## Overview
This repository contains MATLAB scripts and documentation for analyzing system reliability and optimizing maintenance schedules. It focuses on applying **Reinforcement Learning (RL)**—specifically R-learning and Q-learning—and the **Trend Renewal Process (TRP)** to determining optimal component replacement times.

This work supports research in Systems and Engineering Management, specifically addressing reliability in stochastic degradation environments.

## Features
* **TRP Analysis:** Modeling failure intensity using Gumbel and Weibull-based Trend Renewal Processes.
* **RL Algorithms:** Implementation of Average Reward (R-learning) for infinite-horizon maintenance decision-making.
* **Simulation:** Discrete event simulation for testing maintenance policies against random failure data.

## Prerequisites
* MATLAB R2023b or newer
* Statistics and Machine Learning Toolbox
* Optimization Toolbox

## Usage
1.  Run `src/main_simulation.m` to execute the baseline RL training loop.
2.  Adjust parameters in `src/config_params.m` to change failure distributions (e.g., Weibull shape/scale).
3.  View results in the `results/` folder (plots generated automatically).

## Citation
If you use these scripts, please cite the associated dataset/code via the DOI below:
[Insert Zenodo Badge Here once generated]

## License
MIT License
