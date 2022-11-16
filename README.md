# Blocc
A mediocre Block game
## Original idea
This is one dumb block game that was inspired by [Tetris](https://en.wikipedia.org/wiki/Tetris) and [Tetris Attack](https://en.wikipedia.org/wiki/Tetris_Attack). Implemented in [Python](https://www.python.org/) using Pygame along with Numpy, with a sole aim to deliver a lightweight and hassle-free experience for the average end user
## Installation
The game is configured to work with both Python 2 and 3 with extensive support for Windows, Linux and macOS. To install the game, clone the repository and run the following command to install the dependencies:
```
pip install -r requirements.txt
``` 
## Running the actual game
To run the game, simply run the following command:
```
python run_game.py
``` 
Disclaimer: While the game is fully functional, it is still in its early stages of development. There are still a lot of bugs and glitches that need to be fixed.
## EXE compilation
With the game being written in pure python, you can instead convert the game into an executable file using PyInstaller. To do so, run the following command:
```
pyinstaller --onefile --windowed run_game.py
```
In addition you can also use --target-architecture x86-64 to further specify the architecture of the executable file. This will create a single executable file in the dist folder. You can then run the game by simply double clicking on the executable file. 
``` 
pyinstaller --onefile --windowed --target-architecture x86-64 run_game.py
```
Reminder: You will need to install PyInstaller before you can run the above command. To install PyInstaller, run the following command:
```
pip install pyinstaller
```
## Basic controls
This is a basic game where you will try to guide one block and navigate it from other blocks that are strategically placed. The controls are simple and easy to use:
- Basic block movement are handled by mouse controls, where you can move the block by dragging it in 4 directions.
- Blocks can only move one at a time, and you can only move the block that is not obstructed by other blocks.
## How does it actually work
The game rely on the fundamental miracle work of the Pygame library + the randomness Numpy provides. Being used to the highest extend with GameController subset to handle user's input, along with some goofy ahh SFX that we have found on the internet with some 5 min GFX sketch. Create with simplicity in mind, where player can sit back and relax after a long day at work and instead of chilling you are now dealing with one of the most mind boggling game ever. The game is written in Python 2.7, and is compatible with Python 3.6, tested on python 3.11. The game is also compatible with Windows, Linux and macOS.