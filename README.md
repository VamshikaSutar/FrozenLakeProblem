# **Frozen Lake Solver using Q-Learning**

This project explores Reinforcement Learning by developing an intelligent agent to solve the **Frozen Lake** environment from **OpenAI Gym**.  
The agent learns optimal navigation strategies on a slippery grid world using **Q-Learning** and an **epsilon-greedy exploration policy**.

---

## ❄️ Project Overview

The Frozen Lake environment consists of a grid with frozen tiles, holes, and a goal.  
Due to slippery transitions, actions are stochastic, making it ideal for studying model-free RL techniques.

This project implements a **tabular Q-learning agent** that learns safe and efficient paths to the goal through repeated interaction with the environment.

---

## 🧠 Key Features

### ✔ Q-Learning Implementation  
- Full implementation of the Q-learning update rule  
  \[
  Q(s, a) \leftarrow Q(s, a) + \alpha \left( r + \gamma \max_{a'} Q(s', a') - Q(s, a) \right)
  \]
- Supports configurable learning rate, discount factor, and exploration rate.

### ✔ Epsilon-Greedy Exploration  
- Balances exploration and exploitation during training.  
- Epsilon decays gradually to shift focus toward optimal policies.

### ✔ High Training Performance  
- Agent trained for **10,000+ episodes**.  
- Achieved a **95% success rate** in reaching the goal.

---



