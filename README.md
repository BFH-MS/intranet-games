# intranet-games

Minigames for the intranet, mainly for the yearly advent calendar. Each game is plain HTML, CSS and JavaScript and runs without a build step. The games are grouped by the year they were first used.

They are published with GitHub Pages and embedded in SharePoint with the web part from [BFH-MS/spfx-games](https://github.com/BFH-MS/spfx-games).

## Games

Base address: `https://bfh-ms.github.io/intranet-games/`

| Year | Game | Path | Sends score to the web part |
| --- | --- | --- | --- |
| 2026 | Reindeer Flight (Rentier-Flug) | `2026/rentier-flug.html` | yes |
| 2026 | Elf Prank (Wichtel-Streich) | `2026/wichtel-streich.html` | yes |
| 2026 | Cookie Ninja (Guetzli-Ninja) | `2026/guetzli-ninja.html` | yes |
| 2026 | Gift Tower (Geschenke-Turm) | `2026/geschenke-turm.html` | yes |
| 2026 (Easter) | Easter Egg Toss | `2026/easter-egg-toss.html` | yes |
| 2025 | Flappy BFH | `2025/flappy-bfh.html` | no |
| 2025 | Santa Crossing | `2025/santa-crossing.html` | no |
| 2024 | Doodle Jump | `2024/doodle-jump/` | yes |
| 2024 | Memory | `2024/memory/` | yes |
| 2024 | Breakout | `2024/breakout/` | yes |
| 2024 | Pacman | `2024/pacman/` | yes |
| 2023 | Snake | `2023/snake/` | no |
| 2023 | Tetris | `2023/tetris/` | no |

## Adding or updating a game

1. Put the HTML file (or a folder with an `index.html`) into the folder of the year.
2. Commit to `main`. GitHub Pages publishes the change after one to two minutes.
3. Enter the address of the game in the web part on the SharePoint page.
