# Changelog

Notes for each release also appear on the [Releases](https://github.com/CrackedNamless/Aion2-QoL/releases) page. Versions before 1.4.0 are listed there.

## 1.7.0

### Added
- **Pet farm list.** A new widget (`Ctrl+F5`) tracks the pets you are farming, with live soul progress, three stage bars and a +N flash whenever a soul lands. Pick pets with the "+" button by type (Cogni, Fera, Natura, Varian, Special) and by map. Maxed pets move to their own tab.
- **Guided farming.** Click a pet to get a ping and the arrow, plus the nearest teleporter when it saves you a long run. On another map it tells you where to farm. When a pet reaches MAX the closest pet you are tracking is guided for you.
- **Pets card.** Press `P` on the map to browse your whole pet collection with live souls and click a pet to find its spawns.
- **Open world DPS.** A new "Open world: Everyone / Only me" setting, and the DPS rows now slide smoothly when the ranking changes.
- Pet farm list in the guided tour (24 steps), in the widget editor and in the shortcut list.

### Changed
- The map toolbar's *Layout* button is now **Widgets**, and the toolbar reads Route, Widgets, News, Party QoL and Help. The pet buttons were removed from the toolbar: the Pets card stays on `P`.

### Fixed
- The arrow and minimap distance no longer follow the camera on PCs where the position reader had locked onto a camera object. Camera, spring arm and controller objects are now rejected.

## 1.6.0

### Added
- **Party check popup.** When you join a party a centered card lists every member with class, level, gear score, combat power and server. It closes by itself when the party ends or when you enter an expedition or a Transcendence.
- **Party QoL menu.** A new *Party QoL* button on the map toolbar opens a card with a switch for the party check. When it is off the popup is disabled completely.
- **Server column** in the party tab of the DPS meter.
- **CPU and GPU load** (and GPU temperature on NVIDIA cards) as a second row on the timer strip, with a switch in its settings.
- **New waypoint arrow.** A redesigned 3D arrow with a symmetric shape and the game's colour palette.
- **Bottom-right buttons on the map:** check for updates, changelog, GitHub and issues.

### Changed
- The map toolbar is now Route, Layout, News, Party QoL and Help.
- Guided tour extended to 23 steps (Party QoL and the corner buttons, new timer strip and party check texts) and the help card updated.

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
