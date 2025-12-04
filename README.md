# snake-ReinforcementLearning
This project implements a Reinforcement Learning agent trained to play the classic Snake game using PyTorch.
The goal was to create an autonomous agent capable of learning the game dynamics from scratch, improving over time through trial and error.

## Project Overview

The agent learns to play Snake using a Deep Q-Learning (DQN) approach, combining:

- Neural Network function approximation
- Experience Replay
- Epsilon-Greedy Exploration
- Reward Shaping to guide learning

Over time, the model evolves from making random, clumsy moves to achieving consistently high scores.

## Training Progress

Below are two GIFs showing the agent’s progression.

### Early Training
Model plays poorly:
![Image](https://github.com/user-attachments/assets/f1054f70-7b42-4c1a-98d6-500c932f5ddf)
At this stage, the agent barely understands the game. It moves randomly, often crashing quickly and failing to collect apples.

### Fully Trained
High-performing agent:
![Image](https://github.com/user-attachments/assets/a220798e-dd12-4d37-89f6-9a3d75b30f88)
Here, the agent demonstrates advanced behavior:
-Collecting points efficiently
-Avoiding walls and its own tail
