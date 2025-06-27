# Rock, Paper, Scissors Game

A simple command-line implementation of the classic **Rock, Paper, Scissors** game written in Python. This game allows two players to input their moves and determines the winner based on standard game rules.

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Prerequisites](#prerequisites)
- [How to Run](#how-to-run)
- [Game Rules](#game-rules)
- [Notes](#notes)
- [Contributing](#contributing)
- [License](#license)

## Overview
This project is a Python script that simulates a two-player Rock, Paper, Scissors game. Players input their moves via the command line, and the program evaluates the inputs to declare a winner or a tie. The code includes basic error handling for invalid inputs.

## Features
- Two-player gameplay via command-line inputs.
- Supports standard Rock, Paper, Scissors rules.
- Displays valid move options if an invalid move is entered.
- Simple and beginner-friendly code structure.

## Prerequisites
To run this game, you need:
- **Python 3.x** installed on your system. You can download it from [python.org](https://www.python.org/downloads/).
- A terminal or command-line interface to execute the script.

## How to Run
1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name
   ```

2. **Run the script**:
   ```bash
   python rock_paper_scissors.py
   ```

3. **Play the game**:
   - When prompted, each player should enter one of the following moves: `rock`, `paper`, or `scissors`.
   - The program will display the result (e.g., "player_one wins", "player_two wins", or "equal").
   - If an invalid move is entered, the program will show the valid move options.

## Game Rules
- **Rock** beats **Scissors** (Rock crushes Scissors).
- **Paper** beats **Rock** (Paper covers Rock).
- **Scissors** beats **Paper** (Scissors cuts Paper).
- If both players choose the same move, the result is a tie ("equal").

## Notes
- There is a typo in the original code where "scissors" is written as "seccers". For clarity, consider updating the code to use the correct spelling (`scissors`).
- The game currently does not loop to allow multiple rounds. You can enhance it by adding a loop to replay the game.
- Error handling is basic. For a more robust version, consider adding input validation to ensure case-insensitive inputs (e.g., accepting "ROCK" or "rock").

## Contributing
Contributions are welcome! If you'd like to improve the game, please:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes and commit them (`git commit -m "Add feature"`).
4. Push to your branch (`git push origin feature-branch`).
5. Create a Pull Request on GitHub.
