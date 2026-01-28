# 🛸 Project: Space Invaders Arcade

## 📋 Project Overview
Create a classic Space Invaders arcade game as a single-file web application. This project serves as a technical challenge to demonstrate proficiency in Object-Oriented Programming (OOP), canvas-based rendering, and autonomous agent logic.

## 🚀 Setup & Execution
- **No Installation Required**: The entire game runs in the browser.
- **How to Run**: Simply open the `index.html` file in any modern web browser (Chrome, Firefox, Safari, Edge).
- **No Build Process**: Pure Vanilla JavaScript with zero external dependencies.

## 🛠 Technical Stack
- **Engine**: HTML5 Canvas API for 60FPS rendering.
- **Logic**: Vanilla JavaScript (ES6+ Classes).
- **Audio**: Web Audio API for real-time synthesized 8-bit sound effects.
- **Persistence**: `localStorage` API for high-score tracking and leaderboard.

## 🤖 Architecture & Agent Specifications
The game is built using an **Agent-Based Architecture**, where each entity is an independent object with its own state and logic:

### 🛰 Player Agent
- **Movement**: Horizontal movement controlled by input handlers.
- **Combat**: Tactical shooting with cooldown management.
- **States**: Supports "Rapid Fire" and "Shielded" power-up states.

### 👾 Alien Swarm (Swarm Intelligence)
- **Formation**: A grid-based movement pattern that adapts as the swarm size decreases.
- **Scaling**: Movement speed increases dynamically as fewer aliens remain on screen.

### 👹 Boss Agent (Level 5)
- **Behavior**: An autonomous high-HP entity with randomized movement and spread-fire attack patterns.

## 🎮 Game Features
- **Destructible Environment**: Bunkers with pixel-perfect collision and gradual degradation.
- **Particle System**: Real-time explosion effects for immersive feedback.
- **Dynamic Difficulty**: 5 distinct levels with increasing alien HP and aggression.
- **Leaderboard**: Local high-score system with name entry for top 5 commanders.

## ⌨️ Controls
| Key | Action |
| :--- | :--- |
| **A / D** or **Arrows** | Move Spaceship Left/Right |
| **Spacebar** | Fire Laser |
| **P** | Pause / Resume Game |
| **Enter / R** | Restart Game |

## 🛠 Developer & Debug Tools
The project includes built-in debug commands for testing agent behavior:
- `G`: Toggle **God Mode** (Invincibility).
- `L`: **Skip Level** (Instantly clear all enemies).
- `H`: **Heal** (Restore lives and grant shield).

---
*This project was developed as part of a technical study on automation and OOP principles.*