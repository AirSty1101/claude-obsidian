---
type: concept
title: "Discrete Action Space (Trading)"
created: 2026-05-31
updated: 2026-05-31
tags:
  - concept
  - reinforcement-learning
status: defining
related:
  - "[[Deep Q-Network (DQN)]]"
---

# Discrete Action Space (Trading)

In reinforcement learning, a **Discrete Action Space** refers to an environment where the agent can only choose from a finite set of distinct actions. For trading algorithms utilizing a [[Deep Q-Network (DQN)]], the discrete action space is typically formulated as `{Buy, Hold, Sell}` or `{Long, Neutral, Short}`.

This simplifies the modeling process compared to continuous action spaces (which require determining exact position sizing simultaneously) but inherently limits the algorithm's ability to express conviction magnitude unless layered with external sizing logic like the [[Kelly Criterion]].