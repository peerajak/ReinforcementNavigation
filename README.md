# ReinforcementNavigation
# Project 1: Navigation
# by Peerajak Witoonchart as a project for Udacity deep reinforcement learning nano degree.
Suppose you are to build an automatic banana eating monkey robot, how could you do?. Suppose there are two kinds of banana, the yellow bananas which taste good, and the dark blue bananas which taste bad. How could you program the monkey robot in such a way that it selects only yellow bananas?  To solve this problem, let us start with a human controllable handjoy and control the monkey robot manually. We have
- **`0`** - move forward.
- **`1`** - move backward.
- **`2`** - turn left.
- **`3`** - turn right.
, where the **'n'** is the nth botton of handjoy.

In this project, we will show how to write a program, called an agent, to build an automatic banana eating monkey robot for a virtual continuous environment containing both yellow and dark blue bananas.

 



### Introduction

To solve this problem, we apply Deep Q network. In Navigation.ipynb, the Deep Q network algorithm is implemented. 
### Getting Started
You need Python3 and some dependencies. An anaconda environment is recommended. Please follow 
https://github.com/udacity/deep-reinforcement-learning
on dependencies topic to have your enviroment and dependencies installed

After the above is done, you can start with

1. Clone the repository to your local machine
>git clone https://github.com/peerajak/ReinforcementNavigation.git

2. Make sure that your kernel is the installed dependencies, in this case, dlnd enviroment. 
>python -m jupyter notebook Navigation.ipynb

The ipython file should be automatically shown on your web browser. Then simply run all cells. Read all the instruction and comments in ipynb file.
### Understanding the Algorithm
Please read TechnicalReport.pdf. 

Project Rubic
- The submission includes the saved model weights of the successful agent. 
- state and action spaces, and when the environment is considered solved


- explain the performance different between random and trained agent
