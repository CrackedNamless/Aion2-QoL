<div align="center">

<img src="docs/hidden_cube_finder.gif" alt="Hidden Cube Finder: a waypoint arrow and a minimap lead you to the nearest Hidden Cube" width="100%">

**Hidden Cube Finder.** Press <kbd>Ctrl</kbd>+<kbd>F9</kbd> and the arrow points at the nearest Hidden Cube around you, with its distance and height.

<br>

<img src="docs/banner.png" alt="Aion2-QoL" width="100%">

<br><br>

<a href="https://github.com/CrackedNamless/Aion2-QoL/releases/latest/download/Aion2-QoL-Setup.exe">
  <img src="docs/download.png" alt="Download installer" width="420">
</a>

<br>

[![Latest release](https://img.shields.io/github/v/release/CrackedNamless/Aion2-QoL?style=for-the-badge&color=e3bd6e&labelColor=161d2e)](https://github.com/CrackedNamless/Aion2-QoL/releases/latest)
[![Downloads](https://img.shields.io/github/downloads/CrackedNamless/Aion2-QoL/total?style=for-the-badge&color=e3bd6e&labelColor=161d2e)](https://github.com/CrackedNamless/Aion2-QoL/releases)
![Platform](https://img.shields.io/badge/Windows-10%20%7C%2011-e3bd6e?style=for-the-badge&labelColor=161d2e)
[![Issues](https://img.shields.io/github/issues/CrackedNamless/Aion2-QoL?style=for-the-badge&color=e3bd6e&labelColor=161d2e)](https://github.com/CrackedNamless/Aion2-QoL/issues)

**A quality-of-life overlay for AION 2: interactive map, live DPS meter with party check, boss and event timers, routes, pet farming and game news, one key away.**

</div>

---

## Contents

[What's new](#whats-new) · [Features](#features) · [Screenshots](#screenshots) · [Install](#install) · [Shortcuts](#shortcuts) · [Updates](#updates) · [Privacy and safety](#privacy-and-safety) · [Troubleshooting](#troubleshooting) · [FAQ](#faq) · [Changelog](CHANGELOG.md)

## What's new

**1.9.4**

- **Resize any widget with the mouse wheel.** In Widgets mode (the Widgets button on the map), put the mouse over the DPS meter, minimap, waypoint arrow, timer strip, pet list, boss widget or the map button and scroll to make it bigger or smaller. A label shows the size while you edit, the size is remembered across logins, and Reset layout brings back the defaults. Thanks to **Ennz729** for suggesting it.
- **A how-to popup in Widgets mode** explains moving, resizing and saving each time you open it.
- **Skip the NCSOFT intro.** A new tray option shortens the game's intro logo video so you reach the login screen faster. It is off by default, keeps a backup of the original file and re-applies itself after a game update.
- **The tour explains moving and resizing** with a short animation, and **the first-run tour can be skipped** again with the Skip tour button or Esc.
- **A flatter, cleaner look for every overlay:** DPS meter, timer strip, pet list, boss widget, minimap buttons, notifications, party check, settings windows and the Widgets editor now share one style.
- **One opacity for the overlays.** A single setting fades the DPS meter, timer strip, pet list and boss widget together, down to almost invisible. The text gets a thin dark outline as it fades, so the DPS meter stays readable over a bright game.
- **A more reliable start on some PCs.** The app finds the game's world data more reliably after the game finishes loading, so the world, Hidden Cubes and menu hiding work again where they were missing.
- **Empyrean feathers are marked again after the latest game update.** The game renumbered the feather nodes, so feathers you had already collected were no longer ticked off. The app uses the new ids and ignores outdated ones.

Full list in the [changelog](CHANGELOG.md).

## Features

| | |
|---|---|
| **Interactive map** | Altgard, Reshanta and Verteron with thousands of markers: bosses, named monsters, dungeons, portals, merchants, quests, gathering points and pets. Open it in game with <kbd>Right Shift</kbd>+<kbd>M</kbd> (every shortcut can be changed in the Keybinds card). |
| **Filters and progress** | Grouped categories with counters. Mark markers as found, hide what you finished, and keep your progress between sessions. |
| **Routes** | Add stops with <kbd>R</kbd> or build a route from the resources, feathers or cubes you pick, with the shortest path. Skip, go back, re-plan or repeat it, detour to Hidden Cubes on the way, and save routes to reuse them. <kbd>Ctrl</kbd>+<kbd>F11</kbd> skips a stop. |
| **Live DPS meter** | Damage per second, share and crit rate per player. Solo or party scope, top 5 plus your own rank, boss and overall views, dungeon run history (including Shattered Arkanis and Deus Research Base) and per-skill detail. A target health bar, Odyle Energy and ping sit under the list, and the settings open in a window of their own. |
| **Boss timers** | The map's *Bosses* button (<kbd>K</kbd>, or <kbd>Ctrl</kbd>+<kbd>F12</kbd> in game) lists the field bosses of Altgard, Verteron and Reshanta with a live countdown shared between the players of your server. Flag a boss to follow it, get a notification with its portrait (and an optional sound) before it respawns, and keep followed bosses in a compact widget you can place anywhere. |
| **Event timers** | Shugo, Dimensional Invasion, Rift, Siege, daily and weekly resets, plus FPS, ping, server time and an optional CPU / GPU load row. An opacity slider fades the strip down to almost invisible while the text stays readable. |
| **Alert sounds** | The map's *Sounds* button lets you choose which of seven sounds each alert plays (boss alerts, Hidden Cube), set the volume and switch each alert on or off. |
| **Party check** | A card opens when you join a party and lists every member with class, level, server, gear score and combat power. It closes by itself in expeditions and Transcendence dungeons. |
| **Party QoL** | The map toolbar's *Party QoL* menu switches the party check on or off. When it is off the popup is disabled completely. |
| **Hidden Cube finder** | <kbd>Ctrl</kbd>+<kbd>F9</kbd> points the waypoint arrow at the nearest Hidden Cube around you (about 100 m). |
| **Minimap and waypoint arrow** | A live minimap in the corner and a redesigned 3D arrow that points at your current target, with distance and height difference. |
| **Pet farm list** | <kbd>Ctrl</kbd>+<kbd>F5</kbd> shows the pets you are farming with live souls. Pick them by type and map, click one for a ping, the arrow and the nearest teleporter, and the next closest pet is guided when one is maxed. |
| **Keybinds** | The map's *Keybinds* button lists every shortcut. Click one, press the new keys and it is rebound; a circular arrow restores the default. The map opens with <kbd>Right Shift</kbd>+<kbd>M</kbd> by default. |
| **Widgets** | The map's *Widgets* button lets you move every widget on a grid with magnetic centre lines, resize any of them with the mouse wheel, switch each one on or off, and save. Click-through mode keeps the overlay out of your way. |
| **Game news** | Patch notes, events and maintenance without leaving the game, with how long ago each was posted. |
| **Map shortcuts** | Update, changelog, GitHub and issues buttons sit at the bottom right of the map. |
| **Map button** | A small round button with the app icon floats over the game: click it to open or close the map, drag it anywhere. It hides while a game menu is open. |
| **Starts by itself** | Install it once. It starts with Windows, waits quietly in the tray and is ready the moment AION 2 opens. |
| **Stays running** | Runs as administrator without a manual step, and restarts itself if it ever crashes while the game is still open. |
| **Auto-update** | New versions are downloaded in the background and verified with a digital signature before they are applied. |

### Move and resize your widgets

<img src="docs/widgets_resize.gif" alt="Press Widgets on the map, drag a widget to move it and scroll the mouse wheel over it to resize it" width="100%">

Idea and thanks to **Ennz729** for the resize feature.

## Screenshots

<table>
<tr>
<td width="50%"><img src="docs/02_map.png" alt="Interactive map"><br><sub><b>Interactive map</b>: every boss, portal and chest.</sub></td>
<td width="50%"><img src="docs/03_reshanta.png" alt="Reshanta"><br><sub><b>Altgard, Reshanta and Verteron</b>, a click apart.</sub></td>
</tr>
<tr>
<td width="50%"><img src="docs/04_markers.png" alt="Marker cards"><br><sub><b>Marker cards</b>: found, guide arrow, add to route.</sub></td>
<td width="50%"><img src="docs/05_filters.png" alt="Filters"><br><sub><b>Filters</b> with found counters.</sub></td>
</tr>
<tr>
<td width="50%"><img src="docs/06_route.png" alt="Routes"><br><sub><b>Routes</b> planned in seconds.</sub></td>
<td width="50%"><img src="docs/07_news.png" alt="News"><br><sub><b>Game news</b> without alt-tabbing.</sub></td>
</tr>
<tr>
<td width="50%"><img src="docs/08_bosses.png" alt="Boss timers"><br><sub><b>Boss timers</b> shared by your server.</sub></td>
<td width="50%"><img src="docs/09_bossalerts.png" alt="Boss alerts"><br><sub><b>Boss alerts</b> and the flagged-boss widget.</sub></td>
</tr>
<tr>
<td width="50%"><img src="docs/10_dps.png" alt="DPS meter"><br><sub><b>Live DPS meter</b> with target health.</sub></td>
<td width="50%"><img src="docs/11_party.png" alt="Party check"><br><sub><b>Party check</b> before the dungeon.</sub></td>
</tr>
<tr>
<td width="50%"><img src="docs/12_timers.png" alt="Timers"><br><sub><b>Event timers</b> with CPU / GPU load.</sub></td>
<td width="50%"><img src="docs/13_hud.png" alt="Minimap"><br><sub><b>Minimap</b> and waypoint arrow.</sub></td>
</tr>
<tr>
<td width="50%"><img src="docs/14_arrow.png" alt="Waypoint arrow"><br><sub><b>New 3D arrow</b> with distance and height.</sub></td>
<td width="50%"><img src="docs/15_petfarm.png" alt="Pet farm list"><br><sub><b>Pet farm list</b> with guided farming.</sub></td>
</tr>
<tr>
<td width="50%"><img src="docs/16_widgets.png" alt="Widgets"><br><sub><b>Widgets</b>: place every widget.</sub></td>
<td width="50%"><img src="docs/17_keybinds.png" alt="Keybinds"><br><sub><b>Keybinds</b>: change every shortcut.</sub></td>
</tr>
<tr>
<td width="50%"><img src="docs/18_sounds.png" alt="Sounds"><br><sub><b>Sounds</b>: pick the sound of every alert.</sub></td>
<td width="50%"><img src="docs/19_tour.png" alt="Guided tour"><br><sub><b>Guided tour</b> on first run.</sub></td>
</tr>
<tr>
<td width="50%"><img src="docs/21_help.png" alt="Built-in help"><br><sub><b>Built-in help</b> on the map.</sub></td>
<td width="50%"><img src="docs/22_install.png" alt="Install"><br><sub><b>One installer</b>, always the latest version.</sub></td>
</tr>
<tr>
<td width="50%"><img src="docs/23_autostart.png" alt="Automatic start"><br><sub><b>Starts by itself</b> when you play.</sub></td>
<td width="50%"></td>
</tr>
</table>

## Install

<div align="center">
<a href="https://github.com/CrackedNamless/Aion2-QoL/releases/latest/download/Aion2-QoL-Setup.exe"><img src="docs/download.png" alt="Download installer" width="380"></a>
</div>

1. Download **Aion2-QoL-Setup.exe** with the button above and run it.
2. The installer downloads the **latest release** from GitHub, checks its digital signature and installs it. It is a small file because it always fetches the newest version, so this is the only installer you will ever need. The first install downloads about 190 MB (maps and icons).
3. It installs [Npcap](https://npcap.com) for the DPS meter if you do not have it, and sets Aion2-QoL to **start by itself** with Windows. It runs silently in the system tray and picks up AION 2 as soon as the game opens, so there is nothing to launch before you play.
4. Start AION 2 and press <kbd>Right Shift</kbd>+<kbd>M</kbd>. A guided tour of the map, party check, timers and DPS meter opens the first time (replay it from <kbd>F1</kbd>).

**Requirements:** Windows 10 or 11 (64-bit), AION 2 running in borderless or windowed mode so the overlay can draw above it.

**Uninstall:** *Settings > Apps*. Your settings live in the install folder and are removed with it.

## Shortcuts

Global hotkeys work in game. Map keys work while the map is open, and <kbd>F1</kbd> on the map shows this list. All of them can be rebound from the *Keybinds* button on the map toolbar.

| Key | Action | | Key | Action |
|---|---|---|---|---|
| <kbd>Right Shift</kbd>+<kbd>M</kbd> | Open or close the map | | <kbd>Scroll</kbd> | Zoom |
| <kbd>Ctrl</kbd>+<kbd>F11</kbd> | Skip route stop | | <kbd>Drag</kbd> | Pan the map |
| <kbd>Ctrl</kbd>+<kbd>F5</kbd> | Pet farm list | | <kbd>Click</kbd> | Select a marker |
| <kbd>Ctrl</kbd>+<kbd>F6</kbd> | Minimap | | <kbd>P</kbd> | Pets card |
| <kbd>Ctrl</kbd>+<kbd>F7</kbd> | DPS meter | | <kbd>F</kbd> | Mark as found |
| <kbd>Ctrl</kbd>+<kbd>F8</kbd> | Event timers | | <kbd>H</kbd> | Hide found markers |
| <kbd>Ctrl</kbd>+<kbd>F9</kbd> | Hidden Cube finder | | <kbd>G</kbd> | Guide arrow to the selection |
| <kbd>Ctrl</kbd>+<kbd>F10</kbd> | Click-through mode | | <kbd>L</kbd> | Follow the player |
| <kbd>Ctrl</kbd>+<kbd>F12</kbd> | Boss timers | | <kbd>R</kbd> / <kbd>O</kbd> | Add route stop / route planner |
| <kbd>F1</kbd> | Help and shortcuts | | <kbd>N</kbd> | News |
| <kbd>Tab</kbd> | Next zone | | <kbd>K</kbd> | Bosses card |
| <kbd>B</kbd> | Side panel | | Right-click | Fit the map to the screen |

<div align="center"><img src="docs/19_hotkeys.png" alt="Shortcuts" width="80%"></div>

## Updates

Aion2-QoL checks GitHub for a new release when it starts. If one exists it downloads only the parts that changed, verifies them against the signed manifest and applies them. Nothing is installed from a release whose signature does not match the key built into the program. Release notes for every version are on the [Releases](https://github.com/CrackedNamless/Aion2-QoL/releases) page.

## Privacy and safety

- **DPS meter:** reads your own network traffic through Npcap (packet capture). It does not touch the game process.
- **Player position and minimap:** read from the game's memory in read-only mode. Nothing is injected into the game and no input is sent to it.
- **Map, routes, news:** local data shipped with the program and refreshed through updates.
- **Online heights and boss timers:** anonymous and crowd-sourced: terrain heights that place the player more precisely, and boss respawn times shared between players of the same server. No account, no personal data.
- **Updates:** every package is checked against an ECDSA signature whose public key is built into the program, so a tampered update is rejected.
- **Windows warnings:** the installer and the program are not signed with a paid certificate, so Windows may show a SmartScreen or "unknown publisher" prompt the first time. This is expected for a small independent project: choose *More info > Run anyway*.

Aion2-QoL is a fan-made tool and is **not affiliated with NCSOFT**. AION is a trademark of its respective owners. Third-party tools can be restricted by a game's rules: use it at your own risk.

## Troubleshooting

| Problem | What to do |
|---|---|
| The overlay does not appear | Run AION 2 in borderless or windowed mode, then press <kbd>Right Shift</kbd>+<kbd>M</kbd>. Check that the Aion2-QoL icon is in the system tray. |
| The DPS meter shows nothing | Make sure Npcap is installed (the installer offers it) and that you are in a fight. Press <kbd>Ctrl</kbd>+<kbd>F7</kbd> to toggle it. |
| The overlay blocks my mouse | Press <kbd>Ctrl</kbd>+<kbd>F10</kbd> for click-through mode. |
| A widget is in the wrong place | Open the map, press *Widgets*, drag it where you want, then Save. |
| Windows shows a SmartScreen warning | Choose *More info > Run anyway*, see [Privacy and safety](#privacy-and-safety). |

Still stuck? Open an [issue](https://github.com/CrackedNamless/Aion2-QoL/issues/new/choose) and describe what you see.

## FAQ

**Is it free?** Yes.

**Do I have to start it every time?** No. It starts with Windows and attaches to AION 2 on its own. To quit it use the tray icon.

**Do I need to download a new installer after each update?** No. The program updates itself and the installer always fetches the newest release.

**How do I turn the party check off?** Open the map, click *Party QoL* in the toolbar and switch *Party check* off. It then stays disabled until you switch it on again.

**Where do I report a problem or suggest something?** Open an [issue](https://github.com/CrackedNamless/Aion2-QoL/issues/new/choose). Bug reports and feature requests each have a short form.

## License

Aion2-QoL is free to use but closed source. See [LICENSE](LICENSE) for the terms.

---

<div align="center"><sub>Made by <b>CrackedNamless</b></sub></div>
