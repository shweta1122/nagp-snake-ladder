# **Snakes and Ladders Game**


**Overview**
This is a Python implementation of the classic Snakes and Ladders board game. The game features a configurable board size, customizable number of players, and dynamic placement of snakes and ladders. It includes visualizations of the game board and player progress using Matplotlib and Seaborn.


**Features**

  Configurable grid size (n x n)
  Support for 2-4 players
  Customizable number and placement of snakes and ladders
  Visual representation of the game board after each turn
  Player progress tracking and visualization
  Game state saving and loading
  Detailed game history logging

**Requirements**

  Python 3.7 or higher
  Matplotlib
  Seaborn

**Installation**

  Clone this repository or download the source code.
  Install the required libraries:
  Copypip install matplotlib seaborn


**How to Play**

  Run the game by executing:
  `python main.py`
  
  Follow the prompts to set up the game:
  
  Enter the grid size (e.g., 10 for a 10x10 board)
  Specify the number of players (2-4)
  Define the number and positions of snakes and ladders
  
  
  Press Enter to roll the dice for each player's turn
  The game board will be displayed after each turn
  The game continues until a player reaches the final position
  At the end of the game, a progress chart for all players will be displayed

**Game Controls**

  Press Enter to roll the dice and make a move
  Enter 's' to save the current game state
  Enter 'q' to quit the game

**Visualizations**

Game Board: Displayed after each turn, showing the current positions of all players, snakes, and ladders.
Player Progress: A line chart showing the position of each player over time, displayed at the end of the game.

**Files**

  main.py: The main game loop and setup
  snakes_and_ladders.py: Contains the SnakesAndLadders class with game logic and visualization methods
  game_history.txt: Created at the end of each game, logging all moves made during the game.
