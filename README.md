# Connect Four Game:

A Connect Four game built with Python and Pygame. The game allows the player to play against an AI opponent. The game board is represented as a two-dimensional numpy array and the AI uses a simple heuristic to make its moves.

# How To Play:

1. Install Python and Pygame.
2. Clone the repository.
3. Run the file "connect_four.py".
4. Use the mouse to select the column you want to drop your piece in.
5. The game ends when a player gets four pieces in a row either horizontally, vertically, or diagonally.

# Minimax Algorithm:

The AI of the project is powered by the Minimax algorithm. Minimax is a decision-making algorithm used in two-player games, such as tic-tac-toe, chess, or go, to determine the optimal move for a player.

In this project, the algorithm works by evaluating all possible moves for the current player, and then calculating the best move for that player, assuming that their opponent will play optimally as well. The algorithm considers the current state of the game, assigns a value to each possible move based on that state, and chooses the move with the highest value.

By evaluating all possible moves and considering the optimal response of the opponent, the Minimax algorithm ensures that the AI will make the best move possible, maximizing its chances of winning the game and minimizing the chances of losing.

The implementation of the Minimax algorithm can be found in the main.py file, where it is used to determine the optimal move for the AI player in each turn of the game.

# Contributions:

This project is open for contributions. If you have an idea for a new feature or a bug fix, feel free to create a pull request.

#License:

This project is licensed under the MIT License. This means that you are free to use, modify, and distribute the code, as long as you include the original copyright and license notice in any copy of the software/source.
