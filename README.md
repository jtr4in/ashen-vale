# Ashen Vale

A first-person action RPG that runs in the browser. Pick a class, crawl the dungeon, hold the arena or fight down the Island Trail, and build your character from weapons, modifiers and skills.

**Play:** https://jtr4in.github.io/ashen-vale/

## Co-op

Both players open the link above. One picks **Co-op**, chooses **Dungeon** or **Arena**, clicks **Host a run** and shares the 4-letter code; the other picks **Co-op**, types the code and hits **Join**. The host's browser runs the monsters; the two browsers find each other through public Nostr relays (Trystero) and then connect directly, so there is no server to run.

## Working on it

The whole game is `index.html`: Three.js r128 from a CDN, everything else (models, textures, sound) generated in code. Push to `main` and GitHub Pages republishes it within a minute or two.
