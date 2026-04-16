# ScreenForge - Game Definitions

Game definition files for [ScreenForge](https://alphakiir.gumroad.com/l/screenforge).

Each JSON file defines how ScreenForge handles a specific game:
- Config file locations
- Process names for window detection
- Resolution and fullscreen settings
- Special flags (DX11 mode, read-only cfg, etc.)

## Supported Games

| Game | Status |
|------|--------|
| Metro 2033 Redux | Full support |
| Metro Last Light Redux | Full support |
| Metro Exodus | Full support (DX11 mode) |

## Adding a New Game

Create a JSON file in `games/` following the existing format. The app checks this repo for updates automatically.
