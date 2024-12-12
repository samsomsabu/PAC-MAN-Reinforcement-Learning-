
# Pacman Reinforcement Learning Exercise

![Pacman Image](assets/pacman.png)

## Overview

This project is part of the **Reinforcement Learning (RL)** course in the **M.Sc. Artificial Intelligence and Machine Learning** program at **Christ (Deemed to be University), Bangalore**. The exercise is based on the **UC Berkeley RL Exercise**, which includes a Pacman game framework designed to train RL agents to play the game (or a simplified version of it).

## Team Members

- **Samson Sabu**  
- **Guhan K.S.**

## Objective

The goal of this project is to apply reinforcement learning algorithms to train agents capable of navigating and playing Pacman. We have also modified the original framework to make our implementation unique and tailored to our course objectives.

## Modifications

We have introduced some changes to the UC Berkeley Pacman game framework, including:

- **Custom Environment Tweaks**: Modified game dynamics and environment settings to introduce new challenges.  

## Key Components

1. **Agent Training**  
   - Implemented RL algorithms such as Q-Learning.  
   - Tuned hyperparameters for optimal performance in the modified environment.

2. **Environment Setup**  
   - Customized the Pacman grid and gameplay logic to ensure diversity in training scenarios.

3. **Performance Evaluation**  
   - Analyzed the agents' performance using metrics like cumulative rewards and survival time.

## Getting Started

1. Clone this repository:  
   ```bash
   git clone https://github.com/samsomsabu/PAC-MAN-Reinforcement-Learning-Project/blob/main/Readme.md
   cd pacman-rl
   ```

2. Install dependencies:  
   ```bash
   pip install -r requirements.txt
   ```

3. Run the Pacman game:  
   ```bash
   python pacman.py
   ```

4. Train RL agents:  
   ```bash
   python train_agent.py
   ```

## Future Work

- Implement multi-agent scenarios to explore collaborative and competitive behaviors.  
- Experiment with transfer learning to adapt trained agents to new environments.  
- Explore additional algorithms like Actor-Critic and PPO.
