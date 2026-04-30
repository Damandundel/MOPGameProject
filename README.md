# Wizard Duel

## Overview
Wizard Duel is a browser-based 2D game built with HTML5 Canvas and JavaScript. You control a wizard, move around the arena, and fight enemies using spells and positioning.

## Features
- Real-time movement system
- Enemy AI behavior
- Spell casting / attack mechanics
- Score, lives, and game state tracking
- Canvas-based rendering loop

## Controls
- Move Up: W / Arrow Up
- Move Down: S / Arrow Down
- Move Left: A / Arrow Left
- Move Right: D / Arrow Right
- Attack / Cast Spell: Space

## Project Structure
wizard-duel/
├── index.html      (main file to run the game)
├── style.css       (styles)
├── script.js       (game logic)
├── assets/         (optional images and sounds)
└── README.md

## How to Run
1. Download or extract the project folder
2. Open index.html in a browser (Chrome or Edge recommended)
3. Play directly — no installation required

## Game Loop (How it Works)
1. Input is read from the keyboard
2. Game state updates (player, enemies, collisions)
3. Canvas is redrawn every frame

## Known Issues
- Sounds may not work if audio files are missing
- Holding movement or attack keys may cause unintended behavior
- Performance may drop with many enemies on screen

## Future Improvements
- Add finite state machine (FSM) for enemies
- Add attack cooldown system
- Improve collision detection
- Add more enemy types and difficulty scaling
- Add UI controls (HUD toggle, settings)
- Add sound system with proper loading

## Purpose
This project is useful for learning:
- HTML5 Canvas
- JavaScript game loops
- Event handling
- Basic game architecture
