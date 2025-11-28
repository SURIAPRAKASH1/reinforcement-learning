*From below video as you can see DQN found's optimal policy to solve Continuous-State MountainCar problem (takes 84 time-steps)*
<video src="https://github.com/user-attachments/assets/abd065bf-e143-423a-8d44-c72ef27ce63f" width="640" height="480" controls></video>

# Why this repo

_Note: Ongoing project ..._

If you’re learning RL or want reproducible baselines, this repo gives hands-on, readable implementations of the algorithms you always hear about in lectures but rarely see in clean, comparable form. It’s focused on intuition and reproducibility rather than fancy libraries — perfect for learning, teaching, or quickly prototyping ideas.

# Algorithms & environments implemented

## Algorithms

- Tabular: Policy Evaluation, Policy Iteration, Value Iteration

- On-policy control: SARSA (1-step, n-step)

- Off-policy control: Q-learning (1-step, n-step variants)

- Function approximation: Linear value approx, small MLP approximators

- Policy gradient: REINFORCE (+ baseline), Actor-Critic

## Environments

- MountainCar-v0 — classic continuous state, sparse reward

- CliffWalking-v0 — tabular, risky policy behavior
- Gambler — find optimal policy
