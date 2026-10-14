# Ashen Vale

A first-person action RPG that runs in the browser. Pick a class, crawl the dungeon, hold the arena or fight down the Island Trail, and build your character from weapons, modifiers and skills. There are twelve classes: sword, axe, mace, spear, dagger, flail, wand, javelin, staff, bow, claws and shield, each with three combo styles, three right-click moves and its own skill pool.

**Play:** https://jtr4in.github.io/ashen-vale/

## Saves and camp

Each class keeps its level, gear, skills and the furthest floor and island it has reached, saved in the browser. Open **Camp** on the start screen to see your characters, the shared stash (40 slots; weapons for your other classes land there, and G sends any item there), and salvage your camp gathers while you are away. **Copy save code** and **Load a save code** move a save to another browser.

## Co-op

Both players open the link above. One picks **Co-op**, chooses **Dungeon**, **Arena** or **Island**, clicks **Host a run** and shares the 4-letter code; the other picks **Co-op**, types the code and hits **Join**. The host's browser runs the monsters; the two browsers find each other through public Nostr relays (Trystero) and then connect directly, so there is no server to run.

## Working on it

The whole game is `index.html`: Three.js r128 from a CDN, everything else (models, textures, sound) generated in code. Push to `main` and GitHub Pages republishes it within a minute or two.
