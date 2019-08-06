# DRLND-Proj3-Continuous_Control
The goal of this project is to train a double-jointed arm to reach target locations

## Project Details
This project is intended to provide an opportunity for students to gain more experience using Unity’s ML-Agents machine learning toolset and apply their knowledge of  Asynchronous Advantage Actor-Critic (A3C), Deep Deterministic Policy Gradient (DDPG), or Proximal Policy Optimization (PPO) algorithms to train a Deep Reinforcement Learning (DRL) agent to perform a task.  The task is to train a double-jointed arm to track a target location as it orbits the arms anchor point.  The defined task environment includes 33 variables which include position, rotation, velocity, and angular velocities of the arm.  The action performed by the agent is a four element vector corresponding to the torque at each of the two joints.  Each element in the vector is a number that ranges from -1 to +1.  A reward of +0.1 is given to the agent for every step the agent’s hand is touching the target area.  There are two versions of the environment which include a single agent or 20 agent distributed training scenario. The task is considered solved when the agent yields an average score of +30 over 100 consecutive episodes.

## Dependencies (for RTX 2080 Super GPU)
- https://github.com/udacity/deep-reinforcement-learning#dependencies
- PyTorch v1.1.0
- Python 3.7
- CUDA 10.0
- cuDNN 7.6.2 for CUDA 10.0
- Unity ML Agents

## Instructions
Clone https://github.com/udacity/deep-reinforcement-learning
1. Follow the instructions in the DRLND GitHub repository and setup the specified dependencies
2. Clone this repository
3. Copy all files located in this cloned repository into the following cloned deep-reinforcement-learning local directory "...\deep-reinforcement-learning\p2_continuous-control"
4. Unzip "Reacher_Windows_x86_64.zip"
5. Update the file_name= directory on line 2 of the first cell beneath the header "2. Instantiate the Enviornment and Agent and Examine the State and Action spaces" to point to the local directory of the unzipped "Reacher_Windows_x86_64" directory
6. Execute the code located in Continuous_Control.ipynb after the "4. It's Your Turn!" heading
