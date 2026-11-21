# Ashen Oath — 3D Co-op Soulslike Prototype

A browser-based 3D dark-fantasy arena with 2-player Socket.IO multiplayer, animated sword swings, heavy attacks, rolls, flasks, enemies and a boss.

## Run locally

1. Install Node.js 18+.
2. In this folder, run `npm install` then `npm start`.
3. Visit http://localhost:3000.
4. Create a room, then share the room code or invite link.

## Deploy on Render

Push **the contents of this folder** to the root of your GitHub repo. Render Web Service: Node, build `npm install`, start `npm start`. Render supplies `PORT` automatically. The game uses Three.js loaded from a CDN and needs an internet connection.

## Controls

WASD movement; mouse aim; left click slash; right click heavy; Space dodge roll; F heal; R restart after victory.

## Notes

This is an early 3D arena prototype, not a full-scale Elden Ring-style RPG. Animations are procedural, and multiplayer movement is server-updated without interpolation. Free hosting can sleep when idle. A single Render instance is required for room state (no Redis adapter). No accounts or persistent progress.
