# Rock-Paper-Scissors-Lizard-Spock

This repository contains a Python implementation of the game Rock-Paper-Scissors-Lizard-Spock. The game was developed as part of my minor in Interactive Programming in Python, which is part of the "Fundamentals of Computing Specialization" by Rice University on Coursera.

## Overview

Rock-Paper-Scissors-Lizard-Spock is an expanded version of the classic Rock-Paper-Scissors game, which reduces the probability of a tie. Each player chooses one of five options, and the winner is determined using the following rules:

- Rock crushes Scissors
- Scissors cuts Paper
- Paper covers Rock
- Rock crushes Lizard
- Lizard poisons Spock
- Spock smashes Scissors
- Scissors decapitates Lizard
- Lizard eats Paper
- Paper disproves Spock
- Spock vaporizes Rock

## Features

- **Random Computer Choice**: The computer makes a random choice each round.
- **Player vs Computer**: Simulate a round of Rock-Paper-Scissors-Lizard-Spock against the computer.
- **Determines Winner**: Automatically determines and prints the winner of each round.

## How to Play

1. **Choose an Option**: The player selects one of "rock", "paper", "scissors", "lizard", or "Spock".
2. **Computer Chooses**: The computer randomly selects one of the five options.
3. **Determine Winner**: The program compares the player's choice with the computer's choice and prints the result.

## Installation

To run this project, you'll need Python installed. Additionally, make sure you have the `random` module, which is included in Python's standard library.

## Running the Game

1. Clone this repository:

```sh
git clone https://github.com/Hridxyz/interactive-python-games.git
```

2. Navigate to the RockPaperScissorsLizardSpock directory and run the game script:

```sh
cd interactive-python-games/RockPaperScissorsLizardSpock
python RockPaperScissorsLizardSpock.py
```

## Example Output

```plaintext
Player chooses rock
Computer chooses scissors
Player wins!

Player chooses Spock
Computer chooses lizard
Computer wins!

Player chooses paper
Computer chooses rock
Player wins!
```

## Acknowledgements

This game was developed as part of the "Fundamentals of Computing Specialization" by Rice University on Coursera. Special thanks to the instructors Scott Rixner, Joe Warren, and Luay Nakhleh for their guidance.
