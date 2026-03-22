# Tic-tac-toe Project 9

**Bar Pariente, Barbara Aberzon**

## 1. The Idea

The Tic Tac Toe game, developed in Jack, offers a classic two-player gaming experience with modern enhancements. Players take turns placing their symbols ('X' or 'O') on a dynamic 3x3 grid, designed with bold visuals and seamless keyboard integration. The game incorporates features like win or tie detection, real-time feedback, and the ability to restart or quit after each round, providing an engaging and polished user experience.

## 2. Motivation

We chose to build a Tic Tac Toe game because it is a timeless, interactive game that fosters competition and collaboration between two players. Our goal was to create a project that blends logical gameplay with visually appealing graphics, offering a fun and engaging experience. This project also allowed us to explore both strategic thinking and creative design. Inspired by the nostalgia of playing Tic Tac Toe as kids, we wanted to recreate that joy while enhancing it with modern programming concepts and features.

## 3. Architecture

We have built 3 classes to support our game.

- **Main.jack**: The Main class serves as the entry point for the Tic Tac Toe game and manages the overall game flow. It begins by initializing the game environment, displaying instructions, and prompting the player to start. Once a key is pressed, the screen is cleared, and the game board is drawn. The class then enters the main game loop, which alternates between players and continuously checks for a winner or a tie. Using the TicTacToe class to handle game logic and rendering, the Main class ensures a seamless experience.

- **TicTacToe.jack**: Manages the 3x3 board (stored as a 9-element array), cursor movement, player switching, win checking (rows, columns, and diagonals), tie detection, and game reset.

- **Graphic.jack**: Drawing utilities — renders X (two diagonal lines) and O (filled circle with a smaller white circle inside) on the screen.

## Demo

[Watch the demo video](https://drive.google.com/file/d/1R1LLIOXs60itqFcV0pLOWUWPV_FONgQS/view)

## How to Play

1. Launch the program — a welcome screen will appear.
2. Press **Enter** to start. X plays first.
3. Use the **arrow keys** to move the cursor around the board.
4. Press **Enter** to place your mark on the selected cell.
5. The first player to get 3 in a row (horizontally, vertically, or diagonally) wins.
6. If the board fills up with no winner, the game announces a tie.
7. Press **any key** to restart after a win or tie.

## Controls

| Key        | Action       |
|------------|--------------|
| Arrow keys | Move cursor  |
| Enter      | Place mark   |
| Any key    | Restart game |
