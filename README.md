# DrawTimer

A single-file art reference timer. Drop a folder of images, set rounds and time per round, and draw against a shuffled sequence of references.

## Run

Open `index.html` in a browser.

## Notes

- Folder drag-drop uses the standard `webkitGetAsEntry` API. Some browsers (e.g. Brave with Shields) block this; use the "choose a folder" picker instead.
- Settings (rounds, time per round, sound) persist in `localStorage`, but images are never persisted.
- Keyboard during a session: Space = pause, ←/→ = prev/next, Esc = stop.
