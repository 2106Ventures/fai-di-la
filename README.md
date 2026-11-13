# Pak Darky Races

A first-person downhill skateboarding game: a 5.4 km run from the Peak to the Star Ferry pier through 1990s Hong Kong Island. Single-page browser game, playable offline.

## Play
Open the GitHub Pages address for this repo in a browser.

## Controls
| | On the road | In the air |
|---|---|---|
| Left / Right (A / D) | Carve | Barrel roll |
| Up (W) | Push for speed | Flip trick |
| Down (S) | Powerslide | Hold to grab |
| Space | Ollie; boosts a ramp launch | Late pop |

Touch: drag to carve, tap to ollie or flip, flick in the air to roll or grab. `M` cycles sound, music off, mute.

Ollie onto rails and kerbs to grind. Red-and-white pills restore a life (up to five).

## Install on iPhone for offline play
1. Open the Pages address in Safari while online.
2. Tap Share, then "Add to Home Screen".
3. Launch it once from the new icon while still online. After that it works without a connection.

## Files
- `index.html` - the whole game (three.js r128, MIT licence, and fonts are bundled inside)
- `sw.js` - offline cache; bump `CACHE` when the game changes
- `manifest.webmanifest`, `icon-*.png` - home-screen app details
