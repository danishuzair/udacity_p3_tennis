# Project 3: Collaboration and Competition

### 1. Introduction

The objective of the project is to train agents in the "Tennis" environment, where two agents are playing tennis against one another. The reward structure is setup such that each time an agent hits the ball over the net, a reward of +0.1 is received. Additionally, each time the agents lets the ball hit the ground or out of bounds, a reward of -0.01 is received. The goal of the agent is to keep hitting the ball over the net.

### 2. Installing dependencies
To able to run the training environment, the following dependencies need to be installed:
Setup your environment per the instructions found in the README file in the following [link](https://github.com/udacity/deep-reinforcement-learning#dependencies)

Download the Unity environment from the link below that matches your operating system:
- Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis_Linux.zip)
- Mac OSX: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis.app.zip)
- Windows (32-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis_Windows_x86.zip)
- Windows (64-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis_Windows_x86_64.zip)

### 3. Running the scripts
The main file that will take care of initializing the environment, doing the training, and running a trained agent in the environment is the Tennis.ipynb file. Before running this file, ensure that the following files are at the same location as the Tennis.ipynb file:
- ddpg_agent.py
- model.py
- Reacher.app
- checkpoint.pth

### 4. Importing all the libraries
To import all the required libraries, run the block of code in the first section of the Tennis.ipynb script. This section is titled "Importing Libraries".

### 5. Taking random actions in the environment
To have an agent take random actions in the environment, follow the steps below:
1. Restart the jupyter notebook kernel
2. Run the code in section 1 of Tennis.ipynb: "Importing Libraries"
3. Run the code in section 2 of Tennis.ipynb: "Opening the environment and taking random actions"

### 6. Training an agent using Deep Deterministic Policy Gradient (DDPG)
To train an agent using DDPG, follow the steps below:
1. Restart the jupyter notebook kernel
2. Run the code in section 1 of Tennis.ipynb: "Importing Libraries"
3. Run the code in section 3 of Tennis.ipynb: "Training an agent"

### 7. Run a trained agent in the environment
To run a trained agent in the environment, follow the steps below:
1. Restart the jupyter notebook kernel
2. Run the code in section 1 of Tennis.ipynb: "Importing Libraries"
3. Run the code in section 4 of Tennis.ipynb: "Run environment using a trained agent (by importing a checkpoint)"

### 8. References
Please note that the code used originates from the DDPG code that was provided in the Udacity Deep Reinforcement Learning class, and then modifcations were done to make it applicable for the specific environment that was solved. Similarly, some of the content of the README file originates from the Udacity Deep Reinforcement Learning class, as well as from my submission for the first and second projects of this class.