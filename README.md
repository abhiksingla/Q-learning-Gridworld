# Q-learning-Gridworld
This is a simple example of solving Gridworld problems using a special type of Reinforcement Learning called Q-learning.

	● Rules: The agent (yellow box) has to reach one of the goals to end the game (green or red cell).
	● Rewards: Each step gives a negative reward of -0.04. The red cell gives a negative reward of -1. The green one gives a positive reward of +1.
	● States: Each cell is a state the agent can be.
	● Actions: There are only 4 actions. Up, Down, Right, Left.
  
# Dependencies
* `tkinter`
If on Ubuntu you can install tkinter for python2.7 with ``$ sudo apt-get install python-tk``

# Usage
Run `python Learner.py <Number of Rows> <Number of Columns>` in terminal to see the the bot in action. It'll find the optimal strategy pretty fast (like in 15 seconds). Number of Rows and Columns should be greater than (5*5). Add more obstacles and terminal states by modifying `World.py`.

# Credit
This is code is highly based on [Youtube Tutorial](https://youtu.be/A5eihauRQvo) by [Siraj Raval](https://github.com/llSourcell).
