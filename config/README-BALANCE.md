# ============================================================
#  Ender Exploration Modpack — Balance overlay
#  Applies the balance decisions of this pack.
#  Copy the whole config/ folder into .minecraft/config.
# ============================================================

# The values below are the pack's *intended* tuning. Where the mod exposes
# the setting, set it to the listed value in the mod's own config file.
# The pack ships its own note-files so you can apply the balance by hand fast.

# ---------------------- compasses ---------------------------
# Mod: Explorer's Compass (explorerscompass-common.toml)
# Mod: Adventurer's Compass (adventurerscompass-common.toml)
# Goal: compasses point to targets, but must be crafted and used with real
#       travel. Do NOT install any teleport mod — this pack bans teleporting.
#
#   general.allowTeleport = false
#   general.distanceMultiplier = 1.2   (slightly longer ranges, still walk)

# ---------------------- backpack -----------------------------
# Mod: Traveler's Backpack
# Goal: useful extra storage, not a creative shulker. Cap the stack size and
#       keep the backpack disabled in the nether if the mod offers that.
#
#   general.tieredStackSizes = true
#   general.netheriteUpgrade = false   # keep the top tier gated behind netherite

# ---------------------- Terralith structure density ----------
# Mod: Terralith (terralith-common.toml)
# Goal: villages/structures stay findable so Explorer's Compass has targets.
#
#   worldgen.villageDensity = 1.0      # default, do not reduce
#   worldgen.structureDensity = 1.0    # default, do not reduce

# ---------------------- Better End / Better Nether -----------
# Goal: new materials are gated behind their dimension bosses, so the ores and
#       gear are end-game rewards, not early handouts. Leave boss difficulty
#       at default or higher.
#
#   (Better End)  blacklistedMobs = []          # keep bosses enabled
#   (Better Nether) terrain.generationChance = 1.0

# ---------------------- Alex's Mobs --------------------------
# Goal: dangerous mobs offset the power of new tools and food. Keep hostile
#       mob spawn weights at their default (do not raise friendly spawns).

# ---------------------- Create -------------------------------
# Goal: automation stays slow & resource-hungry. Do not enable cheating
#       "free energy" addons. Create Additions is the only Create addon.
