# Mod list — up to 30 mods for Forge 1.20.1

Each entry lists the mod, who makes it, and **why it is in the pack** (its
balance role). Versions below are the latest stable for **Forge 1.20.1**.

> Download everything from the official sources (CurseForge / Modrinth / GitHub).
> Links are to the project pages, not direct jars, so you get the right version.

## 1. Core libraries (needed, add no gameplay on their own)

1. **Forge** — the loader itself.
2. **GeckoLib** — animation library used by Alex's Mobs and Better End/Nether mobs.
3. **Caelus** — library for the Elytra code used by the Better dimension mods.

## 2. Tech & build (Create)

4. **Create** — mechanical automation: kinetics, contraptions, trains. Slow,
   resource-hungry on purpose (the pack's "effort = reward" core).
5. **Create Additions** — small extras so Create synergises with the redstone and
   electrical sides of the pack without power-creeping it.

## 3. Food & farming (renewable, balanced)

6. **Farmer's Delight** — cooking and farming. Renewable food that feeds
   adventure without trivialising hunger.
7. **Croptopia** — more crops. Counterpart to the danger: more food variety,
   but slower to set up than mid-game farms.

## 4. Creatures & mobs (danger counterweight)

8. **Alex's Mobs** — adds many animals, monsters and bosses. Their difficulty
   offsets the power of new tools/food.

## 5. World & biomes (exploration space)

9. **Terralith** — ~95 brand new biomes and revamped worldgen. This is the "go
   explore" area.
10. **YUNG's Better Caves** — true cave sizes and cave biomes. Deep caves are
    dangerous but loot-rich. (Big content, sits in the exploration slot.)
11. **YUNG's Better Mineshafts** — better underground structures to find while
    exploring caves.

## 6. Dimensions (the big goals)

12. **Better End** — rework of the End: new biomes, mobs, **materials** and a boss.
13. **Better Nether** — rework of the Nether: new biomes, mobs, **materials** and
    harder areas.

## 7. Exploration tools (direction without teleports)

14. **Explorer's Compass** — locates structures & biomes so you can plan trips.
15. **Adventurer's Compass** — locates **bosses and Wither** so you can find the
    end-game fights.

## 8. Maps & the world on your back

16. **JourneyMap** — minimap and full-screen map (client-side). Exploration
    planning tool, not a teleport.
17. **Traveler's Backpack** — carry more gear. Storage that weighs inventory
    management, no cheap shulkers.

## 9. Bosses (end-game challenge gate)

18. **Bosses of Mass Destruction** — new high-difficulty bosses.
19. **Cataclysm** (L_Ender's Cataclysm) — an end-game boss that drops the
    strongest loot, intended as the final challenge.

## 10. New materials (boss-gated, so they stay balanced)

20. **Better End's Ender materials** — Enderite etc. only obtainable after beating
    the End boss content.
21. **Better Nether's Nether materials** — Netherite alternatives gated behind
    Nether exploration, not a free upgrade.

## 11. Quality of life (kept minimal, no cheats)

22. **JEI (Just Enough Items)** — recipe viewer. Needed to learn all new recipes.
23. **Jade / WAILA** — see what block you're looking at (helpful with new blocks).
24. **AppleSkin** — shows hunger/saturation, so the food mods make sense.
25. **Controlling** — keybind manager for all the new keybinds.

## 12. Performance & polish (keeps the big world playable)

26. **Embeddium** — performance for the large Terralith world.
27. **FerriteCore** — memory optimisation.
28. **Fastload** — speed up world loading.

## 13. Balance & safety tuning (see `config/`)

29. **Balance config** — in-`config/` tuning applied by this pack
    (compass crafting costs, backpack size, Terralith structure density, and
    Better dimension difficulty). This is not a jar, it's config files.
30. *(reserved, optional)* **JadeAddons** or **Towns & Towers** — keep the pack at
    exactly 30 mods; Towns & Towers adds more buildable structures (adds
    exploration content but stays optional to keep performance).

---

### Balance decisions applied (see `config/`)

| Concern | Decision |
|---|---|
| Teleporting | No teleport or waypoint-teleport mod. Compasses only point. |
| New materials | Gated behind their dimension's boss/exploration. |
| Food | Renewable but slower than mid-game automation. |
| Mobs | Alex's Mobs danger counters new tools. |
| World density | Terralith structure density tuned up so compasses find things. |
| Inventory | Backpack caps stack size; no creative-style storage. |
