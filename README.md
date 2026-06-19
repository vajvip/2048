# 2048

A lightweight browser implementation of the classic `2048` puzzle game using only HTML, CSS, and JavaScript.

## Demo
Open `index.html` in your browser to play.

Live demo: https://2048yz.netlify.app/

## Features

- Classic 4x4 tile grid gameplay
- Swipe support for touch devices
- Keyboard controls with Arrow keys and WASD
- Score tracking and persistent best score using `localStorage`
- Win and game over overlay states
- Smooth tile movement and merge animations

## How to Play

- Use `Arrow Up`, `Arrow Down`, `Arrow Left`, `Arrow Right` or `W`, `A`, `S`, `D` to move tiles.
- When two tiles with the same number collide, they merge into one tile with double the value.
- Continue merging until you reach the `2048` tile.
- The game ends when there are no valid moves left.

## Files

- `index.html` - contains the full game implementation and styling in a single file.

## Notes

- This project is ideal for demonstrating a small, self-contained web game.
- No build tools or dependencies are required.
