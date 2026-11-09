# Spin Wheel Studio

A customizable spin-the-wheel decision maker that installs like an app and works offline (PWA).

## Features
- Add, edit, recolor, shuffle and sort options
- Weighted slices (make some options more likely)
- Built-in presets plus your own saved presets
- Winner history, sound, haptics and confetti
- Dice Throw mode: D4, D6, D8, D10, D12 and D100, with any number of each (switch games from the top menu)
- Installable on Android, iOS and desktop

## Run it locally
Open `index.html` in a browser. (Offline install features need it served over `https://`, e.g. GitHub Pages.)

## Files
| File | Purpose |
|------|---------|
| `index.html` | The whole app (layout, styles, logic) |
| `sw.js` | Service worker for offline use |
| `manifest.webmanifest` | Install info (name, icons, colors) |
| `icon-192.png`, `icon-512.png` | App icons |

## Updating the app
After changing files, bump the `CACHE` version number at the top of `sw.js` (e.g. `v4` to `v5`) so installed copies refresh.
