---
type: source
source_type: paper
author: ["Volodymyr Mnih", "Koray Kavukcuoglu", "David Silver", "et al."]
date_published: 2015-02-26
url: https://www.nature.com/articles/nature14236
confidence: high
key_claims:
  - An artificial agent using a deep Q-network can learn successful policies directly from high-dimensional inputs.
  - The combination of a neural network function approximator, experience replay, and a target network stabilizes Q-learning, preventing divergence.
---

# DQN Nature Paper

"Human-level control through deep reinforcement learning" (2015) by [[Volodymyr Mnih]] and the DeepMind team is the landmark paper combining deep learning with reinforcement learning. By introducing the [[Deep Q-Network (DQN)]] architecture—utilizing [[Experience Replay]] to break data correlation and target networks to stabilize unhinged updates—the authors solved the historic instability of non-linear function approximators inside RL frameworks. While originally tested on Atari paradigms, this framework catalyzed the use of DQNs in sequence decision maps like [[Reinforcement Learning in Finance]].