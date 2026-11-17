# Maze Escaper

A browser maze game. Each level is a square, rectangle, triangle, circle, pentagon, hexagon or star maze, and you only see a 4×4 window of it. Mazes grow from 20×20 to 25×25 to 30×30 as you go, and the last maze of a run is 40×40.

## Controls
- **PC:** WASD or the arrow keys to move · H for a hint (Y to confirm) · Esc to pause
- **Phone:** drag the compass joystick (or switch to a D-pad in Settings) · red button = hint · blue button = pause
- **Settings → Hand:** your dominant hand gets the joystick
- **Bottom-left icons:** ♪ turns music on/off · ⤨ skips to a random song (this never changes the maze)

## Changing the music
1. Put your audio files (.mp3, .ogg, .wav or .m4a) in the `music` folder.
2. Open `music/playlist.js` and add a line for each song, e.g. `{ file: "my-song.mp3", title: "My Song" },`
3. Delete the lines (and files) of songs you no longer want.

Songs play in shuffled order.

## Hosting on GitHub Pages
Upload `index.html`, this README and the whole `music` folder. Then go to **Settings → Pages**, choose **Deploy from a branch**, and pick `main` and `/ (root)`.
