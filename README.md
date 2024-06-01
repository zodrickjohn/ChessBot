![ChessBot Z](https://github.com/zodrickjohn/ChessBot-Z/blob/main/Screenshot%20(287).png)

## How It Works

ChessBot Z utilizes a client-server architecture, with the frontend handling user interaction and the backend managing game logic and AI evaluation. Upon making a move, the frontend sends the current game state to the Flask server, which utilizes python-chess to evaluate potential moves using advanced algorithms. The best move is then sent back to the frontend, updating the board state for continued gameplay.

## Features

- **Interactive Gameplay:** Enjoy intuitive drag-and-drop functionality for making moves on a visually stunning chessboard.
- **Real-time AI Opponent:** Challenge yourself against an AI opponent that evaluates and responds with optimal moves, providing a stimulating gameplay experience.
- **Game Notation:** Track game progress with standard chess notation format, enhancing your understanding and analysis of each move.
- **Customizable Difficulty:** Adjust the AI's analysis depth to tailor the game's challenge level to your skill and preference.
