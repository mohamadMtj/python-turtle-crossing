# python-turtle-crossing
A Turtle Crossing game built with Python using OOP, multiple modules, collision detection, and progressive difficulty.
# 🐢 Python Turtle Crossing

A classic **Turtle Crossing game** built with Python using the Turtle graphics library and Object-Oriented Programming.

The player controls a turtle and tries to cross the road while avoiding randomly generated cars. Each successful crossing increases the level and makes the game progressively more challenging.

This project was created as part of my Python learning journey to practice OOP, multiple modules, collision detection, game loops, and object management.

---

## 🎮 Features

- 🐢 Player-controlled turtle
- 🚗 Randomly generated cars
- 💥 Collision detection
- 🏁 Finish line detection
- 📈 Level progression
- ⚡ Increasing difficulty
- 🎨 Random car colors
- 🧩 Modular project structure
- 🖥️ Turtle-based graphical interface

---

## 🛠 Technologies Used

- Python 3
- Turtle Graphics
- Object-Oriented Programming (OOP)

---

## 📂 Project Structure

```text
python-turtle-crossing/
│
├── main.py
├── player.py
├── car_manager.py
├── scoreboard.py
└── README.md
```

### File Overview

| File | Description |
|------|-------------|
| `main.py` | Runs the main game loop and controls interactions between game objects |
| `player.py` | Handles player movement and finish-line detection |
| `car_manager.py` | Creates, stores, and moves cars |
| `scoreboard.py` | Displays the current level and game-over message |

---

## 🎮 Controls

| Key | Action |
|-----|--------|
| ⬆️ Up Arrow | Move the turtle forward |

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/python-turtle-crossing.git
```

### 2. Navigate to the project

```bash
cd python-turtle-crossing
```

### 3. Run the game

```bash
python main.py
```

---

## 🎯 How to Play

1. Start the game.
2. Use the **Up Arrow** key to move the turtle.
3. Avoid the cars crossing the road.
4. Reach the finish line at the top of the screen.
5. Each successful crossing increases your level.
6. Try to reach the highest level possible without getting hit.

---

## 🧠 Learning Objectives

This project helped me practice:

- Object-Oriented Programming
- Classes and Objects
- Inheritance
- Class Methods
- Python Modules
- Lists
- Loops
- Conditional Statements
- Random Number Generation
- Keyboard Events
- Collision Detection
- Game Loops
- Managing Multiple Objects
- Level Progression

---

## 🏗️ OOP Structure

The project separates different parts of the game into individual classes.

### 🐢 Player

The `Player` class inherits from `Turtle` and is responsible for:

- Creating the player
- Moving the player upward
- Returning the player to the starting position
- Checking whether the finish line has been reached

---

### 🚗 CarManager

The `CarManager` class manages all cars in the game.

It is responsible for:

- Creating cars randomly
- Assigning random colors
- Positioning cars randomly
- Storing cars in a list
- Moving cars across the screen
- Increasing the car speed when the player reaches a new level

---

### 🏆 Scoreboard

The `Scoreboard` class manages the game's level display.

It handles:

- Displaying the current level
- Increasing the level
- Updating the scoreboard
- Displaying the `GAME OVER` message

---

## 🔄 Game Loop

The main game loop continuously:

1. Updates the screen.
2. Creates cars.
3. Moves the cars.
4. Checks for collisions.
5. Checks whether the player reached the finish line.
6. Increases the level when the player successfully crosses.

---

## 📈 Level System

Every time the player reaches the finish line:

```text
Level 1
   ↓
Level 2
   ↓
Level 3
   ↓
Level 4
   ↓
...
```

The car manager increases its speed as the level increases, making the game progressively more difficult.

---

## 💡 Future Improvements

Possible improvements for future versions:

- 🚗 Increase actual car movement speed with each level
- ❤️ Add multiple lives
- 🔊 Add sound effects
- 🎵 Add background music
- 🏆 Add a high-score system
- ⏸️ Add a pause system
- 🎨 Improve the graphics
- 🚦 Add different road lanes
- 🏎️ Add different car sizes and speeds
- 🎮 Add additional controls

---

## 👨‍💻 Author

**Mohamad Mtj**

Computer Engineering Student  
Front-End Developer | Python Learner | Linux & Networking Enthusiast

---

## ⭐ Support

If you enjoyed this project, consider giving it a ⭐ on GitHub.
