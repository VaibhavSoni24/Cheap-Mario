# Cheap Mario 🍄

A 2D platformer game inspired by the classic Super Mario series, built with [Godot Engine 4.4](https://godotengine.org/). Guide your knight through a level, collect coins, and avoid patrolling slime enemies!

---

## 🎮 Gameplay

- Navigate platforms to collect as many coins as possible.
- Avoid slime enemies — touching one will kill the player and restart the level.
- Your coin count is displayed on-screen and updates in real time.

---

## 🕹️ Controls

| Action     | Keys                          |
|------------|-------------------------------|
| Move Left  | `A` / `←` (Left Arrow)        |
| Move Right | `D` / `→` (Right Arrow)       |
| Jump       | `Space` / `W` / `↑` (Up Arrow)|

---

## ⚙️ How to Run

### Requirements

- [Godot Engine 4.4](https://godotengine.org/download) or later

### Steps

1. Clone this repository:
   ```bash
   git clone https://github.com/VaibhavSoni24/Cheap-Mario.git
   ```
2. Open Godot Engine and click **Import**.
3. Navigate to the cloned folder and select `project.godot`.
4. Click **Import & Edit**, then press **F5** (or the ▶ Play button) to run the game.

---

## 🗂️ Project Structure

```
Cheap-Mario/
├── assets/
│   ├── fonts/          # Pixel fonts for UI
│   ├── music/          # Background music
│   ├── sounds/         # Sound effects (coin, hurt, jump, etc.)
│   └── sprites/        # Sprite sheets (knight, slimes, coins, tiles)
├── scenes/
│   ├── game.tscn       # Main game level
│   ├── player.tscn     # Player character (knight)
│   ├── slime.tscn      # Patrolling enemy
│   ├── coin.tscn       # Collectible coin
│   ├── platform.tscn   # Moving/static platform
│   ├── kill_zone.tscn  # Death trigger area
│   └── music.tscn      # Auto-loaded background music
├── scripts/
│   ├── player.gd       # Player movement and animation
│   ├── slime.gd        # Enemy patrol logic
│   ├── coin.gd         # Coin collection and scoring
│   ├── kill_zone.gd    # Death and scene-reload logic
│   └── game_manager.gd # Score tracking and HUD updates
└── project.godot       # Godot project configuration
```

---

## ✨ Features

- Smooth character movement with run and jump animations
- Patrolling slime enemies that reverse direction at walls
- Coin collection system with live score display
- Death sequence with slow-motion effect and automatic level reload
- Pixel-art style with custom fonts and background music
- Separate audio buses for music and sound effects

---

## 📜 License

This project is open source. Feel free to use it as a learning reference or starting point for your own Godot games.
