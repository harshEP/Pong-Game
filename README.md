# Pong Game

## Overview

This is a browser-based version of the classic Pong game. In this game, two players compete by controlling paddles on opposite sides of the screen to bounce a ball back and forth. The left paddle is controlled using the **W** (up) and **S** (down) keys, while the right paddle is controlled using the **Arrow Up** (up) and **Arrow Down** (down) keys.

## Features

- **Two-Player Gameplay:**  
  - **Left Paddle:** Move using **W** (up) and **S** (down).
  - **Right Paddle:** Move using **Arrow Up** (up) and **Arrow Down** (down).
- **Scoring System:**  
  Each time a player misses the ball, the opposing player scores a point. The current scores are displayed on the screen.
- **Randomized Ball Movement:**  
  Each round starts with a random ball speed and direction, adding variety to the gameplay.
- **Game State Management:**  
  The game starts in a "start" state and only begins when you press **Enter**. After a point is scored, the game resets and awaits a new start.

## How to Play

1. **Starting the Game:**  
   - When the game loads, press **Enter** to start the game.
   - The ball will launch with a randomized speed and direction.

2. **Controls:**  
   - **Left Paddle:**  
     - Press **W** to move the paddle upward.
     - Press **S** to move the paddle downward.
   - **Right Paddle:**  
     - Press **Arrow Up** to move the paddle upward.
     - Press **Arrow Down** to move the paddle downward.

3. **Scoring:**  
   - When the ball goes past a paddle, the opposite player earns a point.
   - The game resets after a score, and you can press **Enter** to continue playing.

## Setup and Installation

1. **Clone the Repository:**

   ```bash
   git clone <repository_url>
