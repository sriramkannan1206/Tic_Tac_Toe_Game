Tic Tac Toe Game in C
-
This is a simple command-line implementation of the classic game Tic Tac Toe using C programming language.

How to Play
-
Download or clone the repository

Compile the code using a C compiler such as gcc

Run the executable file and start playing!

The game is played on a 3x3 grid. Players take turns placing their mark (either X or O) on an open square on the grid. The player who succeeds in placing three of their marks in a horizontal, vertical, or diagonal row wins the game.

Code Explanation
-
The main() function of the program implements the game loop, which continues until a win condition or a draw is reached.

The board() function prints the current state of the game board on the console.

The checkwin() function checks the current state of the board for a win condition, returning 1 if a player has won, -1 if the game is still in progress, and 0 if the game is a draw.
