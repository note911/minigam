# PlayZone Project Notes

## Purpose
PlayZone is a lightweight game-link launcher website.

## Main file
- `index.html` — complete front-end interface and browser-side game list logic.

## Server
- `server.js` — small Node.js HTTP server that serves project files.
- `package.json` — project metadata and start script.
- `render.yaml` — Render Web Service deployment configuration.

## Editing guidance
- Keep the page responsive on mobile and desktop.
- Preserve safe URL validation: only `http:` and `https:` game links should be accepted.
- Game links should open in a new tab with `noopener noreferrer`.
- The saved game list currently uses browser local storage, so it is local to each browser/device.
