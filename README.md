# 🎡 Gerund or Infinitive – Spin the Wheel

A single-file web app for practicing English **gerund vs. infinitive** rules.

Open `index.html` in any browser — no build step, no dependencies, works offline.

## Features

- Canvas-based spinning wheel with pointer and easing animation
- Quiz mode: spin, then pick **gerund** or **to + infinitive** and get instant feedback
- Live scoreboard — correct / wrong / left / total
- 9 categories: gerund verbs, after prepositions, expressions, infinitive verbs, verb + object + to, without "to", both (small/big change), notes
- Toggle categories with the chips above the wheel
- Progress saved in `localStorage`, so you can close the tab and resume
- Shuffle to reshuffle the word list
- Arabic translations, light/dark mode (follows system theme), mobile-friendly

## Usage

```bash
# just open it
xdg-open index.html
```

Or serve it locally:

```bash
python3 -m http.server 8000
```

## Deploy

The repo is set up for GitHub Pages — enable it under **Settings → Pages** with source `main` / root.