# SonicGame_OOP_SFML

A Sonic the Hedgehog-inspired game built using Object-Oriented Programming (OOP) principles and the SFML (Simple and Fast Multimedia Library) framework in C++.

## Description

This project is a 2D platformer game featuring Sonic the Hedgehog, implemented with a focus on OOP concepts such as inheritance, polymorphism, and encapsulation. The game includes various game objects, levels, scoring, and a leaderboard system.

## Features

- Classic Sonic gameplay mechanics
- Multiple levels and challenges
- Scoring system with leaderboard
- Audio and visual effects
- Object-oriented design

## Prerequisites

Before running this game, ensure you have the following installed:

- C++ compiler (e.g., g++)
- SFML library (version 2.5 or later)
- Linux environment (Ubuntu recommended)

### Installing SFML on Ubuntu

```bash
sudo apt-get update
sudo apt-get install libsfml-dev
```

## Compilation and Running

### Step-by-step compilation:

1. Compile the source code:
   ```bash
   g++ -c sonic/main.cpp
   ```

2. Link the object file with SFML libraries:
   ```bash
   g++ main.o -o main -lsfml-graphics -lsfml-audio -lsfml-window -lsfml-system
   ```

3. Run the game:
   ```bash
   ./main
   ```

### One-line command for compilation and running:

```bash
g++ sonic/main.cpp -o main -lsfml-graphics -lsfml-audio -lsfml-window -lsfml-system && ./main
```

## Game Controls

- **Arrow Keys**: Move Sonic left/right, jump
- **Spacebar**: Jump (alternative)
- Other controls may be specified in-game

## Project Structure

```
SonicGame_OOP_SFML/
├── README.md
└── sonic/
    ├── main.cpp
    ├── leaderBoard.txt
    ├── audio/
    ├── fonts/
    └── images/
```

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is open source and available under the [MIT License](LICENSE).

## Acknowledgments

- Inspired by Sonic the Hedgehog by SEGA
- Built using SFML library
