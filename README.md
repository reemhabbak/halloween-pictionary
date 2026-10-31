# 🎃 Halloween Pictionary

[![License: CC BY-NC 4.0](https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc/4.0/)

A Halloween-themed Pictionary companion that runs in any browser. No install, no build step, no accounts.

Each card has five Halloween words, one per category, color-coded to match the classic Pictionary category card:

| Tag | Category |
|-----|----------|
| **P** | Person / Place / Animal |
| **O** | Object |
| **A** | Action |
| **D** | Difficult |
| **AP** | All Play |

## Features

- **Draw and discard** cards from shuffled decks (no repeats until a deck runs out)
- **Pick your category** by tapping the row matching your board square, or roll one at random
- **All Play** rounds where every team draws at once, plus optional surprise All Plays (▲) on other rows
- **Built-in timer** (30 sec to 2 min) with a countdown ring and end-of-round sound
- **Score keeping** for 2–4 teams with editable names, manual +/− adjustments and a points-to-win target
- Light and dark modes, works on phones, and scores are saved in the browser between sessions

## How to play

1. Tap **Draw card**. Only the drawer should look.
2. Tap the category row for your board square, or **Roll category**.
3. Tap **Start**. The card hides itself and the timer runs.
4. Mark the result: a correct guess scores a point and that team keeps going; a miss passes the turn. On All Play, choose the team that guessed first.

## Run it

Open ``https://reemhabbak.github.io/halloween-pictionary/`` in a browser. That’s it.

.

## Customize the words

All word lists live in the `WORDS` object near the top of the `<script>` in `index.html`. Add, remove or swap words in any category; the decks reshuffle automatically.

## Tech

A single self-contained HTML file with vanilla JavaScript and CSS. Fonts load from Google Fonts (Grenze Gotisch and Figtree) with system fallbacks.

## License

© 2026 Reem Habbak. Licensed under [Creative Commons Attribution-NonCommercial 4.0](https://creativecommons.org/licenses/by-nc/4.0/) (CC BY-NC 4.0). You’re welcome to share and adapt it with credit, but not for commercial use. See [LICENSE](LICENSE).
