# Game of Life - Pygame Replica

This project is a replica of the renowned **John Conway's Game of Life** using Python's Pygame library. Immerse yourself in this cellular automaton simulation and witness the mesmerizing patterns it can produce!

![Screenshot of the Game](https://raw.githubusercontent.com/TishaMazumdar/game-of-life/main/screenshots/ss1.jpeg)
![Screenshot of the Game](https://raw.githubusercontent.com/TishaMazumdar/game-of-life/main/screenshots/ss2.jpeg)

## Table of Contents

- Introduction
- Rules
- Controls
- Installation
- Usage
- Contributing

## Introduction

The Game of Life, created by mathematician John Conway, is a zero-player game, meaning that its progression is dictated by its initial state, with no further input from humans. This game is a representation of cellular automaton where cells on a grid evolve through a set of rules.

## Rules

The universe of the Game of Life is an infinite two-dimensional orthogonal grid of square cells, each of which is in one of two possible states, alive or dead. Every cell interacts with its eight neighbors, which are the cells horizontally, vertically, or diagonally adjacent. At each step in time, the following transitions occur:

1. **Birth**: A dead cell with exactly 3 live neighbors becomes a live cell.
2. **Survival**: A live cell with 2 or 3 live neighbors remains alive, otherwise, it dies.
3. **Death**:
   - **Overpopulation**: A live cell with more than 3 live neighbors dies.
   - **Loneliness**: A live cell with fewer than 2 live neighbors dies.

## Controls

- **Space**: Pause/Resume the game.
- **G**: Random allocation of live cells on the grid.
- **C**: Clear the screen, making all cells dead.
- **Click (Mouse)**: Toggle a cell's state. Clicking a live cell will make it dead and vice versa.

## Installation

1. Ensure you have [Python](https://www.python.org/downloads/) and [Pygame](https://www.pygame.org/download.shtml) installed.
2. Clone the repository:
    ```bash
    git clone https://github.com/TishaMazumdar/game-of-life.git
    ```
3. Navigate to the project directory:
    ```bash
    cd game-of-life
    ```

## Usage

1. Run the game using the command:
    ```bash
    python main.py
    ```

## Contributing

If you'd like to contribute, please fork the repository and create a new branch, then submit a pull request.

1. Fork the repository.
2. Create a new branch: `git checkout -b new-feature`
3. Make your changes and commit: `git commit -am 'Add some feature'`
4. Push to your branch: `git push origin new-feature`
5. Submit a pull request.
