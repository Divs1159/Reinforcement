# Reinforcement Learning

This repository is created solely for learning purposes and is intended for students taking the "Introduction to AI" course in the 2023 academic year. Here, you will find resources, code, and materials related to Reinforcement learning lab.

## Contents

- [Overview](#Overview)
- [Materials](#Materials)

## Overview
![RL Block diagram](https://github.com/Divs1159/Reinforcement/blob/main/figures/G1.png)

One possible definition of reinforcement learning (RL) is a computational approach to learning how to maximize the total sum of rewards when interacting with an environment. While a definition is useful, this tutorial aims to illustrate what reinforcement learning is through images, code, and video examples and along the way introduce reinforcement learning terms like agents and environments.

In reinforcement learning, one or more agents interact within an environment which may be either a simulation like CartPole in the first tutorial or a connection to real-world sensors and actuators. At each step, the agent receives an observation (i.e., the state of the environment), takes an action, and usually receives a reward (the frequency at which an agent receives a reward depends on a given task or problem). Agents learn from repeated trials, and a sequence of those is called an episode — the sequence of actions from an initial observation up to either a “success” or “failure” causing the environment to reach its “done” state. The learning portion of an RL framework trains a policy about which actions (i.e., sequential decisions) cause agents to maximize their long-term, cumulative rewards.

## Materials
- Simple Cartpole environment
    - Using PPO
    - Using DQN
- Frozen lake environment
