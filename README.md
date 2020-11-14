# Reinforcement-Learning

This repository contains implementation of Reinforcement Learning on Autonomous hill climbing example with the help of OpenAI gym environment. 
 
Abstract: Developing a Reinforcement Learning model Using OpenAI that automatically learns to climb a one-dimensional hill to reach a target and acheive the best possible score over time. An underpowered car must climb a one-dimensional hill to reach a target.
The target is on top of a hill on the right-hand side of the car. If the car reaches it or goes beyond, the episode terminates. On the left-hand side, there is another hill. Climbing this hill can be used to gain potential energy and accelerate towards the target. On top of this second hill, the car cannot go further than a position equal to -1, as if there was a wall.


### A. Observation:
```
$ Car Position 
$ Car Velocity
```


### B. Actions:
```
$ 0 = push left
$ 1 = no push
$ 2 = push right
```

### C. Reward:
```
$ -1 for each time step, until the goal position of 0.5 is reached
```

Dependencies:
- gym
- numpy
- matplotlib

