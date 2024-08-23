# tictactoe_java

## Overview

This is a simple command-line Tic-Tac-Toe game implemented in Java. The game allows two players to take turns marking spaces on a 3x3 grid. The first player to align three of their marks in a row, column, or diagonal wins the game. If all spaces are filled without a winner, the game ends in a draw.

## Features

- **Two-Player Mode**: Play against another player locally.
- **Simple Interface**: The game is played in the console, with easy-to-follow instructions.
- **Win and Draw Detection**: The game checks for win conditions after each move and also detects draws.

## Getting Started

### Prerequisites

- **Java Development Kit (JDK)** installed on your machine.

### Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/simran487/tictactoe_java
   cd tic-tac-toe
   ```

2. **Compile the Program**:
   ```bash
   javac TicTacToe.java
   ```

3. **Run the Program**:
   ```bash
   java TicTacToe
   ```

### How to Play

1. The game initializes with an empty 3x3 board.
2. Players take turns entering their move by specifying the row and column number.
3. The game will display the board after each move.
4. The game continues until a player wins or the board is filled, resulting in a draw.
5. The result is displayed at the end of the game.

## Code Structure

- **TicTacToe.java**: Contains all the game logic, including player moves, board display, win/draw checking, and player switching.

