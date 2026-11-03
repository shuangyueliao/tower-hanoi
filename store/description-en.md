# Tower Hanoi — Store Submission Materials

## Short description (CrazyGames / GameDistribution / itch.io)

Classic Tower of Hanoi puzzle: move the whole stack to the right peg, one disk at a
time, never a big disk on a smaller one. 3–8 disks, smart hints, AI demo mode, and a
gold PERFECT star for matching the mathematical optimum. Easy to learn, deceptively deep.

## Details

- Genre: Puzzle / Classic / Casual
- Controls: Mouse / Touch — tap a peg to lift its top disk (it floats and follows the
  pointer), tap a target peg to drop; drag-and-drop also works. Keyboard: H for hint,
  M to mute, Esc for menu, 3–8 to pick difficulty.
- Features: 3–8 disk difficulty, move counter vs optimal (2^N−1), PERFECT gold star,
  hint system (3 per game, always an optimal-path move), AI demo mode, per-difficulty
  best score in localStorage, win fireworks, WebAudio synth sounds, mute toggle.
- Tech: Vanilla JavaScript, Canvas, WebAudio. Single-file HTML5, no external assets,
  no frameworks, no tracking. Works offline once loaded.

## Tags

hanoi, tower of hanoi, puzzle, classic, logic, brain, casual, single-file

## CrazyGames submission checklist
- [x] Self-contained index.html (SDK loads only on crazygames domains)
- [x] gameplayStart / gameplayStop / loadingStart / loadingStop / happytime events wired
- [x] Responsive (canvas scales, portrait-friendly)
- [x] No external links inside gameplay, no analytics
- [ ] Cover: cover-16x9.png (1280×720)
- [ ] Screenshots: screenshot-raw.png (1280×800)

## GameDistribution
- Upload tower-hanoi-gd.zip (contains only index.html)
- SDK auto-included on gamedistribution / gd.games domains via domain-guard loader

## itch.io
- Upload zip (tower-hanoi-itch.zip), mark "This file is playable in browser",
  entry file: index.html, viewport 480×620, kind: html
- Pricing: $0 (donations optional)
