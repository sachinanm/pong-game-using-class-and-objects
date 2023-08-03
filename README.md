# 🏓 Ping Pong Game 🏓

![Ping Pong Game](game_screenshot.png)

## Description

This is a simple implementation of a ping pong game using the Python Turtle graphics library. The game allows two players to control paddles and bounce a ball back and forth, earning points when the opponent misses the ball.

## 🚀 Implementation

The game is implemented in Python and uses the Turtle graphics library for the graphical user interface. The main components of the game are:

- **`Ball` Class**: Represents the ball object with movement and bouncing capabilities. It uses the `Turtle` class from the Turtle graphics library to create a circular shape representing the ball. The ball can move in both the X and Y directions and bounces off the walls and paddles when collisions occur.

- **`Paddle` Class**: Represents the paddles controlled by the players. It also uses the `Turtle` class to create rectangular shapes representing the paddles. Players can control the paddles using specific keys (e.g., 'W', 'S' for Player 1 and the arrow keys for Player 2).

- **`Scoreboard` Class**: Displays the score on the screen for both players. The scoreboard is updated whenever a player scores a point by missing the ball.

- **Game Logic**: The main game loop runs continuously until the game is exited. The loop updates the screen, moves the ball, checks for collisions with walls and paddles, and updates the scoreboard accordingly.

## 🎮 How to Play

1. Clone the repository to your local machine using Git.
