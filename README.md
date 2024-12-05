# 3D-Maze-Game
The 3D Maze Game has been developed as the final project of ECE243 Computer Organization course at the University of Toronto (Winter 2020).

## Project Overview
This project implements a 3D first-person maze game using the ARMv7 DE1-SoC simulator, CPUlator. The game immerses players in a maze where they navigate to find the red wall or EXIT door. The implementation demonstrates expertise in embedded systems, hardware-software integration, and interactive application design. 

It leverages key I/O devices such as:

- VGA Pixel Buffer for rendering graphics.
- PS/2 Keyboard for user input.
- Switches for additional configuration.
- Character Buffer for text output.
- ARM A9 Private Timer for managing animations and responsiveness.

The entire project was developed in C programming language, ensuring smooth performance and logical consistency within the simulated environment.

## Demo

- [3D Maze Game](https://d-uzun.wixsite.com/deniz-uzun/post/3d-maze-game)

## Features
- First-Person Perspective: Experience the maze from a first-person view for immersive gameplay.

## Keyboard Controls:
- [3D Maze Game Manual](./3D_Maze_Manual)
- SPACE: Start the game.
- Arrow Keys: Navigate (rotate, move forward/back).
- S Key: Access the settings menu.
- ESC Key: Exit the settings without changes.
- T Key: Toggle textures for the maze.
- ENTER Key: Restart the game.
- Customizable Graphics: Players can toggle maze textures on or off for smoother gameplay or enhanced visuals.
- Win Condition: Reach the red wall or EXIT door to win the game.
- Replay: Start a new game easily by pressing ENTER after winning.

## Setup Instructions
- Open the [CPUlator](https://cpulator.01xz.net/)

Configure the simulator:
- Architecture: ARMv7.
- System: ARMv7 DE1-SoC.
- Change the language to C.
- File -> Open -> Select the provided [C source file](./ECE243_project_v17).
- Compile and load the program (F5).
- Start execution by clicking Continue (F3).
- Observe the game's output on the VGA Pixel Buffer window.

## Gameplay Instructions
### Starting the Game:
- Press SPACE to start the game.

### Navigation Controls:
- Use the LEFT and RIGHT arrow keys to rotate and look around.
- Use the UP and DOWN arrow keys to move forward or backward.

### Accessing Settings:
- Press S to open the settings menu.

### In settings:
- Press T to change the maze's texture. The game will automatically continue with the updated texture.
- Press ESC to exit settings without making changes.

### Winning the Game:
- Navigate through the maze to find the red wall or the EXIT door (visible only with textures enabled).

### Restarting the Game:
- After winning, press ENTER to start a new game.

## Technical Details
- Graphics Rendering: Utilizes the VGA Pixel Buffer to dynamically render the maze and animations.
- User Input Handling: Integrated through the PS/2 Keyboard interface.
- Timer Management: The ARM A9 Private Timer ensures smooth and consistent animation updates.
- Text Output: The Character Buffer displays menu and game-related instructions.

## Tips for Gameplay
- For smoother gameplay, consider turning textures off.
- Keep track of your starting position (purple wall) to avoid confusion in the maze.
- Use the rotation keys (LEFT/RIGHT arrows) effectively to orient yourself.

## Learn More:
- [3D Maze Game](https://d-uzun.wixsite.com/deniz-uzun/post/3d-maze-game)
