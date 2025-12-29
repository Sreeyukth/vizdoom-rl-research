VizDoom Reinforcement Learning Research

Overview
This repository contains research work on reinforcement learning in game environments using VizDoom. The objective is to study and compare different learning architectures for controlling an agent in a simplified first-person shooter scenario.

Environment

Simulator: VizDoom
Scenario: basic.cfg
Execution: Headless (rno rendering)
Platform: Linux-based (cloud-compatible)
The environment uses a small discrete action space to enable controlled and fair comparisons across models.

Current Progress
VizDoom environment successfully set up and validated
Random policy baseline implemented
Reward dynamics and episode behavior verified
The random agent establishes a lower-bound performance reference before introducing learning-based agents.

Planned Experiments

PPO baseline
PPO with LSTM
PPO with Transformer
Decision Transformer

All models will be evaluated using the same environment and reward structure.

Contributors

Sreeyukth Shankar
Akash Dileep