# SUIII RUNNER: A Pygame Adventure

"SUIII RUNNER" is a thrilling, side-scrolling game that takes you on an exciting journey with the football superstar, Ronaldo. The game is built using the Pygame library and offers an engaging gameplay experience that's similar to the popular Google Dino Game. 

## Game Overview

In "SUIII RUNNER", you control Ronaldo, who must jump over incoming defenders to keep running. The game starts with a terminal menu where you can choose to play the game, view the high score, view your scores, or exit the game. Once you choose to play, a new window opens up with a scrolling background and the game begins.

## Gameplay Mechanics

The gameplay mechanics are simple yet addictive. You control Ronaldo using the spacebar key to make him jump over defenders. The game features a collision detection mechanism that ends the game if Ronaldo collides with a defender. The longer you can keep Ronaldo running without colliding into a defender, the higher your score!

## Features

- **Username Input**: At the start of the game, players are asked to input their username.
- **Menu**: The game provides a menu with options to play the game, view high scores, view personal scores, or exit.
- **High Scores**: The game keeps track of high scores using a CSV file. It reads from this file to display high scores.
- **Personal Scores**: The game also tracks personal scores for each user. It reads from the CSV file to display these scores.
- **Game Over Screen**: When the player loses, a game over screen is displayed with their score and a countdown timer before the game exits.
- **Background Music (BGM)**: The game features background music that changes depending on whether you're in the menu or playing the game.

## Code Structure

The code is structured into one main script. It starts by importing necessary libraries and initializing Pygame. It then defines several functions for different parts of the game such as displaying scores, handling events, scrolling the background, and detecting collisions.

## Libraries Used

"SUIII RUNNER" utilizes several Python libraries:
- `pygame` for creating the game window, handling events, and rendering graphics.
- `csv` for reading and writing to CSV files for score tracking.
- `math` for mathematical functions used in collision detection.
- `random` for generating random values used in defender positioning.
- `os` for interacting with the operating system.
- `time` for tracking time.

"SUIII RUNNER" is an exciting and engaging Python-based game that offers hours of fun. Whether you're a fan of Ronaldo or just love good side-scrolling games, "SUIII RUNNER" is sure to keep you entertained! So why wait? Start running with Ronaldo today! :)
