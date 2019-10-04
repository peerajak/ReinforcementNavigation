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

2. Change directory to the cloned directory. Download the Unity Environment
Linux: https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux.zip
and unzip to the cloned directory

3. Make sure that your kernel is the installed dependencies, in this case, dlnd enviroment. 
>python -m jupyter notebook Navigation.ipynb
The ipython file should be automatically shown on your web browser. 

4. Save your model
>agent.save_model(< your file Path here >)
Check the saved file at your file path.

5. Initiate new empty model and reload the saved model
>agent2 = Agent(brain.vector_observation_space_size, brain.vector_action_space_size, seed=0)
>agent2.load_model(< your file Path here >)

6. Environment solved. This is shown in the last two cells at the end of the Navigation.ipynb,
  where random agent are test against the trained agent. Clearly, the train agents, with avg score of ~14, triumps over random agent.

### Understanding the Algorithm
Please read Report.pdf to understand the implementation of deep Q network and their parameters. 





