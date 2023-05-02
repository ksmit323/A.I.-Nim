# A.I.-Nim
This is an AI program that plays Nim with a command-line interface. It allows you to play against an AI that uses the Q-learning algorithm to determine the best possible move. 

# Installation
To run the program, you'll need Python 3.7 or later installed on your computer. You can install Python by following the instructions on the official Python website.

Once you have Python installed, download the source code from the repository and navigate to the project directory in your terminal.
```
git clone https://github.com/ksmit323/A.I.-Nim.git
cd A.I.-Nim
```

# Usage
To start the game, run the **'runner.py'** file.
```
python runner.py
```
The game will ask you to choose whether you want to go first or second. Once you've chosen, the game will start and display the number of sticks on the board.

To make a move, enter the number of sticks you want to take from the board. The AI will then make its move, and the game will continue until one player wins or there are no sticks left on the board.

## Q-Learning
**Q-Learning** is a reinforcement learning technique that allows an agent to learn the best action to take in a particular situation based on the rewards it receives. In the case of this program, the agent is the AI, and the rewards are determined by whether the AI wins or loses the game.

During the game, the AI keeps track of the state of the game and the actions it takes in that state. It then updates its Q-table, which is a table that maps states to actions and their associated rewards. The AI uses this table to determine the best possible move in a given state.
