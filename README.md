# Rock Paper Scissors

## Summary
This Python script is a simple implementation of the classic game "Rock Paper Scissors." The player competes against the computer by choosing either rock, paper, or scissors. The program randomly selects the computer's choice and determines the winner based on the standard rules of the game. The game supports multiple rounds and clears the terminal screen between rounds for a clean interface. The player can choose to play again or exit the game after each round.

## Features
- **User Input Handling**: The player can choose rock, paper, or scissors by entering `0`, `1`, or `2`, respectively. The program handles invalid inputs gracefully and prompts the user to enter a valid choice.
- **Computer Choice**: The computer's choice is randomly generated using the `random` module.
- **ASCII Art**: The program uses ASCII art to visually represent the choices of rock, paper, and scissors.
- **Win/Lose/Draw Logic**: The program determines the outcome of the game based on the standard rules:
  - Rock beats scissors.
  - Paper beats rock.
  - Scissors beat paper.
  - If both choices are the same, the game is a draw.
- **Replayability**: The player can choose to play again or exit the game after each round.
- **Screen Clearing**: The terminal screen is cleared between rounds to provide a clean interface for the next round.

## How to Play
1. Run the script in a Python environment.
2. Choose rock, paper, or scissors by entering `0`, `1`, or `2`, respectively.
3. The computer will randomly select its choice.
4. The program will display both choices and determine the winner based on the rules of the game.
5. After each round, you can choose to play again or exit the game.

## Requirements
- Python 3.x

## Running the Game
To run the game, simply execute the script in your Python environment:
```bash
python main.py
```
