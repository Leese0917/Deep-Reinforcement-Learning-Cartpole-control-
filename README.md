# CS 4644 Fall 2023 - Comparing Deep Reinforcement Learning Techniques on Cartpole Control

<img src="https://www.gymlibrary.dev/_images/cart_pole.gif" width="40" height="40" class="center"/>

## Summary
This project explores various deep reinforcement learning methods applied to the classic control problem of CartPole. The study compares different variants of Deep Q-Learning (DQN), including DQN, Double DQN, Dueling DQN, and CNN-based DQN, as well as Proximal Policy Optimization (PPO).

Key components of the project include:

### Method
We utilizes DQN methods, which optimize the expected future rewards for a state-action pair, and PPO, which optimizes policy using an Actor-Critic architecture. The study involves variations of DQN, such as Double DQN, Dueling DQN, and CNN-based DQN.

### Dateset 
The dataset is generated from the experiences of the agent interacting with the CartPole environment. The state space includes parameters like cart position, cart velocity, pole angle, and pole angular velocity.

### Implementation
The project is developed using OpenAI Gym, Keras, and TensorFlow libraries in Python. The training is performed on Google Colab, and testing is done offline.

### Experimental Comparison
Evaluation metrics such as loss, accuracy, reward, score, and Q-values are used to compare the performance of different algorithms. Testing results include videos of the CartPole environment, and average testing scores are calculated across multiple episodes.

### Algorithims
DQN is extended with variations like Double DQN and Dueling DQN. CNN-DQN is explored, where the state is represented as an input image. PPO is introduced as an alternative RL method.

### Results
After tuning, PPO and DDQN achieve perfect scores, outperforming other methods. The project presents visual results through graphs, showing loss, score, value, reward, accuracy, and Q-values.

### Conclusion
We successfully develops a coding pipeline for studying fundamental RL algorithms on the CartPole problem. PPO and DDQN demonstrate superior performance, while CNN-DQN methods require further exploration. The report suggests possible improvements for future work, including addressing issues with CNN-DQN and refining termination criteria for training.

