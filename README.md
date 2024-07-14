# Pong Game in Python

This project is a simple implementation of the classic Pong game using Python and the `turtle` module. The game involves two paddles, a ball, and a scoreboard to keep track of the score. The objective is to score points by making the opponent miss the ball.

## Concepts Learned

### 1. Turtle Graphics
The `turtle` module in Python provides a visual way to understand the concepts of programming and graphics. In this project, the `turtle` module is used to create the paddles, ball, and scoreboard.

### 2. Object-Oriented Programming (OOP)
OOP is a programming paradigm based on the concept of "objects", which are data structures that contain data and methods. This project involves the creation of multiple classes:
- `Paddle`: Represents the paddles used to hit the ball.
- `Ball`: Represents the ball that bounces around the screen.
- `Scoreboard`: Keeps track of and displays the score.

### 3. Class Inheritance
Inheritance is a fundamental concept in OOP that allows a class to inherit properties and methods from another class. In this project, the `Paddle`, `Ball`, and `Scoreboard` classes inherit from the `Turtle` class provided by the `turtle` module.

### 4. Event Handling
Event handling is a programming concept where the program responds to events such as key presses or mouse clicks. In this game, the `screen.onkey()` method is used to bind the movement of the paddles to specific key presses.

### 5. Game Loop
The game loop is the central loop that keeps the game running. It continuously updates the game state and redraws the screen. In this project, a `while` loop is used to keep the game running, update the ball's position, and check for collisions.

### 6. Collision Detection
Collision detection is the computational problem of detecting the intersection of two or more objects. In this project, collision detection is used to determine when the ball hits a wall or a paddle.

## Code Overview

### main.py
Sets up the game screen, creates the paddles, ball, and scoreboard, and contains the main game loop.

### paddle.py
Defines the `Paddle` class with methods to move the paddle up and down.

### ball.py
Defines the `Ball` class with methods to move the ball, bounce off walls and paddles, and reset its position.

### scoreboard.py
Defines the `Scoreboard` class to keep track of and display the score.

## How to Run the Game

1. Ensure you have Python installed on your system.
2. Save the code for `main.py`, `paddle.py`, `ball.py`, and `scoreboard.py` in the same directory.
3. Run `main.py` using the command:
    ```sh
    python main.py
    ```
4. Use the 'Up' and 'Down' arrow keys to control the right paddle, and 'w' and 's' keys to control the left paddle.
