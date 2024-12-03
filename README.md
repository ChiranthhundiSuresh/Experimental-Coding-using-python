# Python Mini-Games and Visualizations

This repository contains three Python projects:

1. Pie Chart Visualization: A program to generate a pie chart for given data.
2. Rock-Paper-Scissors: A simple game between the user and the computer.
3. Tic Tac Toe: A two-player board game.

These projects are beginner-friendly and demonstrate the use of Python programming for games and data visualization.

## Features

#### 1. Pie Chart Visualization
Description: A program that uses the Matplotlib library to create a pie chart based on user-provided data.
Features:
  Generates a pie chart with customizable labels and values.
  Displays the chart using Python's matplotlib.pyplot.

#### 2. Rock-Paper-Scissors
Description: A simple game where the user competes against the computer by choosing one of three options: Rock, Paper, or Scissors.
Features:
  The computer makes a random choice from the three options.
  Implements the game rules:
  Rock beats Scissors.
  Scissors beats Paper.
  Paper beats Rock.
Handles invalid inputs gracefully with prompts to retry.

#### 3. Tic Tac Toe
Description: A classic two-player game on a 3x3 grid where players take turns to place their marks (X or O) on the grid. The goal is to align three of their marks in a row, column, or diagonal.
Features:
  Random selection of the starting player.
  Real-time board updates.
  Automatic validation of moves to ensure proper gameplay.
  Detection for wins and draws.

## How to Run
Prerequisites:
Python 3.x installed.
For Pie Chart Visualization:
  Matplotlib installed. Run:
    pip install matplotlib

####Running the Programs:

##### 1.Pie Chart Visualization:
  Copy the Pie Chart code into a Python file (e.g., pie_chart.py).
  Run the file, and a pie chart will display.

##### Rock-Paper-Scissors:
  Copy the Rock-Paper-Scissors code into a Python file (e.g., rock_paper_scissors.py).
  Run the file and enter your choice when prompted (Rock, paper, or Scissor).

##### Tic Tac Toe:
  Copy the Tic Tac Toe code into a Python file (e.g., tic_tac_toe.py).
  Run the file and follow the on-screen prompts to play the game.
  
## Sample Outputs

#### 1. Pie Chart Visualization:
  A simple pie chart is displayed with the given data:
  a = [35, 15, 30, 20]
  value = ["Python", "Java", "C", "PHP"]

#### Rock-Paper-Scissors:
Gameplay Example:
  Welcome, please choose an option: Rock
  You chose: Rock
  Computer chose: paper
  Result: You lose! Try again.

#### Tic Tac Toe:
Initial Board:
  - - -
  - - -
  - - -
  Game Progress (Player X's Move):
  
  X - -
  - - -
  - - -
  Final Board (Player X Wins):
  
  X X X
  O O -
  - - -
  
## Customization

#### 1. Pie Chart Visualization:
  Allow user input for categories and values via the console or a file.
#### 2. Rock-Paper-Scissors:
  Include scoring to track the user's performance over multiple rounds.
#### 3. Tic Tac Toe:
  Add scoring for multiple rounds.
  Enhance with a single-player mode using a basic AI.
