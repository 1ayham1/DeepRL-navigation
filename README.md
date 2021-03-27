[//]: # (Image References)

[image1]: https://user-images.githubusercontent.com/10624937/42135619-d90f2f28-7d12-11e8-8823-82b970a54d7e.gif "Trained Agent"

# Deep Reinforcement Learning ND
# Project 1: Navigation

### Introduction

Train an agent to navigate (and collect bananas!) in a large, square world. The reward is assigned as follows:
- **`+1`**  for collecting a yellow banana
- **`-1`**  for collecting a blue banana.  

Thus, the goal of your agent is to collect as many yellow bananas as possible while avoiding blue bananas.   

![Trained Agent][image1]


The state space has 37 dimensions and contains the agent's velocity, along with ray-based perception of objects around agent's forward direction.  The agent has to learn how to best select actions.  Four discrete actions are available, corresponding to:
- **`0`** - move forward.
- **`1`** - move backward.
- **`2`** - turn left.
- **`3`** - turn right.

The task is episodic, and the environment is solved if the agent obtained an average score of +13 over 100 consecutive episodes.


### Getting Started
Dependencies, resources, links and further information can be found in the main repository [Udacity DRLND](https://github.com/udacity/deep-reinforcement-learning/tree/master/). Requirements include setting up PyTorch, the ML-Agents toolkit, and a few more Python packages.

1. Download a suitable environment from one of the links below.  
    - Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux.zip)
    - Mac OSX: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana.app.zip)
    - Windows (32-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86.zip)
    - Windows (64-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86_64.zip)


2. Place the file in the DRLND GitHub repository, in the `p1_navigation/` folder, and unzip (or decompress) the file.

### Instructions To Run

After managing all dependencies, please follow the instructions in `Navigation.ipynb`.


### (Optional) Challenge: Learning from Pixels. To be completed

The state is an 84 x 84 RGB image, corresponding to the agent's first-person view.  

You need only select the environment that matches your operating system:
- Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/VisualBanana_Linux.zip)
- Mac OSX: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/VisualBanana.app.zip)
- Windows (32-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/VisualBanana_Windows_x86.zip)
- Windows (64-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/VisualBanana_Windows_x86_64.zip)

Then, place the file in the `p1_navigation/` folder in the DRLND GitHub repository, and unzip (or decompress) the file.  Next, open `Navigation_Pixels.ipynb` and follow the instructions to learn how to use the Python API to control the agent.

(_For AWS_) If you'd like to train the agent on AWS, you must follow the instructions to [set up X Server](https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Training-on-Amazon-Web-Service.md), and then download the environment for the **Linux** operating system above.
