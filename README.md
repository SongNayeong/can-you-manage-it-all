# Can You Manage It All? · City Control

A one-minute browser game: you run a city's night shift at a cute control centre.
Traffic lights, power and air quality break; press the matching arrow key and your crew runs out to fix them.
Round 2 adds PEEKO, an early-warning monitor. In round 3, BEEPO the AI helper offers to take over the whole country.

> A small personal reference project: one self-contained HTML file, no build step, no server, no tracking.

**Play:** open `index.html` in Chrome or Edge, or use the GitHub Pages link of this repository.

## Controls (laptop)

| Key | Action |
|---|---|
| ← or A | Red · SIGGY (traffic lights) |
| ↑ or B | Yellow · VOLT (power) |
| → or C | Blue · PUFF (air quality) |
| ↓ or N | Green · BEEPO (round 3), skip the story |
| Space / Enter | Start, next |
| Esc | Back to the start screen |
| M | Sound on / off |

A gamepad also works (face buttons or D-pad).

## Notes

- Sound needs one click or key press first (browser rule). The crew talk in babble blips; BEEPO uses the browser's built-in speech voice.
- Because `index.html` loads `three.min.js` from the same folder, some browsers block it when opened as a local file; if the city does not appear, run any small local server (for example `npx serve`) or use GitHub Pages.
- Everything runs in the browser; scores are kept only in your own browser (localStorage).
- All city data, numbers and damage figures in the game are made up for the game.
- Characters, story and names are original and fictional.
- 3D engine: [three.js](https://threejs.org) r128, MIT licence (see `three.LICENSE.txt`).
