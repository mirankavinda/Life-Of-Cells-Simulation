# Life Of Cells - Simulation (Conway's Game of Life)

This is a simple implementation of Conway's Game of Life using the pygame library in Python.

![Game of Life Demo](game_of_life_demo.gif)

## Description

Conway's Game of Life is a cellular automaton devised by mathematician John Conway. It is a zero-player game, meaning its evolution is determined by its initial state, with no further input required. The game consists of a grid of cells, each of which can be either alive or dead. The game evolves in steps based on a set of rules:

- Any live cell with fewer than two live neighbors dies (underpopulation).
- Any live cell with two or three live neighbors survives.
- Any live cell with more than three live neighbors dies (overpopulation).
- Any dead cell with exactly three live neighbors becomes a live cell (reproduction).

## Features

- Click on cells to toggle their state between alive and dead.
- Press the spacebar to start or pause the simulation.
- Press 'c' to clear the grid and reset it to a random initial state.
- Press 'g' to generate a random pattern of living cells on the grid.

## Requirements

- Python 3.x
- Pygame library

## Usage

1. Clone this repository to your local machine:

   ```shell
   git clone https://github.com/mirankavinda/Life-Of-Cells-Simulation.git

2. Navigate to the project directory:
   `cd game-of-life`

3. Install the required dependencies (Pygame):
   ``pip install pygame``

4. Run the simulation:
   `python life-of-cells.py

## Controls

-`Left Mouse Button`: Toggle the state of individual cells (alive/dead).
-`Spacebar`: Start or pause the simulation.
-`c` Key: Clear the grid and reset it to a random initial state.
-`g` Key: Generate a random pattern of living cells on the grid.

## Credits
-The Game of Life rules were devised by John Conway.
-Special thanks to TechwiTim for their tutorial on John Conway's Game of Life using Python and Pygame, which served as an inspiration for this project.



