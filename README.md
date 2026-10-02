# Office Rush

Office Rush is a browser game set in a stylized office environment where players dodge workplace chaos, survive as long as possible, build score, and compete on a live leaderboard.

This project is a complete playable static web game and portfolio piece, combining responsive UI, interactive controls, custom character styling, a live leaderboard, a shop system, and an educational awareness mechanic built around office hazards. The project uses Firebase for leaderboard and player data flow.

## How to Run

Play the game here:

https://akramamaarhasan.github.io/Office-Rush/

This project is designed to run as a static frontend game and can be hosted on GitHub Pages or any similar static hosting service.

## Game Overview

Office Rush is an endless office runner where you avoid obstacles, react to incoming chaos, and keep your run alive for as long as possible.

The game includes:

- a score-based survival loop
- keyboard and mobile/touch controls
- a pause system and music toggle
- player customization options
- a shop for cosmetic unlocks
- awareness prompts to explain nearby hazards
- a top-10 leaderboard
- game-over stats and personal-best tracking

## Features

- Endless runner gameplay
- Office-themed obstacle system with multiple hazard types
- Score progression and milestone-based score feedback
- Character customization including:
  - character selection
  - hair style selection
  - skin tone selection
  - hair colour selection
  - ambience colour selection
- Unlockable cosmetic shop system
- Awareness mechanic for learning about nearby hazards
- Pause and resume system
- Music toggle and sound effects
- Personal best tracking
- Game over screen with score and obstacle-summary stats
- Firebase-powered leaderboard integration
- Responsive browser UI for desktop and mobile play
- Multiple office visual themes and atmosphere variations

## Gameplay Controls

### Keyboard

- Space, W, or Up Arrow: Jump
- S or Down Arrow: Drop
- I or Alt: Trigger awareness info for a highlighted obstacle
- Escape or P: Pause the game
- Mouse / touch: Click buttons and interact with the UI

### Mobile

- On-screen jump and drop buttons are available for touch devices

## Screens and Systems

- Start screen with player name entry and customization menu
- Character selection and custom appearance editor
- Pause menu
- Awareness panel for learning about glowing green obstacles
- Shop screen for spending awareness points
- Game over screen with final score and leaderboard submission
- Top 10 leaderboard display

## Project Files

- `index.html` — main game UI, rendering, and game logic
- `config.js` — Firebase web config values used by the app
- `.gitignore` — excludes local-only files such as environment secrets
- `.env.example` — example environment file template for local setup

## Firebase / Leaderboard

This project uses Firebase for the leaderboard and player tracking. For a browser-based game, the Firebase web config and API key are public by design and are expected to be visible in the client code.

This is safe for GitHub-hosted static deployments as long as you do not expose server-side secrets, admin credentials, or private backend keys.

## GitHub Repository Notes

- This project is intended to run as a static frontend.
- Browser-side Firebase config is expected to be visible in the public repo.
- Keep only local-only secrets out of GitHub.
- Use `.gitignore` to prevent accidental commits of machine-specific config or local development files.
- A public GitHub Pages link is the recommended way to share the playable version.

## Notes

Office Rush is a complete playable static web game designed to highlight game feel, UI polish, interaction design, scoreboard progression, and a full arcade-style loop in a compact browser experience.