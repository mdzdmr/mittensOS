# Chess Game Engine

A Python-based chess game engine with a graphical interface using Pygame. This engine includes functionalities to manage the game state, validate moves, log moves, handle AI for making moves, and provide a visual interface for playing chess. The project utilizes `numpy` for efficient array operations.

This project was inspired by Mittens, the strongest chess bot released by Chess.com.

## Features

- **Comprehensive Game State Management**: Tracks the board state, player turns, and special conditions like check, checkmate, and stalemate.
- **Move Validation**: Validates all possible moves, including special moves like castling, en passant, and pawn promotion.
- **Move Logging**: Maintains a log of all moves made during the game, enabling undo functionality.
- **AI Integration**: Uses negamax search with alpha-beta pruning to determine the best moves for the AI.
- **Graphical Interface**: Utilizes Pygame for a visual representation of the chessboard, handling user inputs and displaying the game state.
- **Efficient Array Operations**: Utilizes `numpy` for handling the chessboard as an 8x8 array for efficient computation.

## Installation

To use this chess engine, clone the repository and install the required dependencies.

```bash
git clone https://github.com/yourusername/chess-game-engine.git
cd chess-game-engine
pip install pygame 
```

## Project Structure

- `main.py`: The main driver file for handling user input and displaying the game state using Pygame.
- `ChessEngine.py`: Contains the `GameState` class that manages the current state of the chess game and the logic for making moves.
- `ChessAI.py`: Contains the AI logic for determining the best moves using negamax search with alpha-beta pruning.
- `images/`: Directory containing images for the chess pieces.

## Contributing

Contributions are welcome! Here are some ways you can contribute:

- **Report Bugs**: If you find any bugs, please open an issue describing the problem and steps to reproduce it.
- **Suggest Features**: Have an idea for a new feature? Open an issue to discuss it.
- **Submit Pull Requests**: If you want to contribute code, fork the repository, create a new branch, and submit a pull request. Please ensure your code follows the project's coding standards and includes relevant tests.


## Acknowledgements

- The Pygame library for providing an easy-to-use interface for creating games in Python.
- Eddie Sharick who guided me through this project.
- **Chess.com** for releasing Mittens, the strongest chess bot, which inspired this project.
