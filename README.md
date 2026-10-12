# The Apocalypse — Single Player + Co-op

This ZIP includes both game modes in the same game page.

## Modes
- **Single Player:** starts without connecting to a multiplayer server. The game saves progress in this browser on this device, every few seconds and when the page is closed/hidden. Reopen the same hosted website on the same device/browser to continue.
- **Co-op Multiplayer:** use the optional room code and tap **JOIN / CREATE ROOM**. Multiplayer requires the included Node.js WebSocket server to be deployed to a host that supports WebSockets. GitHub Pages alone cannot run the multiplayer server.

## GitHub Pages
Upload the contents of this ZIP to the root of your repository (including `index.html`, `manifest.json`, and `sw.js`). Do not upload only the ZIP file. Commit the changes, then wait for Pages to redeploy.

## Multiplayer server
The included `server.js` and `package.json` are for a Node.js host that supports WebSockets. Install dependencies with `npm install` and run with `npm start`. The front-end WebSocket URL must point to the deployed server for co-op to connect. GitHub Pages hosts only the front-end.

## Controls
Desktop: WASD to move, mouse to look, click to shoot, R to reload. On touch devices, use the on-screen controls.
