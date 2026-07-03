# Bociany — Where Do the Storks Go?

An interactive, self-contained slide presentation about the migration of the white stork (*bocian biały*) — from the 1822 "Pfeilstorch" that solved the mystery of where birds go in winter, to the two great flyways over Gibraltar and the Bosphorus, and the modern storks that have stopped migrating altogether.

Everything lives in a single file: [`stork-migration.html`](stork-migration.html).

## Usage

Open `stork-migration.html` in any modern browser — no build step or server required:

```sh
# macOS
open stork-migration.html

# Linux
xdg-open stork-migration.html

# Windows
start stork-migration.html
```

An internet connection is needed for the web fonts (Google Fonts), the Leaflet library, and the map tiles on the routes slide. The presentation still works offline, but with fallback fonts and without the interactive map.

### Navigation

The deck has 12 slides. Move through them with the on-screen buttons, the keyboard, or touch:

| Input | Action |
| --- | --- |
| `→`, `Space`, `PageDown` | Next slide |
| `←`, `PageUp` | Previous slide |
| `Home` / `End` | Jump to first / last slide |
| `N` | Toggle the narrator panel (a spoken-word script for each slide) |
| `F` | Toggle fullscreen |
| Swipe left / right | Next / previous slide (touch devices) |

A progress bar along the top and a slide counter in the corner show where you are in the deck.

### The map slide

Slide 6 ("The routes") contains a live [Leaflet](https://leafletjs.com/) map of the two migration flyways. Drag to pan, and zoom with `+` / `−` or a double-click. Swipe gestures are disabled over the map so panning doesn't change slides — use the arrow keys or buttons there instead.

### Presenting

For a talk, press `F` for fullscreen and `N` to open the narrator panel, which carries a short script for each slide as you advance.
