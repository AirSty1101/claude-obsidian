---
type: concept
title: "Deep Q-Network (DQN)"
created: 2026-05-31
updated: 2026-05-31
tags:
  - concept
  - machine-learning
  - reinforcement-learning
status: defining
related:
  - "[[Reinforcement Learning in Finance]]"
  - "[[Experience Replay]]"
  - "[[Markov Decision Process (MDP)]]"
---

# Deep Q-Network (DQN)

A **Deep Q-Network (DQN)** is a reinforcement learning algorithm that combines Q-Learning with deep neural networks. Introduced by DeepMind, DQN solves the curse of dimensionality present in standard Q-Learning by using a non-linear function approximator (a neural network) to estimate the optimal action-value function based on the environment's state.

In quantitative finance, DQNs are utilized to optimize a [[Discrete Action Space (Trading)]]—such as Buy, Hold, or Sell—by maximizing cumulative expected rewards (e.g., risk-adjusted returns like the Sharpe Ratio) over a sequence of states defined by technical indicators and order book data.