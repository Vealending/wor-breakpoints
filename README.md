# WoR Breakpoints

ATK SPD breakpoints and rage timing for every Watcher of Realms hero, computed from the game client's own data tables and its decompiled combat code.

Live: https://vealending.github.io/wor-breakpoints/

Pick a hero, set your ATK SPD and Rage Regen, and see how fast the rage bar fills, when the first ultimate comes after deploy, and which ATK SPD values actually shorten the attack interval (attacks run on a 66 ms clock, so only certain values matter). "How this is computed" at the bottom of the page shows the exact arithmetic for the selected hero.

This repository holds the generated site only (`index.html` plus `img/`). Hero art and UI sprites are the game's own assets.
