# Red-Ball-Game

This is a **2D platformer game** built using **Java Swing** that mimics the style of the popular "Red Ball 4" game. You play as a red rolling ball navigating platforms, collecting power-ups, avoiding power-downs, and reaching the flag to complete levels.

# Features

- **Multiple Levels** with different platform layouts  
- **Jump, Move Left/Right**, and rotate while in air  
- **Power-Ups** to double your size and gain advantages  
- **Power-Downs** that shrink your size  
- **Collision Detection** with platforms and objects  
- **Keyboard Controls** for gameplay  
- Simple but customizable **graphics using AWT/Swing**  
- Goal flag to mark level completion  
- Game Over detection when the player falls off screen  
- Level and Game Reset logic  

# Controls

- `←` : Move Left  
- `→` : Move Right  
- `Space` : Jump  
- `Enter` : Restart the Game (after Game Over or Level Complete)

# Structure

### Main Classes

| Class        | Description |
|--------------|-------------|
| `Main3`      | Entry point of the application |
| `GamePanel`  | Main game loop, rendering, event handling |
| `Player`     | Ball logic, movement, collisions, drawing |
| `Platform`   | Static platform class |
| `MovingPlatform` | Horizontal/Vertical moving platforms |
| `PowerUp`    | Increases player size temporarily |
| `PowerDown`  | Decreases player size temporarily |
| `Vector2D`   | Simple 2D vector math for movement |

# Requirements

- Java 8 or above
- IDE or terminal with support for compiling and running Java Swing programs

# How to Run

1. Download the code file named Main
2. Compile the code and run the game
