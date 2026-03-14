# 🔥 Habit Streak Tracker

A tiny, beautiful daily habit tracker. Log one habit per day and watch your streak grow.

## Features

- Pick an emoji icon and name your habit on first launch
- One-tap daily logging — button locks after you've logged
- Live streak counter with pop animation
- Current streak / best streak / total days stats
- 28-day calendar dot grid
- Fully persisted via `localStorage` — survives page refreshes
- Dark mode support (follows system preference)
- Zero dependencies — pure HTML, CSS, and JavaScript

## Project Structure

```
habit-streak-tracker/
├── index.html   # Entire app — one self-contained file
└── README.md    # This file
```

## Getting Started

### Run locally

Just open `index.html` in any browser — no server needed.

```bash
open index.html        # macOS
start index.html       # Windows
xdg-open index.html    # Linux
```

### Deploy (free options)

| Platform       | Steps |
|----------------|-------|
| GitHub Pages   | Push to a repo → Settings → Pages → Deploy from `main` branch root |
| Netlify        | Drag the project folder onto netlify.com/drop |
| Vercel         | `npx vercel` inside the folder |

## How to push to GitHub

```bash
# 1. Inside the project folder
git init
git add .
git commit -m "feat: initial habit streak tracker"

# 2. Create a repo on github.com, then:
git remote add origin https://github.com/YOUR_USERNAME/habit-streak-tracker.git
git branch -M main
git push -u origin main
```

## Tech

- **HTML5** — semantic, accessible markup
- **CSS3** — custom properties, dark mode via `prefers-color-scheme`, `@keyframes`
- **Vanilla JS** — no frameworks, no build tools
- **localStorage** — client-side persistence
- **Google Fonts** — Syne (display) + DM Mono (numbers)

## License

MIT — do whatever you want with it.
