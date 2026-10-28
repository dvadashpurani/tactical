# Tactics studio

A 3D football tactics board that runs in the browser. Move players and the ball, build plays step by step, switch camera angles, and play the moves back as an animation.

## Run it

It's a single HTML file with no build step.

- **Locally:** open `index.html` in a browser (Chrome, Edge, Firefox or Safari). It needs an internet connection the first time, to load three.js and the fonts from a CDN.
- **GitHub Pages:** push this folder to a repo, then go to Settings → Pages, choose "Deploy from a branch", pick `main` and `/ (root)`, and save. The board will be live at `https://<your-username>.github.io/<repo-name>/`.

## Controls

| Action | How |
| --- | --- |
| Move a player or the ball | Drag it |
| Rotate the camera | Drag the pitch |
| Slide the camera | Right-drag or Shift-drag |
| Zoom | Scroll or pinch |
| Camera presets | Keys 1–5 |
| Play / pause | Space |
| Previous / next step | Arrow keys |
| Add a step | N |
| Hide the panels for recording | H |

## Features

- Plays library with kick-off, corner kick and free kick templates
- Steps per play, with dashed run arrows and pass arrows between steps
- Add or remove players (up to 18 per team, extras go to the bench)
- Team names, colours, formations and badges
- Player photos, names and numbers (upload one at a time, in bulk, or drop an image onto a player)
- Everything is saved in the browser's local storage

## Note on lineup import

The "Import a lineup" screenshot feature uses Claude's in-page runtime, so it only works when the page is opened as an artifact on claude.ai. Everywhere else the rest of the board works normally and the import section shows that it's unavailable.

## Built with

- [three.js r128](https://threejs.org/) for the 3D scene
- Barlow and Barlow Condensed from Google Fonts
