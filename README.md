# Snake Game

A simple console-based Snake game written in C++.

---

## Table of Contents

1. [About](#about)  
2. [Features](#features)  
3. [Requirements](#requirements)  
4. [Installation & Build Instructions](#installation--build-instructions)  
5. [How to Play](#how-to-play)  
6. [File Structure](#file-structure)  
7. [Future Improvements](#future-improvements)  
8. [Contributing](#contributing)  
9. [License](#license)  

---

## About

This is a C++ implementation of the classic Snake game.  
The objective is to control a snake so that it moves around a bounded play-area, eating food items which make it grow.  
The player must avoid collisions with the walls or the snake’s own body.  
The game increases in difficulty as the snake gets longer.

---

## Features

- Basic gameplay: snake moves in four directions (up/down/left/right)  
- Growing mechanics: the snake grows in length each time it eats food  
- Game over conditions: collision with boundary/walls or the snake itself  
- Console (text/terminal) interface  
- Simple, self-contained code (no heavy dependencies)

---

## Requirements

- C++ compiler (C++11 or newer)  
- Operating system: Windows, Linux, or macOS  
- Terminal/console that supports input handling  

---

## Installation & Build Instructions

1. **Clone the repository**

    ```bash
    git clone https://github.com/lokeshkumar80/Snake_Game.git
    cd Snake_Game
    ```

2. **Compile**

    On Linux/macOS (g++):
    ```bash
    g++ Snake_Game.cpp -o snake_game
    ```

    On Windows (MinGW):
    ```bash
    g++ Snake_Game.cpp -o snake_game.exe
    ```

3. **Run**

    ```bash
    ./snake_game
    ```
    or
    ```powershell
    snake_game.exe
    ```

---

## How to Play

- Use **arrow keys** (or **WASD** if implemented) to control movement  
- Eat the food (`*`) to grow longer  
- Avoid hitting walls or colliding with yourself  
- Goal: achieve the highest possible score  

---

## File Structure
Snake_Game/
- ├── Snake_Game.cpp # Main source code
- ├── Snake_Game.exe # Windows executable (if included)
- ├── Snake_Game.code-workspace # VS Code workspace config
- └── README.md # Project documentation


---

## Future Improvements

- Add scoring & high-score persistence  
- Difficulty levels (speed increases over time)  
- Pause/Resume functionality  
- Restart without quitting  
- Improved UI/graphics (e.g. using a graphics library)  
- Cross-platform refinements  

---

## Contributing

1. Fork this repository  
2. Create your feature branch (`git checkout -b feature/Name`)  
3. Commit your changes (`git commit -m "Add new feature"`)  
4. Push to the branch (`git push origin feature/Name`)  
5. Open a Pull Request  

---

## License

This project is licensed under the **MIT License**.  
You are free to use, modify, and distribute this software with proper attribution.



