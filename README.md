# Snake Game in C++

## Overview
This is a simple *Snake Game* implemented in C++ using the console. The game features:
- A moving snake that grows when it eats food.
- Collision detection with the walls and itself.
- A scoring system with a high score tracker.
- Keyboard controls for movement.
- The ability to restart or quit the game after losing.

## Features
- *Dynamic Gameplay*: The snake moves and grows dynamically when food is eaten.
- *Score Tracking*: The game keeps track of the player's score.
- *High Score System*: Stores the highest score achieved until the game session is restarted.
- *Smooth Controls*: Uses arrow keys for movement.
- *Game Over & Restart Option*: The game ends when the snake collides with a wall or itself, and the player can choose to restart or quit.

## Controls
- *Arrow Keys*: Move the snake up, down, left, or right.
- *R Key*: Restart the game after losing.
- *Q Key*: Quit the game.

## How to Run
### Requirements
- Windows OS (since it uses windows.h for console handling)
- A C++ compiler (e.g., MinGW for Windows or Visual Studio)

### Compilation & Execution
1. *Compile the code* using g++:
   sh
   g++ snake_game.cpp -o snake_game.exe
   
2. *Run the executable*:
   sh
   ./snake_game.exe
   

## Code Structure
- SnakeGame Class: Manages game logic, movement, and rendering.
- main() Function: Controls the game loop and manages restart/quit options.
- handleInput(): Reads user input to change the snake's direction.
- updateLogic(): Updates the snake's position and handles collisions.
- draw(): Renders the game board.
- spawnFood(): Generates food at random positions.

## Future Enhancements
- Add difficulty levels with increasing speed.
- Implement a save/load feature for high scores.
- Introduce additional obstacles for more challenges.

## License
This project is open-source and free to use for educational purposes. Feel free to modify and enhance it!

---
Enjoy the game! 🐍
