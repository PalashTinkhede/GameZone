# 🎮 GameZone

A collection of classic browser mini-games built with plain **HTML, CSS, and JavaScript** — no frameworks, no build step. A Bootstrap-powered landing page (`index.html`) serves as the hub linking to each game.

## Games Included

### ❌⭕ Tic Tac Toe
*Folder: `tic tac toe/tic tac toe/`*

The classic two-player X vs O game.
- Click a cell to place your mark; turns alternate automatically
- Win detection across rows, columns, and diagonals with an animated strike-through line
- Sound effects on each move and on game over, plus a celebration GIF for the winner
- Reset button to start a new round

### 🐉 Dragon (Dino) Game
*Folder: `JavaScript Dragon Game/JavaScript Dragon Game/`*

A side-scrolling obstacle-dodging game where a dino must jump over an incoming dragon.
- **↑ (Up Arrow)** — jump
- **← / → (Left/Right Arrows)** — move the dino horizontally
- Score increases each time you clear the dragon, and the game speeds up as you score
- Background music and a game-over sound; reload the page to play again

### 🐍 Snake Game
*Folder: `SnakeGame/SnakeGame/`*

The timeless snake game on an 18×18 grid, rendered with CSS Grid and `requestAnimationFrame`.
- **Arrow keys** — steer the snake (press any arrow to start)
- Eat food to grow and score; colliding with a wall or yourself ends the game
- High score persisted in the browser via `localStorage`
- Background music plus sounds for movement, eating, and game over

## Getting Started

No installation required.

1. Clone or download the repository:
   ```bash
   git clone <repository-url>
   ```
2. Open `index.html` in any modern browser.
3. Pick a game from the navbar or the buttons on the landing page.

> Tip: some browsers block autoplaying audio until you interact with the page — click or press a key if music doesn't start right away.

## Project Structure

```
GameZone/
├── index.html                      # Landing page (Bootstrap 5 navbar + game links)
├── JavaScript Dragon Game/
│   └── JavaScript Dragon Game/     # index.html, script.js, style.css, images & audio
├── SnakeGame/
│   └── SnakeGame/                  # index.html, css/, js/, img/, music/
└── tic tac toe/
    └── tic tac toe/                # index.html, script.js, style.css, media files
```

## Tech Stack

- **HTML5** — structure
- **CSS3** — styling, grid layout, and keyframe animations
- **JavaScript (ES6)** — game logic, DOM manipulation, audio, `localStorage`
- **Bootstrap 5** (CDN) — landing page layout only
