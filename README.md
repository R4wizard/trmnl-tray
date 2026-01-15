# TRMNL Tray

Simple tray/menubar app that displays the current TRMNL screen image.

## Run (dev)

1. `npm install`
2. `npm start`
3. Click the tray/menubar icon, paste your TRMNL `access-token`, press **Refresh**.

The app saves your token locally and auto-refreshes using the `refresh_rate` returned by the API.

## Tray icon theming

- macOS: `assets/tray-icon.png` is treated as a template image (auto light/dark).
- Windows/Linux (optional): add `assets/tray-icon-dark.png` and `assets/tray-icon-light.png` for theme-aware icons.

## Build

- `npm run dist`
