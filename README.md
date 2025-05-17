# Tetris-CPP

A modern implementation of the classic Tetris game built with C++ and SFML.


## Project Description

Tetris-CPP is a feature-complete clone of the classic Tetris game. It offers smooth gameplay, vibrant graphics, and intuitive controls using the Simple and Fast Multimedia Library (SFML).

## Features

- Classic Tetris gameplay mechanics
- Smooth block movements and rotations
- Score tracking system
- Increasing difficulty levels
- Game over detection
- Preview of upcoming tetromino

## Prerequisites

To build and run this project, you will need:

- A modern C++ compiler (C++11 or newer)
- SFML library (version 2.4.2 or newer)
- CMake (version 3.10 or newer) for building

## Installation

### Linux

```bash
# Install SFML dependencies
sudo apt-get install libsfml-dev

# Clone the repository
git clone https://github.com/hoainam1401/Tetris-CPP.git
cd Tetris-CPP

# Build the project
mkdir build && cd build
cmake ..
make

# Run the game
./tetris
```

### Windows

1. Install SFML from https://www.sfml-dev.org/download.php
2. Clone this repository
3. Set up your preferred IDE with SFML
4. Build and run the project

## Controls

- **Left/Right Arrow Keys**: Move tetromino horizontally
- **Down Arrow Key**: Accelerate drop
- **Up Arrow Key**: Rotate tetromino
- **Space**: Hard drop
- **P**: Pause game
- **Esc**: Exit game

## Code Structure

- `src/` - Contains all source files
- `include/` - Header files
- `resources/` - Game assets like fonts and textures

