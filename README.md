# Continuous-Control
Udacity Deep Reinforcement Learning Project 2

The algorithm used in this project is an actor-critic algorithm, the Deep Deterministic Policy Gradients (DDPG) algorithm.

# Project Details

This project is on the [**Reacher**](https://github.com/Unity-Technologies/ml-agents/blob/main/docs/Learning-Environment-Examples.md#reacher) environment.

In this environment, a double-jointed arm can move to target locations. A reward of +0.1 is provided for each step that the agent's hand is in the goal location. Thus, the goal of your agent is to maintain its position at the target location for as many time steps as possible.

The observation space consists of 33 variables corresponding to position, rotation, velocity, and angular velocities of the arm. Each action is a vector with four numbers, corresponding to torque applicable to two joints. Every entry in the action vector should be a number between -1 and 1.

The task is episodic, and in order to solve the environment, the agent must get an average score of +30 over 100 consecutive episodes.

# Getting Started

1. To set up Python environment, follow this [link](https://github.com/udacity/deep-reinforcement-learning#dependencies).

    The instructions can be found in README.md at the root of the repository. By following these instructions, you will install PyTorch, the ML-Agents toolkit, and a few more Python packages required to complete the project.

    (For Windows users) The ML-Agents toolkit supports Windows 10. While it might be possible to run the ML-Agents toolkit using other versions of Windows, it has not been tested on other versions. Furthermore, the ML-Agents toolkit has not been tested on a Windows VM such as Bootcamp or Parallels.

2. To download the Unity Environment, used one of the links below. Select the environment that matches your operating system.

    Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher_Linux.zip)

    Mac OSX: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher.app.zip)

    Windows (32-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher_Windows_x86.zip)

    Windows (64-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher_Windows_x86_64.zip)

3. Place the file in the p2_continuous-control/ folder in the DRLND GitHub repository, and unzip (or decompress) the file.

# Instructions
Follow the instructions in Continuous_Control.ipynb to get started with training your the agent.

# License
This project is licensed under the MIT License - see the [**LICENSE**](https://opensource.org/license/mit-license-php/) file for details.

# Acknowledgments
This project was completed as part of the [**Udacity Deep Reinforcement Learning**](https://www.udacity.com/course/deep-reinforcement-learning-nanodegree--nd893) Nanodegree program.
