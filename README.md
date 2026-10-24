# Degrees of Lewdity 0.5.13.5 — localStorage copy/paste mode

Modified version of Degrees of Lewdity that treats localStorage as a temporary copy/paste method and keeps the game playable on older browsers without IndexedDB.

## Changes
- Save-list condition requires `window.indexedDB`. Browsers without it fall back to localStorage.
- Fallback path is marked as localStorage / copy-paste mode.
- Warning text updated: localStorage saves are temporary; use Export / Copy Text Area to back up the save string.
- Tooltip updated to explain the copy/paste workflow for older browsers.
- Extra tip added after the warning.

## Usage
1. Open the HTML file (with the `img` folder alongside it).
2. On any browser, use the save menu → Export / Copy Text Area to copy your save string.
3. Paste it back later via the import / load-from-text controls.
4. Older browsers automatically use the localStorage path.

## Files
- `Degrees of Lewdity 0.5.13.5.html` — modified game file
- `img/` — game images (from original package)

**Note:** This is a personal modification of an existing game for local use. Respect the original authors.
