# Linux & Bandit command deck

**Live:** https://aleisabek.github.io/Linux-Cheat-sheet/

190 Linux command flashcards in 12 topics, built for OverTheWire's [Bandit](https://overthewire.org/wargames/bandit/) wargame and everyday Linux admin. Where Windows has an equivalent, the PowerShell version is on the back of the card.

## Features

- Search every card, or filter by topic (files, finding, filtering text, encoding, archives, networking, privilege, git and more)
- A Bandit study order: which topics to review, in roughly the order the game needs them. Techniques only, no level solutions.
- Drill mode: one shuffled card at a time (Space flips, → next, Esc closes)
- Three color modes and background code rain, borrowed from SkillQuest
- One self-contained HTML file, works on phone and desktop

## How it's built

This page is generated. The cards live in **SkillQuest**, my offline IT and security practice app, where I study them with spaced repetition. An export script (`tools/export-deck.js` in that project) writes this `index.html` from the same deck, so the site and the app never drift apart. To update: add cards in SkillQuest, run `npm run export-deck -- --out <this repo>/index.html`, commit, push.

By Alei Sabek, cybersecurity student at UHD. Portfolio: https://aleisabek.github.io
