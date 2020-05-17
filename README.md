[//]: # (Image References)

[image1]: https://github.com/Zaharah/unity-navigation-DRL-DQN/blob/master/Images/solved_banana.gif "Trained Agent"

# Banana collection RL Agent

### Introduction

An agent is trained to navigate in a square world to collect yellow bananas.  Following is a **agent in action**m trained with Double DQN algorithm for 1000 episodes. 

![Trained Agent][image1]

A reward of +1 is provided for collecting a yellow banana, and a reward of -1 is provided for collecting a blue banana.  The goal is to collect as many yellow bananas as possible while avoiding blue bananas.  

The state space has 37 dimensions and contains the agent's velocity, along with ray-based perception of objects around agent's forward direction.  Given this information, the agent has to learn how to best select actions.  Four discrete actions are available, corresponding to:
- **`0`** - move forward.
- **`1`** - move backward.
- **`2`** - turn left.
- **`3`** - turn right.

The task is episodic, and in order to solve the environment, your agent must get an average score of +13 over 100 consecutive episodes.

### Getting Started

1. Follow the instructions on the Udacity repo [here](https://github.com/udacity/deep-reinforcement-learning/#dependencies)
2. Download the unity environment. Select the environment that matches your operating system:

* Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux.zip)
* Mac OSX: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana.app.zip)
* Windows (32-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86.zip)
* Windows (64-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86_64.zip)

3. Place the file in the 'p1_navigation/' folder, and unzip (or decompress) the file.

### Instructions

* Follow the instructions in 'Navigation_project.ipynb' to train your agent.
* You can also use the saved model from 'Models/dqn' to see a trained agent in actions. 
