# manual_neural_network
Neural network implemented in python without the use of ml packages

## Description
This project contains a number of files, a number of which are not described here.

#### bustersAgents.py
The agents implementations for pacman.

#### inference.py
Backing code that assists the pacman agents in tracking ghosts

#### busters.py
Main file to run pacman simulation

#### ghostAgents.py
Implementatin of ghost movement intelligence

#### distanceCalculator.py
Computations for distances within the mazes

#### game.py
Backing code for the game board

#### graphicsDisplay.py
Graphics implementation

#### keyboardAgents.py
Keyboard interfacing

#### layout.py
Background layout for all stored content

#### util.py
A number of utility functions for all other files.

#### test.py
Unit based tests for all implemented agents

## Executing Code
The pacman game itself can be played by running
```
python busters.py
```
The test file contains tests for all pacman agent functions, and can be run in its entirety with
```
python autograder.py -q q<number>
```
where \<number\> is a number from 1 to 6. Very specific tests can be run with the '-t' option and any test case found in the 'test_cases' folder.

## Credits
This project was completed as part of CS3600 at the Georgia Institute of Technology, and a significant portion of the code was provided by the teaching staff. All proper credit is given to the GaTech teaching staff and TAs for their portions of the presented code.
