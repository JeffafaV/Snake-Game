# Snake-Game
Excuse all the comments in the code, I treated this project as notes for my reference. This is a simple Snake game made with Python and Pygame. The objective of the game is to collect as much fruit as you can without colliding with yourself or going out of bounds. This implementation focuses on limiting and queueing user input to avoid any buggy movement such as colliding with one self where it shouldn't be possible (user was able to make the snake go left when they're moving right if they press keys fast enough without limiting and queueing input). Also, I implemented the snake's movement to be time dependant (delta time) rather than frame dependant so that the snake's movement speed is consistent no matter the frames per second of a machine. To run the code, follow these steps:

1. Download Python (this project uses Python version 3.12.3).
2. Download Pygame (this project uses Pygame version 2.5.2). Note that if you have multiple versions of Python, make sure that Pygame is being integrated to the correct Python version.
3. Download Visual Studio Code.
4. Download the Python extension by Microsoft in Visual Studio Code.
5. Select your Python interpreter in Visual Studio Code through the command pallete and you should be able to run the code in Visual Studio Code now.

## Future Features and Optimizations
I plan to implement a food counter so that the user can keep track of the score. I also plan to optimize and fix the code for the queueing since it is a bit messy.