# Changelog

All notable changes to this add-on will be documented in this file.

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