# Holytown Colts Playbook

A complete, dependency-free football tactics board for desktop, tablet and mobile browsers. It can be hosted directly on GitHub Pages.

## Fresh installation

Create a new GitHub repository, or remove/replace the old files in your existing repository. Upload the following to the **repository root**:

| File | Required name in GitHub | Purpose |
|---|---|---|
| Downloaded application file | `index.html` | The complete tactics board |
| Downloaded manifest file | `manifest.json` | Progressive Web App metadata |
| Club icon image | `icon.png` | A square 512 × 512 PNG application icon |
| This guide | `README.md` | Optional project documentation |

The application has no external libraries, CDNs, build step, database, API keys, or server-side files.

## GitHub Pages deployment

1. Commit `index.html`, `manifest.json`, and `icon.png` to the `main` branch.
2. In the repository, open **Settings** → **Pages**.
3. Under **Build and deployment**, select **Deploy from a branch**.
4. Select branch `main` and folder `/ (root)`.
5. Save. GitHub will show the published Pages address after deployment.
6. If an old version remains visible after replacing `index.html`, force-refresh the browser:
   - Windows/Linux: `Ctrl + F5`
   - macOS: `Cmd + Shift + R`
   - Mobile: close the tab fully and reopen the Pages URL.

## Pitch views

### Full pitch

The full pitch includes a halfway line and a centre circle positioned in the actual centre of the pitch:

- Centre circle: 18% of the pitch width.
- Circle left edge: 41% of pitch width.
- Circle top edge: 41% of pitch height.
- Circle centre: 50% horizontal and 50% vertical.

### Attacking half

The half-pitch option shows the attacking goal, penalty area, six-yard box, and penalty spot. The centre circle is intentionally not drawn in the half-pitch layout so it cannot overlap the penalty area.

## Pieces

All pieces are draggable with mouse, touch, stylus, or trackpad:

- Outfield players: red, yellow, blue, pink, and purple.
- Goalkeeper: green.
- Flat markers: red, yellow, blue, pink, and purple.
- Small black-and-white football marker.

Select any piece to edit its label, number, or type. Use **Delete** to remove a selected piece and **Duplicate** to create an offset copy.

## Drawing

Use either drawing tool:

- **Freehand line**: draw a curved or freeform tactical line.
- **Arrow**: draw a straight directional arrow.

Before drawing, choose the line colour, solid/dashed style, and thickness. The arrowhead uses the selected colour. Select a piece to leave drawing mode and move it.

## Formations

### 11 v 11

- 4-3-3
- 4-4-2
- 4-2-3-1
- 3-5-2

### 9 v 9

- 3-3-2
- 3-2-3
- 2-4-2

Select a formation and the outfield-player colour, then choose **Apply formation**. The goalkeeper is always placed as a green marker.

## Mobile use

On screens below 900px wide, the side panels become a compact toolbar:

- **Pieces** opens a collapsible menu to add players, markers, and the ball.
- **Draw** opens drawing controls.
- **Pitch** opens full/half pitch and formation controls.
- **Options** opens selected-piece editing, notes, export/import, recording, and presentation controls.

Tap the `×` button at the top of the menu to close it and create more pitch space.

## Saving and sharing

- **Save** stores up to 40 named drills in this browser on this device.
- **Load** retrieves a saved local drill.
- **JSON** downloads a portable drill backup.
- **Import** restores a downloaded JSON drill file.

Local browser storage is not shared between devices. Export the JSON file to back up or move a drill.

## Presentation and recording

- **Presentation mode** hides editing controls and shows a visible **Back to board** button in the top-left corner.
- **Record + audio** asks the browser to share the current screen/tab and, where permitted, access the microphone for spoken coaching narration.
- Stop recording using the button in the app or the browser’s screen-share controls. The recording downloads as a WebM video file.

For the cleanest recording, choose the current browser tab in the browser’s screen-sharing picker and enable its audio option if you need tab audio. Browser and mobile operating-system restrictions may limit screen recording or audio capture on some devices.

## Keyboard shortcuts

| Action | Shortcut |
|---|---|
| Undo | `Ctrl` / `Cmd` + `Z` |
| Redo | `Ctrl` / `Cmd` + `Y`, or `Ctrl` / `Cmd` + `Shift` + `Z` |
| Delete selected piece | `Delete` or `Backspace` |
| Exit drawing mode, presentation mode, or a mobile menu | `Escape` |
