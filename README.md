# -Deep-Q-Learning-for-Atari-Space-Invaders-Reinforcement-Learning-Project-
In this project, I implemented a reinforcement learning agent capable of playing the Atari game Space Invaders using Deep Q-Learning (DQN). The goal was to design an agent that could learn effective strategies purely from pixel inputs and rewards, without any predefined rules.

Key aspects of the project included:

Environment Setup: Leveraged OpenAI Gym’s Atari environments to preprocess raw frames (grayscale conversion, resizing, frame-stacking) for efficient learning.

Model Architecture: Built a convolutional neural network (CNN) to approximate the Q-function, mapping pixel observations to action values.

DQN Variants: Implemented both vanilla DQN and Double DQN to address overestimation bias, with improvements in stability and performance.

Training & Optimization: Applied experience replay buffers, target networks, and epsilon-greedy exploration to balance exploration and exploitation.

Evaluation: Compared results of vanilla vs. double DQN models by analyzing reward progression and visualizing gameplay through rendered episodes.

Through iterative training and tuning, the agent was able to learn effective survival and shooting strategies, demonstrating how reinforcement learning can achieve near-human level performance in complex environments.
