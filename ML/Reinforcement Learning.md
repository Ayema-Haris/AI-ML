# Reinforcement Learning

Reinforcement Learning (RL) is a type of machine learning where an agent learns  
by **interacting with an environment** and **learning from feedback**.

Instead of being told the correct answer, the agent learns by **trial and error**.

---

## 1. What is Reinforcement Learning?

- The model (called an **agent**) takes actions in an **environment**
- The environment returns a **reward or penalty**
- Goal: **Maximize total reward over time**

**Key idea:**  
Learn what to do by *trying*, *failing*, and *improving*.

---

## 2. Core Components of Reinforcement Learning

Every reinforcement learning problem has these parts:

### Agent
- The learner or decision-maker  
- Example: Robot, game AI, self-driving car

### Environment
- The world the agent interacts with  
- Example: Game board, road, simulation

### Action
- What the agent can do  
- Example: Move left/right, accelerate, jump

### Reward
- Feedback from the environment  
- Positive → good action  
- Negative → bad action  

---

## 3. Simple Example

**Example: Teaching a Dog a Trick**

- Dog = Agent  
- Sitting, jumping = Actions  
- Treat = Reward  
- No treat = Penalty  

The dog tries different actions and slowly learns  
which action gives the most treats.

That’s reinforcement learning.

---

## 4. How Reinforcement Learning Works

1. Agent observes the current **state**
2. Agent chooses an **action**
3. Environment changes
4. Agent receives a **reward**
5. Agent updates its strategy
6. Process repeats 🔁

Over time, the agent learns the **best actions**.

---

## 5. Common Algorithms

- Q-Learning
- SARSA
- Deep Q-Networks (DQN)
- Policy Gradient Methods

---

## 6. Key Characteristics

- No labeled data
- Learning happens through interaction
- Feedback is delayed (reward comes later)
- Focused on long-term success, not instant gain

---

## 7. Where Reinforcement Learning is Used

- Game playing (Chess, Go)
- Robotics
- Self-driving cars
- Recommendation systems
- Resource optimization

---

## 8. Comparison with Other Learning Types

| Type | Data | Feedback | Goal |
|-----|-----|---------|-----|
| Supervised | Labeled | Immediate | Predict output |
| Unsupervised | Unlabeled | None | Find patterns |
| Reinforcement | No labels | Rewards/Penalties | Maximize reward |

---

## Conclusion

- Reinforcement Learning = Learn by **doing**
- No correct answers are given upfront
- The agent improves through **experience**
- It is powerful but harder than supervised learning

Reinforcement learning is inspired by **how humans and animals learn** —  
by interacting with the world and adapting over time.
