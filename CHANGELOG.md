# Changelog

Notes for each release also appear on the [Releases](https://github.com/CrackedNamless/Aion2-QoL/releases) page. Versions before 1.4.0 are listed there.

## 1.8.4

### Fixed
- **Menus hiding the overlay again after updates.** The menu reader no longer gets confused when the game sets a neighbouring flag next to the "menu open" bit, which made it lose its settings and hide the HUD, timers and DPS meter at random. It now ignores that bit and goes back to the known layout by itself.

## 1.8.3

### Added
- **Pet spots on Reshanta.** The map now shows where to farm pet souls on Reshanta: Karnif, Skama, Coradon, Slink, Young Slink, Klaw, Kalgolem, Agrint, Zelophi, Nepenthes, Swarm and Slime. They work with the pet farm list, the map filter and the guide arrow like the pets of Verteron and Altgard. Pets whose monsters we cannot match with certainty are not shown yet.

### Fixed
- **Reshanta showed every pet as "all maxed".** The pet picker said "all maxed" for any type with no known spots on the chosen map. It now says "no spots yet", and "all maxed" only appears when the pets really are finished.

## 1.8.2

### Fixed
- **Menus did not hide the overlay after the latest game patch.** The app now finds the game's UI system on its own from the player, so the HUD, timers and DPS meter hide again when a game window or menu is open.

## 1.8.1

### Added
- **Send log button.** The bottom-right button bar of the map has a new button that sends your session log to the developer, to help find bugs. Your home folder, computer name and character name are removed before it is sent. You can send one log every 5 minutes.
- **Hidden Cube finder in the tour.** The guided tour has a new animated step showing how the Hidden Cube finder works (25 steps now).

### Changed
- **The first-run tour is mandatory.** It can no longer be skipped the first time. You can replay it any time from Help (<kbd>F1</kbd>), and the replay can be skipped.

### Fixed
- Widgets blinking when the map was opened or closed, and menus that did not hide the overlay right after the map was closed.

## 1.8.0

### Added
- **Routes rebuilt from scratch.** Every stop is Pending, Done or Skipped, and you can skip a stop, go back, re-plan, reverse the route or jump to any stop. A *Repeat* switch loops the route. The *Build* tab lets you choose Gathering, Feathers or Cubes and tick exactly which resources to include, and a *Saved* tab keeps your routes. While a route is running the top chip shows the progress, the distance and Skip / Pause.
- **Hidden Cube detour.** With the new *Cube detour* switch, a Hidden Cube near your route becomes the target until you collect it. <kbd>Ctrl</kbd>+<kbd>F11</kbd> skips a stop or ignores the cube.
- **First-run setup.** The first time the map opens you choose your map shortcut in a short popup, and the guided tour starts right after it.
- **Menus hide the overlay in both control modes.** The HUD, timers and DPS meter now hide whenever a game window or menu is open, in the AION 1 and the AION 2 control modes. It is on by default, so nothing needs to be switched when you change mode.
- **Heights read from the game.** The app now reads the exact position of the gathering nodes the game has loaded around you and uses it as the height of the markers they sit on, so markers you never walked over get a correct height. These heights are also shared with the online table and replace wrong values there.
- **Self-updating after a game patch.** The camera angle, the node-type id and the node position layout are found again by the app on its own, so the arrow, the Hidden Cube finder and the feather detection keep working after most patches without a new version.
- **Crash log.** If the program ever stops unexpectedly it writes a short report (`crash.log`) next to its settings, so the cause can be found and fixed.

### Changed
- Any single Shift or Ctrl key can now be bound to a shortcut on its own, for example <kbd>Right Shift</kbd>.
- The route arrival radius is 5.5 m in 3D when the height is known, so the next stop starts as soon as you are really there.
- **Quick search and item finder removed for now.** <kbd>Ctrl</kbd>+<kbd>F</kbd> no longer opens the search card: it was not reliable enough and will come back rebuilt from scratch. The News and Pets cards keep their own search box.

### Fixed
- Menus that did not hide the overlay in some game windows.
- Wrong marker heights (too low, from other players' hovering visits) no longer stay in the online table once a player reads the real height from the node.

## 1.7.4

### Fixed
- **Collected feathers are now marked on every map.** In 1.7.3 the feathers you had already collected were only recognized on Altgard. The app now reads them on Reshanta and Verteron too, and works out each map's own collected/uncollected markers by itself.

## 1.7.3

### Added
- **Feathers are marked as found by themselves.** Every Empyrean feather you collect is ticked on the map the moment you pick it up, and the feathers you had already collected are ticked as the game loads them around you (about 100 m), so you no longer have to mark them by hand. Feathers you have not collected are never marked.

### Changed
- The "found" button now appears only on Empyrean feathers, and *Hide found* is on by default.
- The pet farm list is hidden outside the open-world maps (dungeons, instances), where it has nothing to show.

## 1.7.2

### Added
- **Keybinds.** A new *Keybinds* button on the map toolbar lists every shortcut. Click one, press the new keys and it is rebound; a circular arrow puts it back to the default and *Reset all* restores everything. Shortcuts that work in the game need Ctrl or Shift so they never fire while you type, and a key taken from another action unbinds that action with a note.

### Changed
- The map now opens with **Right Shift + M** instead of Right Shift alone (change it in Keybinds). The help, tooltips, tour and widget editor show your current keys.
- The pet farm list is more compact: rows are smaller, at most 5 are visible and the list scrolls when you track more.

### Fixed
- **Pet banner shown by mistake.** The "go back to the login screen" notice no longer appears when your saved pet data was already loaded at start.

## 1.7.1

### Fixed
- **Pets not loaded after an update.** The game only sends your pet collection when you log in, so an app started or updated mid-session had nothing to show. The pet farm list and the Pets card now detect this and tell you to go back to the login screen and enter your character again; once loaded, your pets are saved for the next start.

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
