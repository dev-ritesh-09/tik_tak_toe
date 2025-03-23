# Tic Tac Toe - Python Console Game

## Overview
This is a simple command-line implementation of the classic Tic Tac Toe game in Python. Two players take turns marking their spots on a 3x3 grid, and the game determines a winner based on the standard Tic Tac Toe rules.

## Features
- Two-player mode (X and O)
- Command-line interface
- Dynamic board display
- Automatic win detection

## How to Play
1. Run the script using Python.
2. The game starts with player **X**.
3. Players take turns entering a number (0-8) corresponding to the board position.
4. The board updates after each turn.
5. The game announces a winner when a player gets three in a row (horizontally, vertically, or diagonally).
6. If all spots are filled without a winner, the game ends in a draw.

## Code Explanation
- `sum(a, b, c)`: A helper function to sum three values.
- `printBoard(xState, zState)`: Displays the current state of the Tic Tac Toe board.
- `checkWin(xState, zState)`: Checks if there is a winning combination.
- The main game loop alternates turns between players until a winner is found or the game ends in a draw.

## Running the Game
### Prerequisites
Ensure you have Python installed on your system. You can check by running:
```
python --version
```

### Execution
To start the game, run the following command in your terminal:
```
python tic_tac_toe.py
```

## Example Gameplay
```
Welcome to Tic Tac Toe
0 | 1 | 2
--|---|---
3 | 4 | 5
--|---|---
6 | 7 | 8
X's Chance
Please enter a value: 4
```

## Future Improvements
- Implement AI for single-player mode.
- Add a graphical interface.
- Improve input validation to prevent invalid moves.

## License
This project is open-source and free to use.
