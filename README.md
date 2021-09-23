# Deep-Reinnforcement-Learning-Udacity
This collects all the projects done by me for Udacity Deep Reinforcement Learning course

## 1 The environment can be downloaded from:

* Linux: https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux.zip

* Mac OSX: https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana.app.zip

* Windows (32-bit): https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86.zip

* Windows (64-bit): https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86_64.zip

The Project is done using the Unity Banana environment.

## 2 Activate the environment:

Please follow the instructions in the [DRLND GitHub repository](https://github.com/udacity/deep-reinforcement-learning#dependencies) given to set up the Python environment. By following these instructions, you can install PyTorch, the ML-Agents toolkit, and a few other Python packages required to complete the project.

(For Windows users) The ML-Agents toolkit supports Windows 10. Furthermore, the ML-Agents toolkit has not been tested on a Windows VM such as Bootcamp or Parallels.

We donot need to install it just select apt zip file, unzip it and put it in your project folder. We need to call it from the notebook.

# Reward structure:

The reward we can get is +1 for collecting fresh yellow banana or -1 for collecting roten purple banana.

# Actions Space:

* 0 - move forward.
* 1 - move backward.
* 2 - turn left.
* 3 - turn right.

# State Space:

The state space has 37 dimensions and contains the agent's velocity, along with ray-based perception of objects around the agent's forward direction.

