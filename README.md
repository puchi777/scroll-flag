# Scroll Flag

A simple 2D side-scrolling run game. The player automatically moves to the right — dodge obstacles by moving up and down to reach the flag.

## How to Play

- **Keyboard**: Use the arrow keys (Up/Down) to move vertically
- **Mouse**: Move the mouse up and down to control the player
- **Touch**: Tap the upper half of the screen to move up, or the lower half to move down

Reach the flag to clear the stage. Hitting an obstacle or the left wall results in a miss (lives -1). The game is over when lives reach 0.

## Features

- Scroll speed increases with each stage cleared
- Speed penalty on miss (-180 px/s, with a minimum cap)
- Obstacles and flags are randomly placed per stage
- Copy a result image to the clipboard on game over

## Tech Stack

- Canvas API + vanilla JavaScript (no external libraries)
- Single `index.html` file

## Demo

To be hosted on GitHub Pages.

## License

MIT
