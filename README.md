# Enhanced Hidden Options Unlocker (Cyberpunk 2077 v2.3x)

## Overview
This mod updates the classic *Hidden Settings Unlocker* for the newest Cyberpunk 2077 builds (2.3x).  
It merges the old unlocker changes into the modern `options.json` schema, so you get advanced/hidden options without breaking startup.

## Features
- Unlocks advanced graphics toggles (Global Illumination Range, Texture Quality, Crowd Density “Psycho”).
- Exposes extra HUD and interface controls.
- Preserves **all vanilla v2.3x settings** so nothing is lost.
- Compatible with Mod Settings, CET, RED4ext, TweakXL, etc.
- Prevents launcher crash / silent exit caused by outdated schema overwrites.

## Installation
1. Backup your existing `Cyberpunk 2077\r6\config\settings\options.json`.
2. Copy the provided `options.json` from this mod into the same folder.
3. If needed, delete the `Cyberpunk 2077\r6\cache\` folder (the game will rebuild it).
4. Launch the game (ideally via `Cyberpunk2077.exe` first run to test).

## Compatibility
- **Tested on game version 2.31**
- Works with CET, RED4ext, ArchiveXL, Mod Settings, TweakXL.
- Will skip a few removed/renamed legacy options to avoid errors.

## Notes
- This mod does not overwrite new settings; it merges only safe fields from the old unlocker.
- If CDPR releases another update that alters `options.json`, re‑merging may be required.
- Always backup your config before applying new mods.

---
Author: Cockpit
Date: 20250929
