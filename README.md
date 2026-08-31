# 🐦 Sky Hopper

**Sky Hopper** is a 2D arcade-style endless runner built with **Unity and C#**, inspired by classic obstacle-dodging games. The player controls a bird and must navigate through a continuous series of pipes while avoiding collisions and achieving the highest possible score.

The project focuses on implementing core game-development concepts such as **2D physics, player input, collision detection, procedural obstacle spawning, game-state management, and score tracking**.

---

## 🎮 Gameplay

The objective is simple:

> **Keep flying, avoid the pipes, and beat your high score!**

The bird moves continuously under gravity, while the player uses a single input to make the bird flap upward. Pipes are spawned and moved across the screen, creating an endless sequence of obstacles.

### Controls

| Input     | Action         |
| --------- | -------------- |
| `Space`   | Flap / Move Up |
| Collision | Game Over      |

---

## ✨ Features

* 🐦 Physics-based bird movement using Unity's `Rigidbody2D`
* 🏗️ Continuously spawned pipe obstacles
* 🔄 Moving obstacles for endless gameplay
* 💯 Real-time score tracking
* 💥 Collision-based game-over system
* 🔁 Restart game functionality
* 🎮 Simple and responsive arcade gameplay
* 🧩 Modular C# scripts for gameplay components

---

## 🛠️ Built With

* **Unity**
* **C#**
* **Unity 2D Physics**
* **Unity UI**
* **TextMesh Pro**
* **Git & GitHub**

---

## 🧠 Implementation

The game is structured into dedicated scripts for different gameplay responsibilities:

### `BirdScript.cs`

Handles the bird's core movement and interaction with the physics system.

* Reads player input
* Applies upward flap force
* Tracks whether the bird is alive
* Detects collisions and triggers game over

### `LogicScript.cs`

Manages the overall game state.

* Tracks the player's score
* Updates the score UI
* Displays the game-over screen
* Reloads the active scene when restarting

### `PipeMoveScript.cs`

Controls the movement of pipe obstacles across the game screen.

### `PipeSpawnScript.cs`

Responsible for continuously generating new pipe obstacles to maintain the endless gameplay loop.

This separation keeps gameplay systems modular and easier to maintain.

---

## 📂 Project Structure

```text
Sky-Hopper/
│
├── Assets/
│   ├── Prefabs/
│   ├── Scenes/
│   │   └── GameScreen.unity
│   ├── Scripts/
│   │   ├── BirdScript.cs
│   │   ├── LogicScript.cs
│   │   ├── PipeMiddleScript.cs
│   │   ├── PipeMoveScript.cs
│   │   └── PipeSpawnScript.cs
│   ├── Sprites/
│   └── TextMesh Pro/
│
├── Packages/
├── ProjectSettings/
└── README.md
```

---

## 🚀 Getting Started

### Prerequisites

Make sure you have:

* **Unity Hub**
* A compatible version of **Unity**
* **Git**

### Installation

Clone the repository:

```bash
git clone https://github.com/Aditya1335/Sky-Hopper.git
```

Open **Unity Hub** and select:

```text
Add → Select the cloned Sky-Hopper folder
```

Open the project and load:

```text
Assets/Scenes/GameScreen.unity
```

Press **Play** in the Unity Editor and start playing.

---

## 🎯 What I Learned

Building Sky Hopper helped me strengthen my understanding of:

* Unity's component-based architecture
* C# scripting for gameplay
* 2D physics and `Rigidbody2D`
* Collision detection
* Player input handling
* Scene management
* UI and score systems
* Prefabs and reusable game objects
* Separating gameplay logic into modular scripts

---

## 🔮 Future Improvements

Potential improvements for future versions include:

* High-score persistence
* Difficulty scaling over time
* Additional player skins
* Sound effects and background music
* Main menu and pause functionality
* Mobile touch controls
* Multiple environments and themes

---

## 📸 Screenshots

Add gameplay screenshots here:

```md
![Gameplay](path/to/gameplay-screenshot.png)
```

---

## 👨‍💻 Author

**Aditya Patel**

GitHub: [@Aditya1335](https://github.com/Aditya1335)

---

## 📄 License

This project is available for educational and personal use. See the repository for more information.

---

⭐ **If you found this project interesting, consider giving it a star!**
