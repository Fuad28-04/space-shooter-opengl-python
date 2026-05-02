# 3D Space Shooter Game — Python & OpenGL

## Overview
A real-time 3D space combat game built with Python and PyOpenGL, featuring 
a player-controlled stealth fighter, evolving UFO enemies, dynamic asteroids, 
particle effects, and an AI helper aircraft system.

## Gameplay Features
- **Player Ship** — Stealth fighter with damage states and visual flicker effects
- **Enemy UFO** — Evolves across 5 levels with new colors, shooting styles, and increased lives
- **Asteroids** — 10 dynamic asteroids with trail particles, splitting mechanics, and solar-style rendering
- **Helper Aircraft** — Unlocks after 3 kills, auto-targets nearest asteroid
- **Shield System** — Invincible cheat mode with animated wireframe shield
- **Life Gifts** — Collectible heart pickups dropped by defeated enemies
- **Aurora Effect** — Triggered on every enemy kill with dynamic color waves
- **Camera Modes** — Toggle between third-person overview and first-person cockpit view

## Technologies Used
- Python
- PyOpenGL (OpenGL, GLUT, GLU)
- Math, Random, Time (Standard Libraries)

## Controls

| Key | Action |
|-----|--------|
| W / S | Move Forward / Backward |
| A / D | Move Left / Right |
| Q / E | Diagonal Forward |
| Z / C | Diagonal Backward |
| Left Click | Fire Bullet |
| Right Click | Toggle Camera Mode |
| Arrow Keys | Move Camera |
| SPACE | Pause / Resume |
| I | Toggle Invincible (Cheat) Mode |
| R | Restart (after Game Over) |

## Game Mechanics
- Shoot the UFO enemy to reduce its lives — it respawns stronger each time
- Miss more than 100 bullets → Game Over
- Lose all 9 lives → Game Over
- Collect heart pickups to regain lives
- Kill 3 enemies to unlock the helper aircraft

## Installation & Run

```bash
pip install PyOpenGL PyOpenGL_accelerate
python project_17.py
```

## Project Context
Personal / Academic Project — Developed using Python and OpenGL graphics pipeline
