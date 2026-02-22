# Tower Defense

A browser-based tower defense game built with vanilla HTML, CSS, and JavaScript. Place towers along the path, stop the waves of enemies, and protect your base.

![Tower Defense](https://img.shields.io/badge/game-tower%20defense-e94560)

## How to Play

1. **Start** — Click "Start Wave" to begin. Enemies will follow the path toward your base.
2. **Place towers** — Select a tower from the panel (Arrow, Cannon, or Ice), then click on the green path grid to place it. You need enough gold.
3. **Upgrade & sell** — Click a placed tower to select it, then use Upgrade (costs gold) or Sell (refund) in the panel.
4. **Survive** — Don’t let too many enemies reach the end or you’ll lose lives. Earn gold by defeating enemies and survive as many waves as you can.

### Tower Types

| Tower   | Cost  | Role                          |
|---------|-------|-------------------------------|
| Arrow   | $50   | Fast, single-target           |
| Cannon  | $100  | Slower, area damage           |
| Ice     | $75   | Slows enemies                 |

### Controls

- **Start Wave** — Start or advance to the next wave
- **Pause** — Pause/resume the game
- **Speed** — Toggle game speed

## Run Locally

No build step. Open the file in a browser or serve it with any static server:

```bash
# Option 1: Open directly
open index.html

# Option 2: Simple HTTP server (e.g. Python 3)
python3 -m http.server 8000
# Then visit http://localhost:8000
```

## Tech Stack

- **HTML5** — Structure and canvas
- **CSS3** — Layout and styling
- **Vanilla JavaScript** — Game logic, rendering, and input

Single file, no dependencies, no install required.

## License

MIT
