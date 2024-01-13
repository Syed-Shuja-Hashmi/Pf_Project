# Pf_Project
# Flappy Bird in C++

This is a recreation of the popular mobile game Flappy Bird in C++. The game features ASCII graphics and simple gameplay mechanics, where the player controls a bird that must navigate through a series of pipes without colliding with them or the ground.

## Prerequisites

To run this game, you will need a C++ compiler and a Windows operating system.

## Code Overview

The code is organized into several functions, each responsible for a specific aspect of the game.

### `main` Function

The `main` function is the entry point of the program. It initializes the game, loads the high score from a file, and displays the main menu. The user can choose to play the game, view the help screen, view the credits, or quit the game.

### `game` Function

The `game` function is the main game loop. It initializes the game screen, sets up the bird and pipes, and handles user input. The game loop continues until the bird collides with a pipe or the ground, or the user quits the game.

### `screen` Function

The `screen` function displays the current state of the game to the console. It draws the game screen, the bird, the pipes, and the score.

### `pipes` Function

The `pipes` function generates and moves the pipes. It randomly generates the position of the pipes and moves them towards the left side of the screen. If a pipe moves off the screen, it is removed and a new pipe is generated.

### `bird` Function

The `bird` function controls the movement of the bird. It handles user input and moves the bird up or down accordingly. The bird can only move up a certain distance before it starts falling due to gravity.

### `checkscore` Function

The `checkscore` function checks if the bird has passed through a pipe. If the bird passes through a pipe, the score is incremented.

### `gameover` Function

The `gameover` function checks if the bird has collided with a pipe or the ground. If the bird collides with an obstacle, the game ends and the final score is displayed.

### `endgame` Function

The `endgame` function displays the game over screen and the final score. It also allows the user to return to the main menu.

### `menu` Function

The `menu` function displays the main menu of the game. The user can choose to play the game

