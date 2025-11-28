# 🚀 System Defender: Space Shooter (C++ & Raylib)

> **Group Project: C9** > A high-performance, arcade-style space shooter game built from scratch using C++ and the Raylib library. Defend the galaxy against waves of enemies and face the impossible Boss!



## 🎮 Game Overview

**System Defender** is a classic vertical scrolling shooter. The player controls a spaceship to destroy incoming enemy waves. As the levels progress, enemies become faster and harder to kill. The game features a dynamic difficulty system, a helper wingman mechanic, and an intense Boss Battle at Level 11.

## ✨ Key Features

* **🌊 Dynamic Wave System:** Enemies spawn in waves. Difficulty scales up with every level (increased speed and HP).
* **🤝 Wingman Support:** Press `H` to summon an AI Assistant Ship that doubles your firepower.
* **💀 Epic Boss Fight:** Survive until **Level 11** to face the "Impossible Boss" featuring:
    * A dedicated Health Bar.
    * Custom Laser Patterns.
    * Hit-reaction visual feedback (Explosions/Red Flash).
* **💾 Persistence:** High Score is saved locally (`savegame.dat`) and loaded on the next run.
* **💥 Visual Effects:** Particle explosion system for enemy deaths and boss damage.
* **⏯️ Game States:** Full support for Main Menu, Pause Menu, Instructions, Game Over, and Victory screens.
* **🛠️ Polished Gameplay:** * Input buffering to prevent auto-fire bugs during transitions.
    * Smooth level transitions.
    * Crash-free optimized game loop.

## 🕹️ Controls

| Key | Action |

| **⬅️ Left Arrow** | Move Ship Left |
| **➡️ Right Arrow** | Move Ship Right |
| **SPACE** | Fire Lasers |
| **H** | Toggle Wingman (Assist Ship) |



## 🛠️ Tech Stack

* **Language:** C++
* **Library:** Raylib (Graphics, Audio, Input handling)
* **IDE:** Visual Studio / VS Code

## 🚀 How to Run

1.  Ensure you have **C++** and **Raylib** installed and configured in your IDE.
2.  Clone this repository.
3.  Open the solution file.
4.  Build and Run.
5.  *Note:* Make sure the `assets` (images/sounds) are in the same directory as the executable.

## 👥 Team Members

* ABUZAR- [25L-2059]
* MUHAMMAD BURHAN - [25L-2061]
* ABDULLAH SHAH - [25L-2064]

## 📝 Version History (v1.0 Final)

* **Core Gameplay:** Implemented ship movement, shooting, and collision detection.
* **Optimization:** Fixed memory leaks and resolved critical crash issues in the main loop.
* **Balancing:** Adjusted scoring (10 pts/kill) and enemy health scaling.
* **UX Improvements:** Added cooldown timers for shooting to prevent input glitching between levels.

---
*Created for the Final Project Submission (Fall 2025).*
