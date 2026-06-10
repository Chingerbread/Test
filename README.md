# Test Games

Small browser games, each in a single self-contained HTML file. No build step —
just open the file in a browser (or serve the folder with any static server).

## Battle Network 5 — Fan Clone (`battle-network.html`)

A fan-made clone of the *Mega Man Battle Network 5* battle system, written from
scratch in vanilla JavaScript on an HTML5 canvas (original code and vector art,
not affiliated with Capcom).

### Features

- **6×3 grid battles** — red panels are yours, blue panels belong to the viruses
- **Custom screen & battle chips** — the custom gauge fills during battle; open
  the custom screen to pick up to 5 chips per draw, following the classic rule:
  selected chips must share a chip **code** (with `*` wildcards) or share the
  same name
- **30-chip folder** — Cannon, HiCannon, Sword, WideSword, LongSword,
  ShockWave, Vulcan1, MiniBomb, AirShot, Recover30/80, and AreaGrab (steal
  enemy panels!)
- **Buster & charge shot** — tap to pepper, hold to charge
- **Counter hits → Full Synchro** (the BN5 signature mechanic) — hit an enemy
  during its attack wind-up to stun it and double your next chip's damage
- **4 battles with classic virus AI** — Mettaurs that line up and send ground
  waves, Canodumbs that snipe your row, fire-breathing Spikeys, and a
  teleporting sword-slinging boss
- **Busting ranks** — S/A/B/C rank and zenny rewards based on deletion time
- Synthesized sound effects via the Web Audio API

### Controls

| Key | Action |
| --- | --- |
| Arrow keys | Move on the grid |
| Z | Buster (hold to charge a charge shot) |
| X | Use the next queued battle chip |
| Enter | Open the custom screen when the gauge is full |
| Z / X / Enter (custom screen) | Select chip / undo / confirm |

## Connect 4 (`index.html`)

A browser-based Connect 4 game with falling-piece animation.
