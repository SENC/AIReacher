# AI - Deep Reinforcement Learning (DRL) - Continuous space - Policy based - 'Actor-Critic' - DDPG :
Deep Reinforcement Learning (DRL) ,In simple , a mathematical way to clone the experiences start with trial and error (reward & punishment) approach to form a #digitalmemory (Policy with Critic) and take the best actions based on current situation to maximize the rewards like how a Toddler learn to play a Cricket  motivated by 'high scorer' achievement.

This project simply help you to get the core of how AI works and detail implementation of Deep Deterministic Policy Gradients (DDPG) algorithm .


# 9 steps for AI to Win n Continuous...

<img src=images/9StepsDDPG_ActorCriticv2.png width="684">

# AIReacher Project Overview

This Reacher project is as part of Udacity Nanodegree - AI Deep Reinforcement Learning Expert and aims to develop an AI Agent - "a double-jointed arm" - move to target location in Continuous space using  Policy-based 'Actor-critic' Methods using Deep Neural Networks. 

The Environment preview

<img src=images/Reacher.gif width="684">

In this environment, a double-jointed arm can move to target locations. A reward of +0.1 is provided for each step that the agent's hand is in the goal location. Thus, the goal of your agent is to maintain its position at the target location for as many time steps as possible.  The observation space consists of 33 variables corresponding to position, rotation, velocity, and angular velocities of the arm. Each action is a vector with four numbers, corresponding to torque applicable to two joints. Every entry in the action vector should be a number between -1 and 1.

The observation space consists of 33 variables corresponding to position, rotation, velocity, and angular velocities of the arm. Each action is a vector with four numbers, corresponding to torque applicable to two joints. Every entry in the action vector should be a number between -1 and 1.

# Problem Statement
Develop an AI Agent using 'actor-critic' methods - which should learn the best policy to maximize its rewards by taking best actions in the given continuous environment  

#Goal 
The environment is considered solved, when the average (over 100 episodes) of those average scores is at least +30.

# Files :

1. Report.pdf: Gives complete project implementation report with results
2. DDPG/Continuous_Control _local_windowsEnv.ipynb : Python Notebook "DDPG Implementation and test and validation in windows env"
3. DDPG/agent.py : DDPG Agent class defintion and Utility functions like Replay Memory and OUNoise funtions
4. DDPG/nn_model.py : Actor and Critic Neural Network Architecture
5. DDPG/checkpoint_actor30.pth : Trained Agent's Neural Network weights - Actor (Ploicy)
6. DDPG/checkpoint_critic30.pth: Trained Agent's Neural Network weights - Critic (state-action Value)
7. DDPG/Reacher.exe : Unity Environment for Windows- 64bit



# Environment Setup:
For Environment setup, you need Python 3.6, pytorch ,Ml-agents, Unity Environment to be installed. Once you setup your python environment , you just needs to have agent.py ,nn_model.py and Continuous_Control.ipynb if you wish to have quick hands-on .
1. Anaconda Navigator - python 3.6
2. PyTorch 
 Example: conda install pytorch torchvision cudatoolkit=10.2 -c pytorch
 select right commands based on your OS , Python and conda/pip 
  https://pytorch.org/get-started/locally/>
3. Unity Environment 
   https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Installation.md
   
4.More detail on  Ml-Agents 
   https://github.com/Unity-Technologies/ml-agents/blob/master/docs/ML-Agents-Overview.md

5.Windows Env setup details - deprecated but may be useful
  https://hub.udacity.com/rooms/community:nd893:845401-project-503-smg-2/community:thread-12988088548-3621024?messageId=3652300&contextType=room

  
For the detail instruction please check https://github.com/udacity/deep-reinforcement-learning/blob/master/p1_navigation/README.md

