# Maze Solver with A* Algorithm and Pygame

## Overview

This project is a Maze Solver implemented in Python using the A* algorithm and the Pygame library. It allows users to draw and customize mazes, solve them, and save/load them. The primary goal is to find the shortest path from the start position to the goal position within the maze.

## Project Structure

The project consists of the following files:

- `main.py`: The main program that runs the Maze Solver with the graphical user interface (GUI).
- `helper.py`: This module (not included in the provided code snippet) likely contains functions related to the A* algorithm and pathfinding.
- `patterns/default.txt`: This text file stores the default maze pattern, which can be loaded by the application.
- `patterns/save.txt`: This text file is used to save and load custom mazes.

## Color Definitions

The project uses RGB color values to represent different elements within the maze:

- `black`: Background color
- `white`: Empty squares
- `gray`: Wall squares
- `green`: Start position
- `red`: Goal position
- `blue`: Path squares (used to display the solution path)
- `path`: Color for path squares
- `drawMode`: Color for indicating the selected draw mode in the menu

## Functionality

### Drawing Mode

- Press 'Q' to cycle through different drawing modes: None, Wall, Empty, Start, and Goal.
- The selected drawing mode is displayed in the GUI.

### Maze Editing

- Click on the grid to draw walls, empty spaces, start, or goal positions based on the selected drawing mode.
- Walls block the path, while empty spaces are traversable.
- Start and goal positions are used for finding the path.

### Controls

- Press 'C' to clear the entire maze.
- Press 'Enter' to solve the maze using the A* algorithm and display the solution path in blue.
- Press 'S' to save the current maze to the "patterns/save.txt" file.
- Press 'L' to load a saved maze from the "patterns/save.txt" file.

### GUI Display

- The maze is displayed using rectangles with colors representing the various elements.
- The GUI also shows the current drawing mode and provides control instructions.

## Dependencies

This project depends on the following libraries:

- `pygame`: Used for creating the graphical user interface and handling user interactions.

## Usage

1. Make sure you have Python installed on your system.
2. Install the required dependencies using `pip install pygame`.
3. Run the `main.py` script to start the Maze Solver application.
4. Follow the on-screen instructions to draw, edit, save, and solve mazes.

## Future Improvements

- Provide a way for users to create custom maze patterns from scratch.
- Implement additional pathfinding algorithms.
- Improve the user interface and add more features for maze customization.
