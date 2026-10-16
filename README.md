# THEETAM ARCADE — The Birthday Boss Fight

A no-build mobile-first browser game using HTML, CSS, Canvas, and JavaScript.

## Run locally
Keep `index.html` and `assets/` together. From this folder run:
```bash
python -m http.server 8000
```
Open `http://localhost:8000`.

## Deploy
Upload the contents of this folder to any static host. No dependencies or build step required.

## Assets and personalization
- Intro image: `assets/your-photo.jpg` (blended with a radial mask; the complex forest background is softened rather than fully removed).
- Atheeth player: `assets/atheeth-warrior.png` (background removed approximately).
- Poop boss: `assets/poop-boss.png` (background removed approximately).
- Dialogue and friendship letter text are editable in `index.html`.

## Controls
- Intro: tap/click dialogue to advance; the quest button appears after the last line.
- Cake: swipe upward through the cake seven times.
- Fight: move left/right using the on-screen move control (tap its left/right half), dodge, and attack. Desktop supports arrows/A/D, Space to attack, Shift to dodge.
- Sound starts enabled, but browsers may wait for the first user interaction before allowing audio. The toggle can mute it.
