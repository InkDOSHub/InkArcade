# InkArcade roadmap

InkArcade plays the user's own retro games in the browser with EmulatorJS and touch controls.

Written on 2026-11-20 during the InkOS autopilot run. Ordered by priority; nothing here is started unless marked.

## Now

- Adopt the InkOS postMessage protocol v1 (`docs/PROTOCOL.md`): theme via `ink-tema`, files via `inkos-vfs-file` (`inkos:file` event from the Hub's `assets/tema.js`).
- Validate parent origin against the InkOS allowlist before acting on any message.
- License review: EmulatorJS (GPL-3.0) and libretro cores ship in `ejs/` next to MIT code; keep them as a separate, clearly licensed artifact (flagged in THIRD_PARTY_LICENSES.md).

## Next

- Test on iPhone 17 Pro Max and iPad 11" (A16), iOS 27 Safari, and record results.
- Keep third-party components listed in `THIRD_PARTY_LICENSES.md` up to date.

## Not planned in this round

- Large new features. This file only records direction; see the README for the current state.
