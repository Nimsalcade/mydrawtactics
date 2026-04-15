# DrawTactics

A free, open-source soccer/football tactical board and animation tool that runs entirely in the browser — no sign-up, no subscription required.

## Features

- 🎨 **Tactical Board** (`index.html`) — Draw formations, player movements, arrows, shapes and text on a pitch
- 🎬 **Tactics Animator** (`tactics-animator.html`) — Animate player movements with timing or step-by-step mode, export as video
- 📹 **Video Analysis** (`video-analysis.html`) — Annotate over match footage with drawing tools
- 🖊️ **Screenshot Annotator** (`screenshot-annotator.html`) — Annotate screenshots with tactical markings

## Usage

Just open any `.html` file directly in your browser — no build step, no server needed.

Or serve locally:
```bash
npx serve .
# or
python3 -m http.server 5500
```

Then visit `http://localhost:5500`.

## Tech Stack

- Vanilla HTML, CSS, JavaScript
- [Fabric.js](https://fabricjs.com/) v5.3.0 — Canvas rendering
- [ONNX Runtime Web](https://onnxruntime.ai/) — ML inference for video analysis
- Google Fonts (Inter)

## Pitch Assets

Pitch background templates are in `/assets/`:
- `jdp-pitch.png` — JDP style
- `set-piece.png` — Set piece view
- `minimal-pitch.png` — Minimal markings
- `no-markings.png` — Plain green

## License

MIT — free to use, modify, and distribute.
