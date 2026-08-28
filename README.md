# Holytown Colts Playbook — Responsive Edition

A standalone football tactics board designed to work on mobile phones, tablets, laptops and desktop computers.

## Files to upload

For a fresh GitHub Pages installation, rename and upload these files to the **root** of the repository:

| Downloaded file | Rename to in GitHub | Purpose |
|---|---|---|
| `index-responsive-tactics-board.html` | `index.html` | The complete tactics-board application |
| `manifest-responsive-tactics-board.json` | `manifest.json` | Progressive Web App configuration |
| Your existing club icon | `icon.png` | 512 × 512 PNG app icon |
| This README file | `README.md` | Optional project documentation |

## GitHub Pages setup

1. Create a new repository, or open the repository you want to replace.
2. Upload `index.html`, `manifest.json`, and `icon.png` to the repository root.
3. Commit the changes to the `main` branch.
4. Go to **Settings** → **Pages**.
5. Select **Deploy from a branch**.
6. Choose branch `main` and folder `/ (root)`.
7. Save the setting and wait for the site to deploy.

## Responsive use

- **Desktop:** left and right tool panels remain visible.
- **Tablet:** the board scales to the available screen space; use the normal touch controls.
- **Mobile:** a compact action toolbar appears at the top of the pitch, with the most important add, draw, undo and redo controls.
- Icons use pointer/touch drag handling and can be moved on any supported screen size.
- Object and drawing positions are stored as percentages of pitch width and height, so drills scale across devices.

## Marker and player tools

- Add player icons in red, yellow, blue, pink or purple.
- Add a **green goalkeeper**, which remains visually distinct from outfield players.
- Add flat circular markers in red, yellow, blue, pink or purple.
- Add a smaller black-and-white football marker styled as a traditional pentagon/hexagon-panel ball.
- Select an item to change its type, colour, label, name or shirt number.
- Drag every player, marker and football around the pitch.

## Drawing tools

### Freehand line

1. Choose **Freehand line**.
2. Select the line colour, style (solid or dashed), and thickness in the right panel.
3. Drag across the pitch to draw.

### Arrow

1. Choose **Arrow**.
2. Select the desired colour, solid/dashed style, and thickness.
3. Drag from the start point to the destination.

Arrows retain the chosen colour and line style, including the arrowhead colour. Use **Clear drawings** to remove all freehand lines and arrows without moving players or markers.

## Formation presets

### 11 v 11

- 4-3-3
- 4-4-2
- 4-2-3-1
- 3-5-2

### 9 v 9

- 3-3-2
- 3-2-3
- 2-4-2

Choose the team size, formation, and outfield shirt colour, then select **Apply formation**. The goalkeeper is added in green automatically. Applying a formation replaces players in the selected shirt colour and green goalkeeper; other coloured players, markers and the football remain in place.

## Saving and sharing

- **Save:** stores the named drill in browser storage on the current device.
- **Load:** opens a saved drill from the current device.
- **JSON:** downloads a portable backup/share file.
- **Import:** restores a previously exported drill JSON file.

Browser saves are local to the device and browser. Export JSON files when you need to back up drills or move them between devices.

## Keyboard shortcuts

| Action | Shortcut |
|---|---|
| Undo | `Ctrl` / `Cmd` + `Z` |
| Redo | `Ctrl` / `Cmd` + `Y`, or `Ctrl` / `Cmd` + `Shift` + `Z` |
| Delete selected item | `Delete` or `Backspace` |
| Leave drawing mode | `Escape` |
