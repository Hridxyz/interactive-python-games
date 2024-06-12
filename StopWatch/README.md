# Stopwatch: The Game

This repository contains a Python implementation of a digital stopwatch game using SimpleGUI. The game was developed as part of my minor in Interactive Programming in Python, which is part of the "Fundamentals of Computing Specialization" by Rice University on Coursera.

## Overview

"Stopwatch: The Game" combines text drawing on the canvas with timers to build a simple digital stopwatch that keeps track of time in tenths of a second. The stopwatch includes "Start", "Stop", and "Reset" buttons and tracks the player's ability to stop the timer on whole seconds.

## Features

- **Start**: Start the stopwatch.
- **Stop**: Stop the stopwatch and check if it was stopped on a whole second.
- **Reset**: Reset the stopwatch and the score counters.
- **Time Display**: Shows the elapsed time formatted as A:BC.D.
- **Score Tracking**: Tracks the number of successful stops on whole seconds and the total number of stops.

## How to Play

1. **Start**: Click the "Start" button to begin the timer.
2. **Stop**: Click the "Stop" button to stop the timer. If the timer stops on a whole second, you score a successful stop.
3. **Reset**: Click the "Reset" button to reset the timer and the score counters.

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

2. Navigate to the Stopwatch directory and run the game script:

```sh
cd interactive-python-games/Stopwatch
python StopWatch.py
```

## Example Output

```plaintext
0:00.0
Score: 0/0

[Start] [Stop] [Reset]

Elapsed Time: 0:23.5
Score: 2/5
```

## Acknowledgements

This game was developed as part of the "Fundamentals of Computing Specialization" by Rice University on Coursera. Special thanks to the instructors Scott Rixner, Joe Warren, and Luay Nakhleh for their guidance.