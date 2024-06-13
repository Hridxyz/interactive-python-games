# Memory

This repository contains a Python implementation of the classic card game Memory using SimpleGUI. The game was developed as part of my minor in Interactive Programming in Python, which is part of the "Fundamentals of Computing Specialization" by Rice University on Coursera.

## Overview

Memory is a card game in which the player deals out a set of cards face down. In each turn, the player flips over two cards. If they match, the player leaves them face up. If they don't match, the player flips the cards back face down. The goal is to end up with all of the cards flipped face up in the minimum number of turns.

## Features

- **Card Matching**: Click on cards to flip them. If they match, they stay face up; otherwise, they flip back.
- **Turns Counter**: Keeps track of the number of turns taken.
- **Reset Button**: Reshuffles the cards and resets the game.
- **Random Shuffling**: Cards are shuffled randomly at the start of each game.

## How to Play

1. **Start the Game**: Click on any card to begin. The first card will flip over.
2. **Flip Cards**: Click on another card to try and find a match. If the cards match, they remain face up; if not, they flip back over.
3. **Continue**: Keep flipping cards to find all pairs.
4. **Reset**: Click the "Reset" button to start a new game with the cards reshuffled.

## Installation

To run this project, you'll need Python and SimpleGUI installed. You can install SimpleGUI using the following command:

```sh
pip install simplegui
```

## Running the Game

1. Clone this repository:

```sh
git clone https://github.com/Hridxyz/interactive-python-games.git
```

2. Navigate to the Memory directory and run the game script:

```sh
cd interactive-python-games/Memory
python Memory.py
```

## Example Output

```plaintext
Turn: 0
[Card Back] [Card Back] [Card Back] [Card Back] [Card Back] [Card Back] [Card Back] [Card Back]
[Card Back] [Card Back] [Card Back] [Card Back] [Card Back] [Card Back] [Card Back] [Card Back]

Turn: 1
[2] [Card Back] [Card Back] [Card Back] [Card Back] [Card Back] [Card Back] [2]
```

## Acknowledgements

This game was developed as part of the "Fundamentals of Computing Specialization" by Rice University on Coursera. Special thanks to the instructors Scott Rixner, Joe Warren, and Luay Nakhleh for their guidance.