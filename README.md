# Office Rush

Office Rush is a browser-based endless runner game set in a stylized office environment. Players dodge workplace chaos, survive as long as possible, collect score, and compete on a live leaderboard.

## Features

- Endless runner gameplay
- Character customization
- Office-themed obstacle system
- Awareness mechanic for learning about nearby hazards
- Score tracking and leaderboard integration
- Shop / unlockable cosmetic items
- Responsive browser UI

## Gameplay Controls

- Space, W, or Up Arrow: Jump
- S or Down Arrow: Drop
- I or Alt: Trigger awareness info for a highlighted obstacle
- Mouse / touch: Click buttons and interact with UI

## How to Run

Play the live version here:

https://akramamaarhasan.github.io/Office-Rush/

This project is designed to run as a static website, so the easiest way to play is through GitHub Pages or another static hosting service.

## Project Files

- `index.html` — main game UI and game logic
- `config.js` — Firebase web config values used by the app
- `.gitignore` — excludes local-only files such as environment secrets
- `.env.example` — example environment file template for local setup

## Firebase / Leaderboard

This project uses Firebase for the leaderboard. For a browser-based game, the Firebase web config and API key are public by design and are expected to be visible in the client code.

## GitHub Repository Notes

- This project is intended to run as a static frontend.
- Browser-side Firebase config is expected to be visible in the public repo.
- Keep only local-only secrets out of GitHub.
- Use `.gitignore` to prevent accidental commits of machine-specific config or local development files.