# Holytown Colts Playbook

A single-file football tactics board for planning, presenting, saving and sharing coaching drills.

## Fresh-install files

Upload these files to the root of a GitHub repository:

- `index.html` — the complete application
- `manifest.json` — Progressive Web App metadata
- `icon.png` — app icon (use the existing club icon from the previous repository, or add your own 512 × 512 PNG with this exact filename)

## GitHub Pages deployment

1. Create a new GitHub repository or open the repository you want to use.
2. Upload `index.html`, `manifest.json`, and `icon.png` to the repository root — not inside another folder.
3. Commit the files to the `main` branch.
4. In GitHub, open **Settings** → **Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Select the `main` branch and the `/ (root)` folder, then save.
7. Wait for Pages to deploy. GitHub will display the published site address in the Pages settings screen.

## Features

- Add red players, blue players, balls and cones
- Drag objects around a responsive football pitch
- Add player labels and shirt numbers
- Select, duplicate and delete markers
- Draw movement or passing arrows
- Use undo and redo controls
- Apply red-team formation layouts: 4-3-3, 4-4-2, 4-2-3-1 and 3-5-2
- Write coaching notes
- Save up to 40 named drills in browser storage
- Export and import drills as JSON files
- Use presentation mode for a clean full-screen tactics board
- Mobile-friendly controls for phones and tablets

## Keyboard controls

| Action | Keyboard control |
|---|---|
| Undo | `Ctrl` / `Cmd` + `Z` |
| Redo | `Ctrl` / `Cmd` + `Y`, or `Ctrl` / `Cmd` + `Shift` + `Z` |
| Delete selected object | `Delete` or `Backspace` |
| Exit draw mode | `Escape` |

## Saving drills

The **Save** button stores a named drill in the current browser on the current device. To retain a backup or share a drill with another device, use **JSON** to export a copy and **Import** to restore it.

## Notes

No installation, accounts, database, framework, or build process are required. The application runs directly in a modern web browser and can be hosted using GitHub Pages.
