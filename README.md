# 👾 PAC-MAN: Reinforcement Learning Agent

This project implements a **Reinforcement Learning (RL)** agent to play the classic **Pac-Man** game using the **Q-Learning algorithm**. The project is part of the coursework for AI studies and showcases how an agent can learn optimal strategies by interacting with the game environment.

---

## 🎯 Project Objective

The aim is to develop an intelligent Pac-Man agent that learns to:

- Navigate the maze
- Avoid ghosts
- Eat pellets and fruits
- Maximize its total reward through repeated trials

The learning process is based on **Q-Learning**, a model-free RL technique where the agent learns from experience without requiring a model of the environment.

---

## 🧠 Key Concepts

- **Reinforcement Learning**
- **Q-Learning Algorithm**
- **State-Action-Reward Dynamics**
- **Exploration vs Exploitation**
- **Training over Episodes**

---

🎮 How It Works

➤ Q-Learning Formula
Q(s, a) ← Q(s, a) + α [r + γ max Q(s', a') - Q(s, a)]



Where:
	•	s: current state
	•	a: action taken
	•	r: reward received
	•	s': next state
	•	α: learning rate
	•	γ: discount factor

➤ Training Process
	•	The agent starts with an empty Q-table.
	•	It plays multiple episodes of the game.
	•	At each step, it chooses an action using an ε-greedy policy.
	•	After each move, the Q-table is updated based on the reward and next state.
	•	Over time, it converges to an optimal policy.

⸻

📊 Results
	•	The agent improves with each episode.
	•	It learns to avoid ghosts and prioritize food.
	•	Convergence can be visualized using reward plots over episodes (provided in report).

⸻

📈 Sample Output
Episode: 50 | Total Reward: 110
Episode: 100 | Total Reward: 150
...
Agent successfully avoids ghosts and clears levels!
✍️ Author

Developed by Chaitanya Handore
📫 chaitanyahandore@gmail.com
🔗 LinkedIn | GitHub






