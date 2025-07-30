# Changelog

All notable changes to this add-on will be documented in this file.

## 2.2.0 - 30 July 2025

- Added 250 new individual structures: 52 Savanna Village, 40 Snowy Village, 45 Abandoned Desert Village, 61 Abandoned Plains Village, and 52 Old Zombie Village (all variants).
- Added a new instant Old Village design for all variants (Desert, Plains, Savanna, and Taiga).
- Added instant village generation for Savanna Village, Snowy Village, Abandoned Desert Village, Abandoned Plains Village, and Old Zombie Village (all variants).
- Added Abandoned Village and Old Zombie Village populate functions.
- Chests in structures now generate with random loot.
- Fixed incorrect use of dirt blocks instead of dirt path blocks in some structures.
- Renamed vg/instant_village directory to vg/instant.
- Minor tweaks and improvements.
- Minimum engine version is now Minecraft 1.21.80.

## 2.1.0 - 25 May 2025

- Added 109 new individual structures.
    - Added all 43 remaining taiga village structures.
    - Added all 40 remaining desert village structures.
    - Added all 13 old taiga village structures.
    - Added all 13 old savanna village structures.
- Added instant taiga village generation.
- Added instant desert village generation.
    - Added 2 instant desert village designs.
- Added instant old taiga village generation.
- Added instant old savanna village generation.
- Added old village populate function.
- Instant old villages are now populated upon generation.
- Fixed oak tree not generating in plains_2 instant village.
- Minor tweaks and improvements.

## 2.0.0 - 13 April 2025

- Structures now generate in the cardinal direction the player is facing.
- Added a new instant plains village design.
- Added old desert village structures.
- Added instant old desert village generation.
- Added snowy village farms and small houses.
- Fixed door generation for structures with double door configurations.
- Fixed incorrect default mirroring for old plains village structures.
- Fixed incorrect blocks for plains and savanna village structures.
- Fixed incorrect old plains village blacksmith structure chest rotation.
- Added missing cobblestone stairs to the old plains village blacksmith structure.
- Beds in plains and savanna village structures now generate in the appropriate colour.
- Old plains village well bottom no longer generates outside structure bounds.
- The populate function now attempts to spread mobs farther.
- Mobs summoned by the populate function are now tagged with the corresponding spawn events.
- Redesigned the help function system to improve navigation. Now, every subfolder has only one help function that indexes every available function it contains.
- Improved compatibility with third-party add-ons. All functions specific to the add-on are now scoped under the vg namespace.
- Updated command syntax used in function files to the new format.
- Pack name and description are now translated for all languages supported by Minecraft.
- The minimum supported engine version is now Minecraft 1.21.60.
