# DRLND-Proj3-Continuous_Control
The goal of this project is to train a double-jointed arm to reach target locations

# Project Details
This project is intended to provide an opportunity for students to gain more experience using Unity’s ML-Agents machine learning toolset and apply their knowledge of  Asynchronous Advantage Actor-Critic (A3C), Deep Deterministic Policy Gradient (DDPG), and Proximal Policy Optimization (PPO) algorithms to train a Deep Reinforcement Learning (DRL) agent to perform a task.  The task is to train a double-jointed arm to track a target location as it orbits the arms anchor point.  The defined task environment includes 33 variables which include position, rotation, velocity, and angular velocities of the arm.  The action performed by the agent is a four element vector corresponding to the torque at each of the two joints.  Each element in the vector is a number that ranges from -1 to +1.  A reward of +0.1 is given to the agent for every step the agent’s hand is touching the target area.  There are two versions of the environment which include a single agent or 20 agent distributed training scenario.

# Dependencies
- PyTorch v1.1.0
- Python 3.6
- Unity ML Agents

# Instructions
1. Download Reacher Environment from the appropriate link below:
2. Copy the downloaded zip file into the continuous_control directory and unzip it's contents
3. Execute the code located in Continuous_Control.ipynb
4. Use ddpg_agent.py to adjust the agents hyperparameters
