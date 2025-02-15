# Snake Game

## Overview
This is a classic Snake Game implemented in C++ with a simple console-based interface. The game offers two difficulty modes: Easy (no border collision) and Hard (border collision enabled). The player's goal is to control the snake, eat fruits, and avoid collisions.
This project is the closest to my heart. It was the first-semester project I did with Muhammad Uzair. So many memories flood back when I read through the comments. I am not one, but I think this is how fathers feel watching their children's childhood videos. <3 :')

https://github.com/user-attachments/assets/00c93b97-5fc7-4b4d-a6ad-a27f49545227

## Features
- Two difficulty levels: **Easy** (border collision off) and **Hard** (border collision on)
- Simple **WASD** controls for movement
- **Spacebar** to pause the game
- Dynamic snake movement and growth
- Random fruit generation
- High score tracking with file storage

## Controls
- **W** - Move Up
- **A** - Move Left
- **S** - Move Down
- **D** - Move Right
- **Space** - Pause/Unpause

## How to Play
1. Run the program.
2. Choose the difficulty level (1 for Easy, 2 for Hard).
3. Use **WASD** keys to control the snake.
4. Eat fruits (@ symbol) to grow and increase score.
5. Avoid hitting the border (in Hard mode) or yourself.
6. The game ends when the snake collides with itself or the border (in Hard mode).
7. The high score is saved in a file.
8. You can restart or exit the game upon losing.

## Files Used
- **highscore for easy.txt** - Stores high score for Easy mode.
- **highscore for hard.txt** - Stores high score for Hard mode.

## Requirements
- Windows OS (uses `<Windows.h>` for Sleep function)
- C++ compiler (such as MinGW or MSVC)

## Compilation & Execution
1. Open a terminal or command prompt.
2. Navigate to the directory containing the source code.
3. Compile using:
   ```sh
   g++ snake_game.cpp -o snake_game
   ```
4. Run the executable:
   ```sh
   ./snake_game  (Linux/Mac)
   snake_game.exe  (Windows)
   ```

## Future Improvements
- I don't want this to change :')

## Credits
Coded by ** Asfand Yar & Uzair Ashfaq **

