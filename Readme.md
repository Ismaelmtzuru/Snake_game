# Snake Game 🐍

Welcome to the Snake Game! This is a simple project where you will learn to create a classic game using HTML, CSS, and JavaScript. Below, I provide you with a basic description and the general functionality of the code.

## General Description 🎮

The game involves controlling a snake that moves across the screen to eat food represented by a red square. For every food the snake eats, the score increases. The goal is to avoid collisions with the walls or the snake itself.

## How to Play 🕹️

- Use the arrow keys (up, down, left, right) to control the direction of the snake.
- The snake will move in the direction indicated by the keys and eat the red food.
- Each time the snake eats, your score increases.

## Code Structure 🧩

- **Constants:** Define constant variables for canvas and snake colors.

- **Variables:** Declare variables for the snake, speed (dx, dy), and score.

- **Canvas Retrieval:** Use JavaScript to get the canvas element and its drawing context.

- **Canvas Functions:** Define functions to clear the canvas and draw snake and food parts.

- **Main Functions:**
    - `updateSnake()`: Updates the snake's position and checks if it has eaten.
    - `main()`: Main function called repeatedly to animate the game.
    - `changeDirection()`: Changes the snake's direction based on the pressed keys.

- **Food Generation and Game Over:**
    - `randomTen(min, max)`: Generates random locations for food.
    - `createFood()`: Creates new food, avoiding it appearing on the snake.
    - `gameOver()`: Checks if the game has ended due to collisions with walls or the snake itself.

## Score and Game Over 💔

- The score is displayed at the top of the game.
- The game ends if the snake collides with the walls or itself.

Have fun playing and learning to develop basic games with HTML, CSS, and JavaScript! 🚀