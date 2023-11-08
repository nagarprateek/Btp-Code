## Reinforcement learning based Tic-Tac-Toe playing agent

#### This is a simple C++ implementation of a tic-tac-toe playing agent based on Q Learning. We maintain a table of Q values for every (state, action) pair in 'table.txt'. Actions are then sampled via an epsilon greedy policy. We update our Q table by updating Q values for the (state, action) along the sampled trajectory depending on whether the game was won or lost.
#### </br>

### Running the Code
#### To play a game against the agent, compile the code via:
#### ```g++ tictactoe.cpp -o tictactoe```
#### To execute, run:
#### ```./tictactoe```</br></br>

#### Notes: 
#### The agent always starts and plays with 'X' (represented as 1). You play 'O' (represented as 0).
#### Actions are the position you would like to place 0 on the board. Reading the positions from left to right and up to down, they are represented by the integers 0-9.
