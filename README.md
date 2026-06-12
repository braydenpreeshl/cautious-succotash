# LiftLog 🏋️

A simple, fast workout tracker that runs entirely in your browser — no account, no server. Log exercises with **weight, reps, and sets**, and watch your **progressive overload** on a chart.

## Features

- **Log tab** — quickly log a set with exercise name (with autocomplete from your history), weight, reps, sets, and date. Shows what you lifted last time for the same exercise.
- **Progress tab** — per-exercise chart of your top weight and estimated 1RM (Epley formula) over time, with a PR badge when you hit an all-time best.
- **History tab** — all entries grouped by day, with per-set volume and delete.
- **kg / lb toggle**, dark theme, works offline (PWA), data stored privately on your device via localStorage.

## Use it on your iPhone

1. Enable GitHub Pages for this repo: **Settings → Pages → Source: Deploy from a branch → Branch: `main` / root → Save**.
2. Open the published URL in **Safari** on your iPhone.
3. Tap the **Share** button → **Add to Home Screen**.
4. Launch it from your home screen — it runs fullscreen like a native app and works offline.

Your data never leaves your phone (it's stored in the browser's localStorage).

## Files

- `index.html` — the entire app (HTML + CSS + JS, no dependencies, no build step)
- `manifest.webmanifest` — PWA manifest for home-screen install
- `sw.js` — service worker for offline support
- `icon-180.png`, `icon-512.png` — app icons
