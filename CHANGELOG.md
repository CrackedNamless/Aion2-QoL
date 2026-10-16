# Changelog

Notes for each release also appear on the [Releases](https://github.com/CrackedNamless/Aion2-QoL/releases) page. Versions before 1.4.0 are listed there.

## 1.5.0

### Added
- **Map button.** A small round button with the app icon floats over the game. Click it to open or close the map (a fallback for Right Shift), drag it anywhere without the layout editor. It hides while a game menu is open.
- **DPS meter in Transcendence dungeons.** Shattered Arkanis and Deus Research Base now run in dungeon mode with readable run names, and hub areas (lobby, legion, artifact) are no longer treated as dungeons.
- **Guided tour extended to 21 steps.** It now covers the map button, the timer strip with its details and settings, and the DPS meter: list, party check, skill breakdown, dungeon runs and settings, each with a preview.
- **Crash recovery.** If the program crashes while the game is still open it restarts by itself.

### Changed
- Starting the program by hand now asks for administrator rights automatically, so the map, minimap and FPS counter always work.
- Alt+F4 is ignored by the overlays, so it can no longer close the program by accident.
- The map footer reads "Made by CrackedNamless".

## 1.4.0

### Added
- **Layout editor.** The map's *Layout* button hides the map and shows a semi-transparent grid over the game. Drag the minimap, arrow, timers and DPS meter, with magnetic centre lines (vertical and horizontal), switch each widget on or off, and save from the central card (Esc also saves).
- **Item finder.** `Ctrl+F` now finds items as well as map markers. Press Enter on an item to see where to get it: drops, crafting, shops, gathering, quests and dungeons.
- **Dimensional Invasion** on the event timer strip.
- **Dungeon-aware DPS meter.** Automatic party, boss and overall views in dungeons, boss fights kept apart, and a Dungeons page with the history of your runs. An open-world boss mode.

### Changed
- **New map.** Opaque, near full screen for your monitor, sharper upscaling, smoother pan and zoom, and drawn above the other overlays.
- The map toolbar is now Route, Layout, News and Help.
- Help card and guided tour describe the new controls.

### Removed
- The lock, home and default buttons on the DPS meter and timer strip: positions are now set from the Layout editor.
- The Bosses pill and card on the map.

### Installer
- The Npcap step now accepts the signer "Nmap Software LLC".
