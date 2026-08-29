# Holytown Colts Playbook

A complete, dependency-free football tactics board for desktop, tablet and mobile browsers, built to run on GitHub Pages.

## Files in this set

| File | Upload as | Purpose |
|---|---|---|
| `index.html` | `index.html` | The full tactics-board application |
| `manifest.json` | `manifest.json` | Progressive Web App metadata |
| This guide | `README.md` | Optional documentation |

You also need a square icon saved as **`icon.png`** (512 × 512) in the same repository root, referenced by the manifest. Reuse your existing club icon if you have one.

## Clean installation

1. In your repository root, remove any old `index.html` and `manifest.json`.
2. Upload the new `index.html`, `manifest.json`, and `icon.png`.
3. Commit to the `main` branch.
4. Open **Settings** → **Pages**.
5. Set **Deploy from a branch**, branch `main`, folder `/ (root)`.
6. Save and wait for GitHub Pages to redeploy.
7. Hard-refresh your browser to clear any cached older version:
   - Windows/Linux: `Ctrl + F5`
   - macOS: `Cmd + Shift + R`
   - Mobile: fully close and reopen the browser tab.

## Pitch

- **Full pitch**: shows a halfway line, both penalty areas, both six-yard boxes, and a centre circle positioned with `top: 35%` and its centre spot at `top: 49%`, matching your confirmed correct layout.
- **Attacking half**: shows only the attacking goal, penalty area, six-yard box, and penalty spot, with no centre circle, for finishing and final-third drills.

Switch between them from the **Pitch view** panel (desktop) or the **Pitch** menu (mobile).

## Pieces

All pieces are draggable using mouse, trackpad, touchscreen, or stylus:

- Outfield players: red, yellow, blue, pink, purple.
- Goalkeeper: green, always distinct from outfield colours.
- Flat markers: red, yellow, blue, pink, purple.
- A small black-and-white panelled football icon.

Select a piece to rename it, assign a shirt number, or change its colour/type. Use **Delete** to remove it and **Duplicate** to copy it nearby.

## Drawing

Two drawing tools are available:

- **Freehand line** — for curved runs, pressing triggers, or zones.
- **Arrow** — for direct passing or movement lines with an arrowhead.

Before drawing, set the colour (white, yellow, red, blue, pink, purple, or black), style (solid or dashed), and thickness (thin, medium, thick). Selecting a piece automatically exits drawing mode so it does not interfere with dragging.

## Formations

| Team size | Formations |
|---|---|
| 9 v 9 | 3-3-2, 3-2-3, 2-4-2 |
| 11 v 11 | 4-3-3, 4-4-2, 4-2-3-1, 3-5-2 |

Pick a team size, formation, and outfield shirt colour, then select **Apply formation**. The goalkeeper is always placed in green automatically.

## Mobile layout

On screens under 900px wide, the side panels are replaced with a compact top toolbar:

- **Pieces** — add players, the goalkeeper, markers, and the football.
- **Draw** — freehand/arrow tools and line styling.
- **Pitch** — pitch view and formation controls.
- **Options** — piece editing, notes, save/load, export/import, recording, and presentation mode.

Tapping a menu opens a bottom sheet; use the `×` button to close it and free up pitch space.

## Recording drills

- **Desktop (Chrome, Edge, Firefox)**: the **Record + audio** button uses the browser's screen-sharing API to capture the tab or screen, plus optional microphone narration, and downloads a `.webm` video when stopped.
- **Mobile (Android or iPhone)**: browsers do not support in-page screen recording. Tapping **Record + audio** now shows a clear on-screen guide instructing the coach to use their phone's native screen recorder (Quick Settings → Screen Record) with microphone audio enabled, then dismiss the message with **Got it**.

## Saving and sharing drills

- **Save** stores up to 40 named drills in the browser's local storage on the current device.
- **Load** retrieves a previously saved local drill.
- **JSON** exports the current drill as a downloadable file.
- **Import** restores a drill from a previously exported JSON file.

Local saves do not sync between devices or browsers — use JSON export/import to transfer or back up drills.

## Presentation mode

Selecting the **⛶** button hides all editing controls and expands the pitch to fill the screen for presenting to players or parents. A **Back to board** button appears in the top-left corner, and pressing `Escape` also exits presentation mode.

## Keyboard shortcuts

| Action | Shortcut |
|---|---|
| Undo | `Ctrl` / `Cmd` + `Z` |
| Redo | `Ctrl` / `Cmd` + `Y`, or `Ctrl` / `Cmd` + `Shift` + `Z` |
| Delete selected piece | `Delete` or `Backspace` |
| Exit drawing mode, presentation mode, notice, or mobile menu | `Escape` |
