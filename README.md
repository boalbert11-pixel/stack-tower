# Stack Tower

A one-tap stacking game in a single HTML file. Drop each sliding block onto the tower; whatever hangs over the edge gets sliced off, so the tower narrows until you miss.

## Play

Open `index.html` in any modern browser. There's no build step and no dependencies.

## Controls

| Action     | Input                                   |
| ---------- | --------------------------------------- |
| Drop block | Tap / click, <kbd>Space</kbd>, <kbd>Enter</kbd>, or <kbd>↓</kbd> |
| Mute sound | <kbd>M</kbd> or the speaker button      |

## Scoring

- Each block you land scores one point.
- A near-perfect drop snaps into place with no width lost and plays a note; chained perfects climb a pentatonic scale.
- Three or more perfects in a row grow the block back a little.
- The slider speeds up as your score rises.

Your best score and mute setting are saved in the browser's `localStorage`.
