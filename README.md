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
- **Per-status timers with sensible defaults** — each status remembers its own
  countdown length (Lunch 60 min, Break 15 min, Meeting/Be Right Back/Focus
  30 min). Edit the value while a status is active and it's saved for next time.
  The board counts down, shows your "back at" time, and keeps counting in red if
  you run over.
- **Done for the Day** uses a customizable **return time** instead of a countdown
  ("Back tomorrow at 8:00 AM").
- **One-tap presets** — Available, On Lunch, On Break, In a Meeting, Be Right
  Back, Focus Time, Done for Day.
- **Fullscreen** — one button enters and exits fullscreen (no need to know the
  F11 shortcut).
- **Remembers your status** across refreshes (via `localStorage`).
- **Focus mode** hides the controls for a clean display.
- **Installable PWA** — works offline and can be installed as an app (look for the
  install icon in your browser's address bar, then launch it in its own window).

## Installing as an app (PWA)

The install/offline features require the page to be served over **HTTPS** (or
`localhost`) — opening the file directly with `file://` won't register the
service worker. The easiest route is to enable **GitHub Pages** for this repo,
then visit the Pages URL and click **Install** in the address bar.

## Keyboard shortcuts

| Key       | Action                                  |
|-----------|-----------------------------------------|
| `1`–`7`   | Jump to the matching status preset      |
| `F`       | Toggle focus mode (hide the controls)   |
| `Esc`     | Clear the active timer                  |
