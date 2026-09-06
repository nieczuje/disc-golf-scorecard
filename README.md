# Reagana DGC Scorecard

![Vibecoded](https://img.shields.io/badge/provenance-vibecoded-blue)

A mobile-first scorecard for **Disc Golf Park im. R. Reagana** in Gdańsk — 18 holes, par 58.

## Features

- Hole-by-hole scoring with +/- steppers
- Live leaderboard across players
- Embedded course map tab
- Self-contained single-file app — no build step, no server, no dependencies. Open `index.html` and go.

## Usage

Just open `index.html` in a mobile browser. For a home-screen "app" feel on iOS/Android, use "Add to Home Screen" from the browser menu.

## Tech

Vanilla HTML/CSS/JS. All assets (logo, course map) are base64-embedded directly in the HTML, so the whole app is one file you can drop anywhere — no CDN, no build pipeline required to *run* it.

## Notes

- Course logo and map images are inlined as base64 to keep the app a single portable file.
