# Overlord Rising

2D platformer game built with Phaser 3, developed as a team project (TP2) for university coursework.

## Features

- 3 playable levels with increasing difficulty
- Enemies and a boss encounter
- Main menu, instructions and settings screens
- Language switching (Portuguese / English)
- Volume control
- Arcade physics with gravity-based platforming
- Responsive scaling (1280x720 base resolution, fits any screen)

## Tech stack

- JavaScript (ES6 modules)
- Phaser 3 (HTML5 game framework)
- HTML5 Canvas / WebGL

## Project structure

```
Projeto Phaser/
├── assets/           # Sprites, backgrounds and audio
├── src/
│   ├── main.js       # Game configuration and entry point
│   ├── Enemy.js      # Enemy behaviour
│   ├── Tradu.js      # PT/EN translations
│   └── scenes/       # Menu, Start (level 1), Nivel2, Nivel3, Settings, Instrucoes
├── index.html
└── phaser.js         # Phaser library
```

## Running the game

Serve the `Projeto Phaser` folder with any static web server:

```bash
cd "Projeto Phaser"
python -m http.server 8000
```

Then open `http://localhost:8000` in your browser.

## Academic context

Team project developed with a classmate for a university course. The source code (comments, identifiers and some file names) is kept in Portuguese, exactly as originally submitted.

## Authors

- **Alexandre Silva** — [GitHub](https://github.com/alexandresilva-dev) · [LinkedIn](https://www.linkedin.com/in/alexandresilva-dev)
- **Daniel Pereira** — [GitHub](https://github.com/danielpereira11)
