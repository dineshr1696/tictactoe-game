# Tic-Tac-Toe Game with Easy and Hard AI Modes

This is a web-based Tic-Tac-Toe game featuring two AI difficulty levels: Easy and Hard. The Easy mode makes random moves, while the Hard mode utilizes the Minimax algorithm to make optimal decisions, aiming to win or prevent the player from winning.

## Table of Contents

- [Technologies Used](#technologies-used)
- [Game Modes](#game-modes)
  - [Easy Mode](#easy-mode)
  - [Hard Mode](#hard-mode)
- [Minimax Algorithm in Hard Mode](#minimax-algorithm-in-hard-mode)
- [Features](#features)
- [How to Play](#how-to-play)
- [Future Enhancements](#future-enhancements)
- [License](#license)

## Technologies Used

- **HTML5**: Provides the structure for the game interface.
- **CSS3**: Offers styling to enhance the visual appeal of the game.
- **JavaScript (ES6)**: Implements the game logic and interactivity.

## Game Modes

### Easy Mode

In Easy mode, the AI selects its moves randomly from the available empty cells. This mode does not employ any strategic decision-making, making it easier for players to win.

### Hard Mode

In Hard mode, the AI uses the Minimax algorithm to determine its moves. This algorithm evaluates all possible game states to choose the most optimal move, either to win or to block the player from winning.

## Minimax Algorithm in Hard Mode

The Minimax algorithm is a recursive function used for decision-making in game theory and artificial intelligence. In the context of Tic-Tac-Toe, the algorithm evaluates all possible moves by simulating future game states and assigns scores based on the outcome:

- **+1**: AI wins.
- **0**: Draw.
- **-1**: Player wins.

The AI then selects the move that maximizes its chances of winning while minimizing the player's chances. This approach ensures that the AI plays optimally, making it challenging for the player to win.

For a detailed explanation of the Minimax algorithm, refer to this guide: [Tic Tac Toe: Understanding the Minimax Algorithm](https://www.neverstopbuilding.com/blog/minimax)

## Features

- **Dynamic Game Board**: A responsive 3x3 grid that updates based on player and AI moves.
- **Two AI Difficulty Levels**: Players can toggle between Easy and Hard modes using a switch.
- **Interactive UI**: Hover effects, animations, and a confetti celebration upon winning enhance the user experience.
- **Restart Functionality**: Players can restart the game at any time using the "Restart Game" button.

## How to Play

1. **Launch the Game**: Open the `index.html` file in a web browser.
2. **Select Difficulty**: Use the toggle switch to choose between Easy (green) and Hard (red) modes.
3. **Make Your Move**: Click on an empty cell to place your 'X'. The AI will respond with its move.
4. **Game Outcome**: The game continues until a player wins or the board is full, resulting in a draw.
5. **Restart**: Click the "Restart Game" button to play again.

## Future Enhancements

Consider implementing the following features to enhance the game:

- **Score Tracking**: Maintain a scoreboard to track wins, losses, and draws.
- **Multiplayer Mode**: Allow two human players to play against each other.
- **Adaptive AI**: Develop an AI that learns from the player's moves and adapts its strategy accordingly.
- **Mobile Responsiveness**: Ensure the game is fully functional and visually appealing on mobile devices.
- **Sound Effects**: Add audio feedback for moves, wins, and losses to enhance engagement.

## License

This project is licensed under the MIT License, permitting free use, modification, and distribution. For more details, refer to the LICENSE file.
