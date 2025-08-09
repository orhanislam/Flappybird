# Flappy Bird (HTML5 Canvas)

A lightweight Flappy Bird clone built with vanilla JavaScript and Canvas. No external assets, responsive-ish, and accessible controls.

## Run

- Open `index.html` in a browser, or
- Serve the folder with any static server:

```bash
python3 -m http.server 8080 --directory /workspace/flappybird
# then open http://localhost:8080/
```

## Controls

- Space / Arrow Up / Click / Tap: Flap
- P: Pause / Resume
- R: Reset
- Buttons in the HUD also work.

## Notes

- Difficulty ramps up by increasing pipe speed and reducing the gap as your score increases.
- Best score is stored in `localStorage`.