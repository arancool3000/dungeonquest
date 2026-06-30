# Dungeon Quest 3D

A first-person (and overhead) action-RPG set in **one continuous country** with
**enterable buildings**, a **second district**, a **day/night cycle**, and
**arcade minigames** — all in a single self-contained HTML file. Textures,
sprites and music are generated in code. No build, no dependencies, no network.
Open `index.html` and play (desktop or phone).

## The world
- **The town square** — wandering townsfolk, lamps, and **shops you walk into**:
  - **The Inn** (rest = full heal + save)
  - **The Smithy** (buy weapons & armour)
  - **The Arcanist** (potions & tomes)
  - **The Arcade** — step to the cabinet to play minigames
- **Green fields**, **deep jungle** (with a Snake stone), and the **shore**.
- **The Harbour** — a second district reached by road: market stalls, gulls,
  the open sea, and more townsfolk.
- **Cave mouths** in the fields: walk **down the steps** into the Hollow Caves,
  then deeper to the **Throne of the Lich**.
- A **day/night cycle** — the sun arcs over, dusk falls, the moon rises and the
  **lamps & braziers glow** in the dark.

## Minigames (play them in the world)
Six in-world minigames, each with saved scores:
- 🐍 **Snake** · 🍎 **Apple Catch** · 🎯 **Shooting Gallery** · ⛳ **Mini-Golf**
  · 🃏 **Memory Match** (in the Arcade) · 🎣 **Fishing** (off the Harbour dock).
- ⛳ A **golf flag** also stands on the green out in the fields.

## Houses you can enter (furnished)
Walk through the door into modelled rooms with furniture (beds, tables, chairs,
bookshelves, hearths, cauldrons, anvils, counters):
- Town: **Inn**, **Smithy**, **Arcanist**, **Arcade**.
- Harbour: **Library** (a scholar + shelves), **Tavern** (barkeep + patrons),
  a **Cottage** (a resident, bed and hearth).

## Living world
- **Wandering townsfolk** in the town and Harbour.
- **Day/night cycle** — sun & moon, dusk, and **lamps/hearths that glow** at
  night (and inside).
- **Weather** — clear skies give way to **rain** (with lightning & thunder) and
  rolling **fog** that dims the daylight.
- **Ambient sound** per area — birdsong in the fields, gulls and surf at the
  shore, insects in the jungle, drips in the caves, fire crackle indoors — plus
  footsteps that change with the ground (grass, sand, stone).

## Things to do
- **Notice board** in the town square — accept odd jobs (cull crabs, clear
  slimes, collect gold, break skeletons), complete them out in the world, then
  return to **claim gold, XP and potions**.
- **The Tavern** (Harbour) — buy an ale for a slow-healing regen buff.
- **The Library** (Harbour) — study for a temporary **+50% XP** buff.

## Two camera views
First-person ray-cast 3D, or an **overhead tilted** view — press **V** anytime.

## Controls
Move **WASD** / arrows · strafe **A/D** · look **drag/mouse** · **jump** Space ·
attack **F / click / tap** (Ranger charges) · ability **Shift / right-click**
(Knight block · Ranger dodge · Mage fireball) · interact/enter **E** ·
potions **1 / 2** · map **M** · overhead **V** · hero **I** · pause **Esc** ·
help **❓**. Turn sensitivity is in **Options**.

## RPG
Three classes, XP & levels, gold, gear tiers, the shops above, a main quest plus
the notice-board side jobs, tavern/library buffs, real-time combat with
telegraphs, chests/keys/levers, procedural audio (SFX + adaptive music),
auto-save/Continue, Quality toggle.

## Notes
- The surface country is **one connected map**; the only descents are the cave
  stairs you physically walk down (the camera dips as you take the steps) and
  the building doors you walk through. Buildings, the Harbour and the caves are
  linked by walkable doors/roads.
- True free-form terrain height (Doom-style multi-level sectors) isn't simulated;
  elevation is the walkable stairs + jump.

Single self-contained `index.html` (~134 KB). Open and play.
