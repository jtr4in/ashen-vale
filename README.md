# Ashen Vale

A first-person action RPG that runs in the browser. Pick a class, crawl the dungeon, hold the arena or fight down the Island Trail, and build your character from weapons, modifiers and skills. There are twelve classes: sword, axe, mace, spear, dagger, flail, wand, javelin, staff, bow, claws and shield, each with three combo styles, three right-click moves and its own skill pool.

**Play:** https://jtr4in.github.io/ashen-vale/

## Saves and camp

Each class keeps its level, gear, skills and the furthest floor and island it has reached, saved in the browser. Open **Camp** on the start screen to see your characters, the shared stash (40 slots; weapons for your other classes land there, and G sends any item there), and salvage your camp gathers while you are away. **Copy save code** and **Load a save code** move a save to another browser.

Pick a character at camp to see its gear. The **crafting bench** works on any item there or in the stash: reroll the weakest modifier, lock one so rerolls never touch it, reforge a weapon or shield up to your level, or empower an item a rarity tier (up to epic) with salvage and ashen cores, which you earn by clearing dungeon floors. Weapons now roll modifiers too.

Each mode pays its own way: the Island Trail pays salvage and gear for your class at every island, the dungeon pays ashen cores per floor, and the arena pays marks (free rerolls) for every boss wave. Every 3rd floor or island and every 8th wave also gives a vale key. Toggle **Heroic** on the start screen to spend a key on a solo run with tougher monsters, better drops, doubled rewards and a cache from every boss.

## Skill tree and monsters

Every level gives one skill point, and levels come slower than they used to. Press **K** (or tap **Skills**) for the skill tree. Each key has its own branch: learn a skill (Q at level 1, E at 3, R at 6), rank it up to V, add its **Enhanced** and **Mastery** modifiers, then choose one of two forms (for example Brutal or Echoing on Q). Your right-click signature ranks up too, and from level 5 four passives (Might, Vigor, Fury, Focus) take points. Switching a skill gives back the points in it, and **Refund all** resets the tree for free. Saves from before the tree keep their skills and get every point back.

Wolves, skeleton warriors, skeleton archers and stone golems join the monsters. Bosses come in five kinds with their own attacks: the winged demon, a lich who raises skeletons and throws soul bolts, a giant alpha wolf that calls its pack and leaps, a brood queen spider that hatches spiders, and a stone colossus that stamps the ground around you.

## The Chapel Below (story version)

**Play:** https://jtr4in.github.io/ashen-vale/story/

An experimental story build on the same engine, in `story/index.html` with its own save. Four classes (Warrior, Templar, Rogue, Mystic) split into three subclasses each at level 6, covering all twelve weapons. You start in Hollowmere, a small village at night under falling ash, with an elder, a blacksmith (crafting bench), a healer, a witch (subclasses) and a stash chest. The chapel leads down into Act 1: four darker crypt floors with lore pages, two quests and the Hollow Abbot.

## Ashen Realms (realm war version)

**Play:** https://jtr4in.github.io/ashen-vale/realms/

An experimental open-world build in `realms/index.html` with its own save. One big map split between three realms (Emberhold, Frostmark, Thornwood), each with a capital castle, two keeps and three villages, plus the neutral Ashen Crown in the middle and monster camps in the wilds. Swear to a realm and pick a class. The AI realms send war parties along the roads and besiege each other's strongholds whether you're there or not. Ride to your villages to break raids, storm enemy villages, keeps and castles to raise your banner, and hold all three capitals to win the season. **M** opens the war map, where you can travel to anything your realm holds.

## Co-op

Both players open the link above. One picks **Co-op**, chooses **Dungeon**, **Arena** or **Island**, clicks **Host a run** and shares the 4-letter code; the other picks **Co-op**, types the code and hits **Join**. The host's browser runs the monsters; the two browsers find each other through public Nostr relays (Trystero) and then connect directly, so there is no server to run.

## Working on it

The whole game is `index.html`: Three.js r128 from a CDN, everything else (models, textures, sound) generated in code. Push to `main` and GitHub Pages republishes it within a minute or two.
