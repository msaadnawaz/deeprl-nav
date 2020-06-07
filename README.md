#Project 1: Navigation - Banana Collector
This project is part of Udacity Deep Reinforcement Learning Nanodegree.

##Project Details
The goal of the banana collector agent is to collect as many yellow bananas within the given time of episode and avoid blue bananas.

The banana collector environment has 37 possible states and four possible actions available. The environment is considered solved when the agent starts to score beyond 16 for the episode on average.

##Getting Started
The project has dependency on following libraries:

* Python 3
* PyTorch
* UnityEnvironment
* Matplotlib
* Numpy

##Instructions
The project has Navigation (Jupyter) Notebook as the base file. 

The environment class is called in the notebook to show the state and action spaces. The dqn() function is defined in the notebook which calls the agent class defined in dqn_agent.py to select take actions and to learn after each step. 

The neural network model is defined in model.py which is called by the learning function (Agent.step).

Project report discusses the learning algorithm and results.