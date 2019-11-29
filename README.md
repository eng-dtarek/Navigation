# Project 1: Navigation

## Introduction

This project aims to train an agent to navigate (and collect bananas!) in a large, square world. A reward of +1 is provided for collecting a yellow banana, and a reward of -1 is provided for collecting a blue banana. Thus, the goal of this agent is to collect as many yellow bananas as possible while avoiding blue bananas.

The state space has 37 dimensions and contains the agent's velocity, along with ray-based perception of objects around the agent's forward direction. Given this information, the agent has to learn how to best select actions. Four discrete actions are available, corresponding to:

* move forward.
* move backward.
* turn left.
* turn right.

The target of the agent is to get an average score of +13 over 100 consecutive episodes.

## Dependencies

To set up your python environment to run the code in this repository, follow the instructions below.

1. Create (and activate) a new environment with Python 3.6.
    * Linux or Mac:
        ```
        conda create --name navigation python=3.6
        source activate navigation

        ```
    * Windows:
        ```
        conda create --name navigation python=3.6 
        activate navigation

        ```

2. Follow the instructions in [this repository](https://github.com/openai/gym) to perform a minimal install of OpenAI gym.

    * Next, install the classic control environment group by following the instructions [here](https://github.com/openai/gym#classic-control).
    * Then, install the box2d environment group by following the instructions [here](https://github.com/openai/gym#box2d).

3. Clone the repository (if you haven't already!), and navigate to the python/ folder. Then, install several dependencies.

```
git clone git@github.com:eng-dtarek/Navigation.git
cd Navigation/python
pip install .

```

4. Create an [IPython kernel](http://ipython.readthedocs.io/en/stable/install/kernel_install.html) for the navigation environment.

```
python -m ipykernel install --user --name navigation --display-name "navigation"
```

5. Before running code in a notebook, change the kernel to match the navigation environment by using the drop-down Kernel menu.

## Getting Started

1. Download the environment from one of the links below. You need only select the environment that matches your operating system:

* Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux.zip)
* Mac OSX: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana.app.zip)
* Windows (32-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86.zip)
* Windows (64-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86_64.zip)

For Windows users) Check out [this link](https://support.microsoft.com/en-us/help/827218/how-to-determine-whether-a-computer-is-running-a-32-bit-version-or-64) if you need help with determining if your computer is running a 32-bit version or 64-bit version of the Windows operating system.

(For AWS) If you'd like to train the agent on AWS and have not enabled a virtual screen, then please use [this link](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux_NoVis.zip) to obtain the environment.

2. Place the file in the repository, in the repository, and unzip (or decompress) the file.

3. Follow the instructions in Navigation.ipynb to get started with training your own agent!
