# Neon Stack Daily

A one-file browser stacking game. A block slides back and forth — tap (or press
space) to drop it. Whatever hangs over the edge falls away, perfect drops build
combos and grow your tower back, and every day is a slightly different game.

**Play it:** open `index.html` in any browser, or the live site on GitHub Pages.

## How it plays

- **Daily by design** — the date seeds the day's colours and speed, so
  everyone's tower today is the same shade of hard.
- **Daily goal** — reach 30 points to complete the day.
- **Streaks** — play on consecutive days to grow your 🔥 streak.
- **Unlockable themes** — Neon, Sunset, Ocean, Aurora and Gold unlock at
  3, 7, 14 and 30-day streaks.
- **Combos** — perfect drops stack a multiplier and play a rising pentatonic
  note; at a ×3 combo your block starts growing back.
- Your bests, streak and theme live in your browser (localStorage). No
  accounts, no tracking, no server.

## Tech

- A single `index.html` (~13 KB): HTML, CSS and vanilla JavaScript on a
  `<canvas>`. Zero dependencies, zero network calls.
- Delta-time game loop, WebAudio sound, vibration on mobile, guarded
  localStorage saves.

## Day rollover

The date is re-checked every time a run starts, so playing across midnight
in the same open tab rolls cleanly into the new day — new seed, fresh daily
goal, streak judged against the real date.

## Credits

Directed and published by **Mohamed Idris**.
Built with **Claude** (Anthropic). Reviewed and play-tested by **Haven**
(Muse) — judged 8.8/10.
