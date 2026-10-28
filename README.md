# Lumen

**Search. See. Feel.**

An immersive Unsplash visualizer for inspiration, references, and mood boards.

## Live prototype

This is a single-file HTML/CSS/JS app. Open `index.html` locally or host it (GitHub Pages works).

## Setup

1. Get a free Access Key at [unsplash.com/developers](https://unsplash.com/developers) (demo mode: 50 requests/hour).
2. Open the page and paste the key when prompted. It is stored only in your browser’s LocalStorage.
3. Start searching.

## Features

- Cinematic masonry results with lazy loading + infinite scroll
- Orientation filters
- Full-screen detail view with download (tracks Unsplash downloads) and photographer credit
- Local collections / mood boards (LocalStorage)
- Search history
- Dark mode by default + light toggle
- Keyboard: `/` to focus search, `Esc` to close
- “Surprise me” for random high-quality terms
- Fully responsive

## Notes

- Photos are served via the official Unsplash API and remain subject to [Unsplash guidelines](https://unsplash.com/documentation#guidelines).
- Collections and history never leave the browser in this prototype.
- For production use, apply for higher rate limits and consider a backend proxy.

## Repo

Created as a public prototype of the Lumen concept.
