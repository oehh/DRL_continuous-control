[//]: # (Image References)

[image1]: https://user-images.githubusercontent.com/10624937/43851024-320ba930-9aff-11e8-8493-ee547c6af349.gif "Trained Agent"
[image2]: https://user-images.githubusercontent.com/10624937/43851646-d899bf20-9b00-11e8-858c-29b5c2c94ccc.png "Crawler"

# Continuous Control

### Introduction

For this continuous control project, you will work with the [Reacher](https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Learning-Environment-Examples.md#reacher) environment.

![Trained Agent][image1]

In this environment, a double-jointed arm can move to target locations. A reward of +0.1 is provided for each step that the agent's hand is in the goal location. Thus, the goal of your agent is to maintain its position at the target location for as many time steps as possible.

The observation space consists of 33 variables corresponding to position, rotation, velocity, and angular velocities of the arm. Each action is a vector with four numbers, corresponding to torque applicable to two joints. Every entry in the action vector should be a number between -1 and 1.

For this project, there are two separate versions of the Unity environment, where this solution is handling the first version that contains (only) a single agent.

The task is episodic, and in order to solve the environment,  the agent must get an average score of +30 over 100 consecutive episodes.

### Dependencies

To set up your python environment to run the code in this repository, follow the instructions below.

Create (and activate) a new environment with Python 3.6.

Linux or Mac: 
- conda create --name drlnd python=3.6 
- source activate drlnd

Windows: 
- conda create --name drlnd python=3.6 
- activate drlnd

Follow the instructions in this repository (https://github.com/openai/gym) to perform a minimal install of OpenAI gym.

Clone the repository (if you haven't already!), and navigate to the python/ folder. Then, install several dependencies.

- git clone https://github.com/udacity/deep-reinforcement-learning.git
- cd deep-reinforcement-learning/python
- pip install .

### Getting Started

1. Download the environment from one of the links below.  You need only select the environment that matches your operating system:

    - **_Version 1: One (1) Agent_**
        - Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher_Linux.zip)
        - Mac OSX: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher.app.zip)
        - Windows (32-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher_Windows_x86.zip)
        - Windows (64-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher_Windows_x86_64.zip)

2. Place the file in the DRLND GitHub repository, in the `p2_continuous-control/` folder, and unzip (or decompress) the file. 

### Instructions

Go to `Continuous_Control.ipynb` for training and running the trained agent. 

This files references to a feed-forward neural network (see model.py) and to the agent (see ddpg_agent.py).
