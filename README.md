# r0ll

Dice for deciding. Single, multiplayer, or full game presets.

Live at [r0ll.app](https://r0ll.app). Part of the [0fam](https://0utput.co).

## What it is

A single-file dice rolling web app. Tap to roll. Built for the moments you need a die and don't have one, or the group needs to decide who goes first, or your Monopoly dice are missing.

## What it does

**Single** — d4 through d20, one to six dice at a time, sums auto-shown for multiple dice.

**Multiplayer** — 2 to 12 players, sample-without-replacement (no ties), die type auto-scales to the player count.

**Games** — nine presets with real game-aware logic:

- Yahtzee (5d6, hold + 3 rolls per turn)
- Farkle (6d6, hold scorers, bank or push luck)
- D&D Stat Roll (4d6 drop lowest, 6 stats)
- Liar's Dice (5d6 hidden, pass-and-play)
- Craps (2d6, named outcomes)
- Monopoly (2d6 with doubles tracker and jail-on-three)
- Catan (2d6 with 7-triggers-robber and probability dots)
- Backgammon (2d6 where doubles become four moves)
- Risk (attacker vs defender, sorted-pair resolution)

## Deploying

Drop `index.html` and `og.png` anywhere that serves static files. It's a single HTML file, no build step, no dependencies beyond Google Fonts.

For GitHub Pages: push the repo, turn Pages on in settings, pointing at the root. That's it.

## Files

- `index.html` — the app, canonical entry point for deploys
- `r0ll-20260422-16.html` — dated versioned copy (same contents, kept for archival)
- `og.png` — 1200×630 social preview image
- `icon.png` — 512×512 app icon (dotted-zero mark)

## Built with

Vanilla HTML, CSS, JS. No framework, no bundler. Synthesized audio via the native Web Audio API — no audio files shipped. Fonts from Google Fonts (Space Mono and Inter).
