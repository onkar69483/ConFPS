# ConFPS

**ConFPS** is a console-based 3D raycasting first-person shooter game written in C++. The game features a simple 3D environment rendered directly in the console using characters and shading to simulate depth. Players can navigate through a maze-like world with movement and rotation controls.

## Demo video

https://github.com/user-attachments/assets/42ee67ef-2ba0-462e-bdce-a0ff847535cd

## Features

- **3D Raycasting**: Uses raycasting to render walls in a 3D perspective in the console.
- **Player Controls**: Move forward, backward, and rotate left or right to explore the world.
- **Collision Detection**: Prevents players from walking through walls.
- **Console-Based Rendering**: Simulates 3D graphics within a simple text console.

## Controls

- **W** - Move Forward
- **S** - Move Backward
- **A** - Rotate Left
- **D** - Rotate Right

## Getting Started

To play the game, download and run the executable file [ConFPS.exe](./ConFPS.exe) from the root directory.

### Prerequisites

- Windows Operating System (Console-based rendering is tailored for Windows consoles)
- The game is compiled to run as an executable, so no additional software is required.

### Running the Game

1. Download **ConFPS.exe** from the root directory.
2. Open the file to start playing.

## Technical Details

The game is built using C++ and leverages Windows console functions to create a simple 3D environment. It simulates a 3D effect using raycasting, where each column of the screen represents the distance to the nearest wall. The distance is calculated using trigonometric functions based on the player's position and orientation.

Key variables:
- **fPlayerX, fPlayerY**: The player's position in the world.
- **fPlayerA**: The player's rotation angle.
- **fFOV**: Field of view, controls the extent of the player's visible area.
- **fDepth**: Controls how far the player can see.
