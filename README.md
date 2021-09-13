# ConnectThreeAI
In this project we apply reinforcement learning in order to train an agent and perform optimally in a game of Connect Three.

Connect Three is a variation of the Connect Four game. This is a two-player game where each player is given disks of a particular colour. The players take turns dropping one of their disks from above the grid, into one of the columns. The piece falls straight down, occupying the lowest empty slot within the column. The objective of the game is to be the first to form a horizontal, vertical, or diagonal line of three discs. If the grid fills up before either player achieves the objective, the game is a draw. The game is played on a 3*5 grid.

We compare three different agents:
* Q-Learning
* Minimax
* Random

The repository consists of:
* **ai4_connect_three.ipynb** file where the agents are trained and compared
* **connect.py**, **utils.py** which hold the API of the board game.
