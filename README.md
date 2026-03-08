# Pac-Man Q-Learning

> A Pygame-based Pac-Man clone where ghosts learn to hunt using Q-learning.

This is a Pac-Man clone created using Python and Pygame. It features a custom environment where the ghosts (specifically the Cyan ghost) track Pac-Man using **Reinforcement Learning** (Q-learning).

## Features

- **Classic Pac-Man Gameplay**: Navigate the maze and eat all the dots to win.
- **Q-Learning AI Ghost**: The Cyan ghost uses a Q-learning algorithm to intelligently learn how to catch Pac-Man. It calculates Manhattan distances, updates its Q-table based on rewards/penalties, and gets smarter over time.
- **Persistent Learning**: The Q-table is saved locally to `q_table.pkl` and loaded on subsequent runs, meaning the AI retains its knowledge across multiple sessions.
- **Custom Tile Map**: Built with a grid-based tile system and Pygame sprites.

## Requirements

- Python 3.x
- `pygame`

## Installation & Usage

1. **Install dependencies:**
   ```bash
   pip install pygame
   ```

2. **Run the game:**
   ```bash
   python main.py
   ```

## Controls

- **Arrow Keys**: Move Pac-Man (Up, Down, Left, Right).
- **Escape**: Quit the game.
