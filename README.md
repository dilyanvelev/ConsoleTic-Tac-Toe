# ConsoleTic-Tac-Toe
A simple command-line Tic-Tac-Toe game implemented in Python. Play against a friend and see who can achieve victory first!

How to Play
Clone this repository to your local machine:

shell
Copy code
git clone https://github.com/yourusername/tic-tac-toe.git
Navigate to the project directory:

shell
Copy code
cd tic-tac-toe
Run the game:

shell
Copy code
python tic_tac_toe.py
Follow the on-screen instructions to input player names and symbols.

Take turns choosing a free position on the board by entering a number between 1 and 9.

The first player to complete a row, column, or diagonal with their symbol ('X' or 'O') wins the game!

Game Rules
The game is played on a 3x3 board.
Players take turns choosing a free position on the board.
The first player to complete a row, column, or diagonal with their symbol ('X' or 'O') wins.
If all positions on the board are filled, and no player has won, the game ends in a draw.
Code Overview
Here's a brief overview of the key functions in the source code:

start(): Initializes the game by getting player names and symbols.
print_board(begin=False): Prints the current state of the board. If begin is True, it also displays the board numeration and the starting player.
choose_position(): Allows the current player to choose a free position on the board.
place_symbol(position): Places the current player's symbol on the chosen position and checks for a win condition.
check_for_win(): Checks if the current player has won the game by examining rows, columns, and diagonals.
Feel free to explore and modify the code to enhance your Tic-Tac-Toe experience!

Have fun playing! 🎮





