# Ping Pong

A self-contained HTML5 and JavaScript Pong game. Open `index.html` in a browser and play.

## How to play

- Left paddle is yours. Right paddle is a simple AI opponent.
- First player to 5 points wins.
- After each paddle hit the ball speeds up a little.
- Bounce angle depends on where the ball hits the paddle. Edge hits send it at a steeper angle.

## Controls

- Up / Down arrow keys to move your paddle
- Mouse movement over the court also moves your paddle
- Spacebar to start, pause, or resume
- On-screen Start / Resume / Restart button

## Run locally

Open the file directly:

```bash
# Open the game in your default browser
xdg-open index.html
```

Or serve it with any static file server:

```bash
# Serve the current directory on port 8000
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Files

- `index.html` — game markup, styles, and logic in one file
- `LICENSE` — project license
