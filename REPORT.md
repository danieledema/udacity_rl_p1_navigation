# P1: Navigations

## Learning Algorithm
The core part of the agent is a _double DQN_, composed by three fully connected layers, and a _prioritized qcperience replay_.
Most of the code has been reused from the _DQN_ project.

## Rewards
In the Jupyter Notebook file, a plot of the review can be seen.
The training procedure has been stopped as soon as the reward reached 15 (episode 900), while 13 has been passed at the episode 600.

## Ideas for Future Work
To improve the work it is possible to implement the _dueling DQN_ paradigm.
