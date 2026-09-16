# Gatsby Trail Camera — clickable prototype

Static site. Open `index.html` (or the GitHub Pages URL). No build step.

- `index.html` — the prototype app (all CSS/JS inline)
- `data.js` — screens, hotspots, notes and paths extracted from the Figma page "P1 - Flow"
- `img/` — screens exported from Figma at 2×, WebP

Modes
- Facilitator (default): right-hand panel with screen name, P0/P1 tag, designer notes, callouts and every path out of the screen.
- Participant: add `?mode=test` to the URL (or use "Copy participant link"). Clean phone, no annotations; tapping a non-hotspot flashes the hotspots.

Deep links: `#/<flow>/<screenId>` e.g. `#/zc1/4004:124361`. Flows: zc1, zc2, ble, sub, wifi, edge, checkin.

Keyboard: H hotspots · A callouts · F panel · ← back · → first path · Esc all flows.
