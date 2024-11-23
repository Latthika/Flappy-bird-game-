# Flappy Bird Game in Java

## Overview
This project implements a simple and interactive **Flappy Bird** game using Java's Swing library. The game features:
- A bird controlled by the player using the spacebar.
- Dynamic obstacles in the form of pipes.
- Scoring based on successful navigation through pipes.
- Game-over conditions when the bird collides with a pipe or goes out of bounds.
- Integrated sound effects for flapping, scoring, and game-over events.

## Features
- Graphics: The game uses custom images for the bird, pipes, and background.
- Game Mechanics:
  - Gravity affects the bird's motion.
  - Spacebar input lets the bird "flap" upwards.
  - The score increases as the player navigates past obstacles.
- Sounds: Includes sound effects for key game actions.
- Replayability: Restart the game seamlessly after a game over.

## Installation
1. Clone the Repository:
   ```bash
   git clone [https://github.com/Latthika/Flappy-bird-game-.git]
2. Compile the Code:
- Ensure you have Java Development Kit (JDK) installed.
- Compile the Java files:
  ```bash
  javac App.java FlappyBird.java
3. Run the Game:
    ```bash
    java App
## How to Play
- Objective: Control the bird to navigate through the pipes without collision.
- Controls:
  - Press the spacebar to make the bird flap and ascend.
  - Release the spacebar to let gravity pull the bird down.
- Scoring: Earn points for each successful pass through a set of pipes.
- Game Over: Occurs when:
  - The bird collides with a pipe.
  - The bird falls out of bounds.
 # Code Files
1. App.java
This file sets up the game window using Swing and initializes the main game loop.

2. FlappyBird.java
This file contains:

- Game logic: Bird movement, pipe spawning, collision detection, and scoring.
- Rendering: Draws the bird, pipes, and background.
- Sound integration: Plays sound effects for key actions like flapping and scoring.    
## Resources
- Images: Background, bird, and pipe images are stored in the /resource folder.
- Sounds: Sound effects (flap.wav, score.wav, gameover.wav) are also in the /resource folder.  
