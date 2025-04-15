# Catman

**Catman** is a Java-based arcade game inspired by the classic Pac-Man, developed as an early project for the *Programming 3* laboratory. In this version, you play as a cat navigating a maze, collecting points while avoiding randomly moving mice.

## Game Concept

- The player controls **Catman** (a cat character).
- Instead of ghosts, the enemies are **mice**.
- Mice move randomly around the map — no AI or pathfinding is implemented.
- The objective is to collect all the items (e.g., food or tokens) without being caught by a mouse.

## Features

- Simple 2D grid-based movement
- Randomized enemy (mouse) behavior
- Game over and win conditions
- Basic scoring system
- Classic maze-style gameplay
- Power-ups (like temporary invincibility)

## Technologies Used

- Java SE (Standard Edition)
- Java Swing or AWT for GUI (depending on your implementation)
- Object-oriented programming principles

## How to Run

1. Make sure you have Java JDK 8 or higher installed.
2. Compile the game:

   ```bash
   javac Catman.java
3. Run the game:
java Catman

## Notes
This was one of my first Java projects, focusing on understanding GUI elements, object interaction, and game loops.
No complex algorithms (like pathfinding or AI) are used for enemy movement — all movements are randomized.

## Future Ideas (Not Implemented)
- Smarter enemy behavior using algorithms like A* or BFS
- Multiple levels or increasing difficulty
- Sound effects and animations

##License
This project was created for educational purposes in the Programming 3 lab.
