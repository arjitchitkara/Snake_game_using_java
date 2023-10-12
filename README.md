
# Snake Game in Java

A classic snake game implemented in Java using Swing.

## Overview

This snake game is built using Java's Swing library. The game has a snake that the player can control with arrow keys, and the goal is to eat the apple. As the snake eats the apple, its length increases, making the game more challenging.

## Classes Overview

1. **SnakeGame**: This is the main class that contains the `main` method, and it initializes the game by calling `GameFrame`.

2. **GameFrame**: Extends `JFrame` and is responsible for creating the main game window. It sets the title, default operations, and other properties of the frame.

3. **GamePanel**: Extends `JPanel` and implements `ActionListener`. This class has all the game logic, including rendering the snake, apple, checking for collisions, and handling keyboard inputs.

## How to Run

To run the game, compile all the Java classes and execute the `SnakeGame` class.

```bash
javac SnakeGame.java GameFrame.java GamePanel.java
java SnakeGame
```

## Game Features

- The game increases in difficulty as the snake eats more apples by increasing the snake's length.
- The game ends if the snake collides with the game window boundaries or itself.
- Score display to show how many apples the snake has eaten.
- Colorful rendering of snake's body parts.

## Controls

- **Arrow Up**: Move Up
- **Arrow Down**: Move Down
- **Arrow Left**: Move Left
- **Arrow Right**: Move Right



