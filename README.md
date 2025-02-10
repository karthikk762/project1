Description
This project is a simple implementation of the classic Tic-Tac-Toe game in Python. It supports both single-player (against the computer) and multiplayer (two players) modes. The game uses the minimax algorithm for the computer's AI, ensuring a challenging experience for the player.

Features
Single-player mode: Play against the computer.
Multiplayer mode: Play with another person.
Minimax algorithm for AI.
Simple text-based interface.

Requirements
Python 3.x

Installation
Clone the repository or download the Tic_Tac_Toe_Project.py file.
Ensure you have Python installed on your system. You can download it from python.org.

How to Run
Open a terminal or command prompt.
Navigate to the directory where the Tic_Tac_Toe_Project.py file is located.

Run the following command:
bash
Copy
python Tic_Tac_Toe_Project.py
Follow the on-screen instructions to start the game.

Usage
Single-Player Mode
Choose 1 when prompted to play against the computer.
Select whether you want to play first or second.
Enter the position (1-9) where you want to place your 'X'.
The computer will make its move automatically.

Multiplayer Mode
Choose 2 when prompted to play with another person.
Players take turns entering the position (1-9) where they want to place their 'X' or 'O'.

Game Rules
The game is played on a 3x3 grid.
Players take turns marking a cell with their symbol ('X' or 'O').
The first player to get three of their symbols in a row (horizontally, vertically, or diagonally) wins.
If all cells are filled and no player has won, the game ends in a draw.

Code Structure
ConstBoard(board): Displays the current state of the game board.
User1Turn(board): Handles the user's (player X) turn.
User2Turn(board): Handles the second user's (player O) turn.
minmax(board, player): Implements the minimax algorithm for the computer's AI.
CompTurn(board): Handles the computer's turn.
analyzeboard(board): Checks if the game has been won or ended in a draw.
main(): The entry point of the program, handles user input and game flow.
