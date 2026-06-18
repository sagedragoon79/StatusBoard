# Status Board

A stylish, single-file browser status board you can put up on a spare monitor so
coworkers can tell at a glance whether you're **available**, **on lunch**, **on
break**, **in a meeting**, and so on — with an optional countdown showing when
you'll be back.

## Use it

Just open `index.html` in any modern browser. No build step, no dependencies,
no server.

Tip: put it fullscreen (⛶ button) on a second monitor for maximum glance-ability.

## Features

- **Big, glanceable status** — emoji + label readable across the room, with the
  whole board tinted to match the status color.
- **Return timer** — set a number of minutes and the board counts down and shows
  your "back at" time. It keeps counting (in red) if you run over.
- **One-tap presets** — Available, On Lunch, On Break, In a Meeting, Be Right
  Back, Focus Time, Done for Day.
- **Remembers your status** across refreshes (via `localStorage`).
- **Focus mode** hides the controls for a clean display.

## Keyboard shortcuts

| Key       | Action                                  |
|-----------|-----------------------------------------|
| `1`–`7`   | Jump to the matching status preset      |
| `F`       | Toggle focus mode (hide the controls)   |
| `Esc`     | Clear the active timer                  |
