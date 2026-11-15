# Bonk Bots

A 3D physics party game for the browser. Ball-shaped robots with wobbly, grabbing arms bonk each other around a set of minigames. One to four players (keyboard and controllers), with CPU bots filling the empty slots.

## Play

Open `index.html` in Chrome or Edge. It is a single self-contained file; the only thing it loads from the internet is the three.js 3D engine.

Opening the file directly (rather than inside another page) matters for controllers: browsers only pass controller input to a top-level page.

- `index.html` is version 2 (in progress).
- `v1/index.html` is the saved version 1.

## Minigames

| Game | Goal |
|---|---|
| Sumo | Knock everyone off the shrinking disc. |
| Goal Guard | Three balls, four nets. Every goal against you costs a life. |
| Hill Top | Hold the glowing zone on the hilltop the longest. |
| Junk Tower | Climb the falling shapes and stay out of the lava. |
| Marble Run | Three laps of a twisty sky track with boosts and jumps. |
| Ice Box | A slippery rink walled with breakable ice blocks. |
| Clockwork | Two sweeping clock hands on an open disc. |
| The Drain | Solid walls and a bot-sized hole in the middle. |

Bonk Party plays the games back to back and crowns a champion on points.

## Controls

| Action | Keyboard and mouse | Controller |
|---|---|---|
| Roll | WASD / arrows | Left stick |
| Dash | Space | A |
| Jump | C or X | B |
| Left arm (hold to grip) | Q or left click | LB / LT |
| Right arm (hold to grip) | E or right click | RB / RT |
| Lift what you hold | F or Shift | Right stick, or X / Y |
| Throw | Let go of the arm while lifting | Same |
| Pause | P | Start |

Grip a block, wall or ledge and lift to climb. Mash dash to break free when someone is holding you.

## Items and powerups

Items drop from the sky and are picked up by grabbing them: sledgehammer, TNT, electric fan, black hole bomb, oil can, uzi, hookshot, flamethrower and laser.

Powerups are collected by rolling into them: Big, Long Arms and Super Jump.
