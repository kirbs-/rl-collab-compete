# Tennis

## How to run this project
1. Clone this repository `git clone https://github.com/kirbs-/rl-collab-compete`
2. Download the environment from one of the links below.  You need only select the environment that matches your operating system:
      - Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis_Linux.zip)
   - Mac OSX: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis.app.zip)
   - Windows (32-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis_Windows_x86.zip)
   - Windows (64-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis_Windows_x86_64.zip)
3. Place the file in the rl-collab-compete GitHub repository and unzip (or decompress) the file. 
4. Install dependencies with `pip install -r requirements.txt` **Note Python 3.7+ is required.**
5. Execute `Tennis.ipynb` notebook to train an agent.

## Environment
In this environment, two agents control rackets to bounce a ball over a net. If an agent hits the ball over the net, it receives a  reward of +0.1. If an agent lets a ball hit the ground or hits the ball out of bounds, it receives a reward of -0.01.  

The observation space consists of 8 variables corresponding to the position and velocity of the ball and racket. Each agent receives its own, local observation. Two continuous actions are available, corresponding to movement toward (or away from) the net, and jumping.  

The task is episodic, and in order to solve the environment, the agents must get an average score of +0.5 over 100 consecutive episodes (after taking the maximum over both agents).

