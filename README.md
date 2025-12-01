# Final Project – Deep RL for Atari Pong

**Author:** Quoc Dat Cao   
**Repo URL:** https://github.com/QuocDatCao1425/final-project  

This project trains deep reinforcement learning agents to play Atari **Pong**.  
Starting from the course starter notebook, I implement and compare:

- A **baseline DQN** agent
- A **Double DQN (DDQN)** agent

## Repository Contents

- `pong.ipynb` – Main Jupyter notebook with all code for training and evaluation.
- `baseline-early-episode-0.mp4` – Baseline DQN agent, early in training.
- `baseline-learned-episode-0.mp4` – Baseline DQN agent after learning.
- `ddqn-early-episode-0.mp4` – Double DQN agent, early in training.
- `ddqn-learned-episode-0.mp4` – Double DQN agent after learning.
- `report.pdf` – Written report with method details, experiments, and discussion.
- `README.md` – This file.

---

## Starter Code Reference (Required by Assignment)

This project is adapted from the course starter notebook:

> **Starter notebook:**  
> [`c166f25_02b_dqn_pong.ipynb`](https://github.com/everestso/summer25/blob/main/c166f25_02b_dqn_pong.ipynb)

The overall structure of the environment setup and baseline DQN implementation comes from that notebook. I extended it with additional experiments and videos as described below.

---

## Project Description

The goal of this project is to train an agent to play **Atari Pong** using deep Q-learning. The agent interacts with the Pong environment (via the ALE / OpenAI Gym / Gymnasium interface), observes image frames, and learns a policy that maximizes game score.
