# AIReacher Project Overview
<img src=images/Reacher.gif width="684">

In this environment, a double-jointed arm can move to target locations. A reward of +0.1 is provided for each step that the agent's hand is in the goal location. Thus, the goal of your agent is to maintain its position at the target location for as many time steps as possible.  The observation space consists of 33 variables corresponding to position, rotation, velocity, and angular velocities of the arm. Each action is a vector with four numbers, corresponding to torque applicable to two joints. Every entry in the action vector should be a number between -1 and 1.

The observation space consists of 33 variables corresponding to position, rotation, velocity, and angular velocities of the arm. Each action is a vector with four numbers, corresponding to torque applicable to two joints. Every entry in the action vector should be a number between -1 and 1.

# Problem Statement
Develop an AI Agent using 'actor-critic' methods - which should learn the best policy to maximize its rewards by taking best actions in the given continuous environment  

#Goal 
The environment is considered solved, when the average (over 100 episodes) of those average scores is at least +30.

# What you can learn:
Deep Reinforcement Learning ,In simple , a mathematical way to clone the experiences start with trial and error (reward & punishment) approach to form a #digitalmemory (Policy with Critic) and take the best actions based on current situation to maximize the rewards like how a Toddler learn to play a Cricket  motivated by 'high scorer' achievement.

This project simply help you to get the core of how AI works and detail implementation of Deep Deterministic Policy Gradients alogorithm .


**5 Winning Rules for AI too !** <<WIP>>

<img src=images/DDPG.png width="684">


# Environment Setup:
1. Anaconda Navigator - python 3.6
2. PyTorch 
 Example: conda install pytorch torchvision cudatoolkit=10.2 -c pytorch
 select right commands based on your OS , Python and conda/pip 
  https://pytorch.org/get-started/locally/>
  
3.UnityAgent

  
For the detail instruction please check https://github.com/udacity/deep-reinforcement-learning/blob/master/p1_navigation/README.md
To setup, you need Python 3.6, Unity Environment to be installed.Once you setup your python environment , have agent.py ,nn_model.py and checkpoint17.pt if you wish to directly test the trained Agent.
