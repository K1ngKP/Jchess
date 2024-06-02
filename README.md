# Chess Engine Web App

## Overview

This is a web-based chess engine designed using JavaScript, HTML, and CSS. The chess engine features a functional gameboard, piece movement according to the standard rules of chess, and an AI opponent powered by an alpha-beta pruning search algorithm with a depth of up to 8. The engine can evaluate up to 400,000 positions (400 KiloNodes) and supports position analysis using the FEN (Forsyth-Edwards Notation) bar.

## Features

- **Interactive Gameboard**: A visually appealing and interactive chessboard for players to make moves.
- **Chess Pieces**: All standard chess pieces (king, queen, rook, bishop, knight, and pawn) with proper movement rules.
- **Move Validation**: Ensures all moves comply with the rules of chess.
- **AI Opponent**: An intelligent opponent using an alpha-beta pruning search algorithm.
- **Depth of Search**: AI can search up to a depth of 8 moves ahead.
- **Position Evaluation**: Capable of evaluating 400 KiloNodes.
- **FEN Support**: Analyze different chess positions using the FEN bar.

## Getting Started

### Prerequisites

To run this web app, you'll need a modern web browser such as:
- Google Chrome
- Mozilla Firefox
- Safari
- Microsoft Edge

### Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/chess-engine-web-app.git
    ```

2. Navigate to the project directory:
    ```bash
    cd chess-engine-web-app
    ```

3. Open the `index.html` file in your preferred web browser:
    ```bash
    open index.html
    ```

## Usage

1. **Playing the Game**:
    - Open the web app in your browser.
    - Use the mouse to click and drag pieces to make your moves.
    - The AI will automatically make its move after you complete yours.

2. **Analyzing Positions**:
    - Enter a FEN string in the FEN bar and press "Analyze" to load and analyze the position.
    - The AI will evaluate the position based on the current depth setting.

## Customization

### Adjusting AI Depth

To adjust the AI search depth, modify the `maxDepth` variable in the `script.js` file:
```javascript
const maxDepth = 8; // Change this value to adjust the depth
