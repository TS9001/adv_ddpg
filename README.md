#### MDDPG Collaboration and Competition
Project using Reinforced learning and  modified MDDQN algorithm with Unity ML-Agents Tennis.
Implementation was made as part of Udacity Deep Reinforcement Learning Nanodegree.

##### *Environment:*

* In this environment, two agents control rackets to bounce a ball over a net
* If an agent hits the ball over the net, it receives a reward of +0.1
* If an agent lets a ball hit the ground or hits the ball out of bounds, it receives a reward of -0.01.
* Goal is to keep ball in the play
* The observation space consists of 8 variables corresponding to the position and velocity of the ball and racket
* Each agent receives its own, local observation. Two continuous actions are available, corresponding to movement toward (or away from) the net, and jumpingEach agent receives its own, local observation. Two continuous actions are available, corresponding to movement toward (or away from) the net, and jumping
* The task is episodic, and in order to solve the environment, your agents must get an average score of +0.5 (over 100 consecutive episodes, after taking the maximum over both agents)
* After each episode, we add up the rewards that each agent received, to get a score for each agent. This yields 2 (potentially different) scores. We then take the maximum of these 2 scores as single score for each episode.


#### Setup
1. Clone [DRLND Github repository](https://github.com/udacity/deep-reinforcement-learning#dependencies) 
2. Download the environment that matches your operating system:
    * *Linux*: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis_Linux.zip)
    * *Mac OSX*: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis.app.zip)
    * *Windows (32-bit)*: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis_Windows_x86.zip)
    * *Windows (64-bit)*: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis_Windows_x86_64.zip)
3. Place the file in the DRLND GitHub repository, in the p3_collab-compet/ folder, and unzip (or decompress) the file.

#### Instructions
* Follow the instructions in Tennis.ipynb to get started.

