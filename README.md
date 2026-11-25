# TI4 Table Companion

A fan-made table companion for Twilight Imperium 4th Edition (with Prophecy of Kings).
Not affiliated with Fantasy Flight Games or Asmodee.

## Files
- `index.html` – the whole app
- `manifest.webmanifest` – app name, colors and icons for "Add to Home Screen"
- `sw.js` – offline support (saves the app, icons and fonts on the device)
- `icons/` – home screen and install icons

## Updating
Replace `index.html` with the new version (Add file → Upload files → Commit).
Phones pick up the new version the next time the app is opened online.
If you ever change the icons or the manifest, also change the version in the first lines of `sw.js`
(e.g. `ti4-companion-v1` → `ti4-companion-v2`) so devices refresh their saved copies.
