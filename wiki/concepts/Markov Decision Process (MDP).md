---
type: concept
title: "Markov Decision Process (MDP)"
created: 2026-05-31
updated: 2026-05-31
tags:
  - concept
  - reinforcement-learning
  - mathematics
status: defining
related:
  - "[[Reinforcement Learning in Finance]]"
---

# Markov Decision Process (MDP)

A **Markov Decision Process (MDP)** provides the mathematical framework for modeling decision-making in situations where outcomes are partly random and partly under the control of a decision-maker. It is defined by a set of states, actions, transition probabilities, and rewards.

In [[Reinforcement Learning in Finance]], formulating the market as an MDP is the foundational step. The agent observes the state (price history, indicators), takes an action (buy/sell), receives a reward (profit/loss), and the environment transitions to the next timeframe. The core assumption (the Markov Property) is that the current state encapsulates all necessary historical information to predict future transitions.