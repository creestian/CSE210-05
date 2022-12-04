# CSE210-05
# Cycle
## Overview
Cycle is a game where the players try to cut each other off using cycles that leave a trail behind them.

## Rules
It's a two player game
Cycle is played according to the following rules.
```
1. Players can move up, down, left and right.
  a. Player one moves using the W, S, A and D keys.
  b. Player two moves using the I, K, J and L keys.
2. Each player's trail grows as they move.
3. Players try to maneuver so the opponent collides with their trail.
4. If a player collides with their opponent's trail.
  a. A "game over" message is displayed in the middle of the screen.
  b. The cycles turn white.
  c. _Players keep moving and turning but don't run into each other.
```
## Getting Started
---
Make sure you have Python 3.8.0 or newer and Raylib Python CFFI 3.7 installed and running on your machine. You can install Raylib Python CFFI by opening a terminal and running the following command.
```
pip install raylib
```
After you've installed the required libraries, open a terminal and browse to the project's root folder. Start the program by running the following command.```

python cycle
```
You can also run the program from an IDE like Visual Studio Code. Start your IDE and open the 
project folder. Select the main module inside the hunter folder and click the "run" icon.

## Project Structure
---
The project files and folders are organized as follows:
```
root                    (project root folder)
+-- cycle               (source code for game)
  +-- game              (specific game classes)
  +-- __main__.py       (entry point for program)
+-- README.md           (general info)
```

## Required Technologies
---
* Python 3.8.0
* Raylib Python CFFI 3.7

## Authors
---
* Cristian Navia (creestian@byui.edu)