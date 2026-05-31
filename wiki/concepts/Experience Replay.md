---
type: concept
title: "Experience Replay"
created: 2026-05-31
updated: 2026-05-31
tags:
  - concept
  - reinforcement-learning
status: defining
related:
  - "[[Deep Q-Network (DQN)]]"
---

# Experience Replay

**Experience Replay** is a pivotal mechanism in reinforcement learning algorithms like the [[Deep Q-Network (DQN)]]. It stores the agent's experiences (state, action, reward, next state) in a replay buffer. During training, the network randomly samples minibatches from this buffer rather than learning purely from sequential, chronological inputs.

In algorithmic trading, financial time series data is highly autocorrelated. Experience replay breaks this correlation, stabilizing the neural network updates and preventing the model from catastrophic forgetting or overfitting to a specific localized market regime.