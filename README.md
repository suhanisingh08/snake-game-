# Snake Game

**Student:** Suhani | 2nd Year CSE-IOT III Sem | USN: 25BTRCO051

The classic Snake game on a canvas, with keyboard and on-screen controls and a saved high score.

## OVERVIEW
The player steers a snake around a 20 x 20 grid to eat food. Each piece of food grows the snake and adds a point. The game ends when the snake hits a wall or itself.

## TECH STACK
- Frontend: HTML5 Canvas, CSS3 (dark theme, button pad)
- Logic: vanilla JavaScript (setInterval game loop, arrays of coordinates, keyboard events)
- Storage: browser localStorage for the high score

## HOW IT WORKS
The snake is an array of grid cells. Every tick, a new head is added in the current direction and the tail is removed unless food was eaten. Wall and self collisions are checked before moving. The direction cannot reverse directly into the body. Every 5 points the loop restarts at a faster speed. Space pauses, Enter restarts, and the high score is saved when a game ends.

## KEY FEATURES
- Arrow keys or WASD, plus on-screen buttons for touch
- Growing snake and random food placement
- Score and saved high score
- Pause and restart
- Speed increases as the score rises

## USES
Learning game loops, collision detection and coordinates, building on the Canvas work in OI-CORE.

## HOW TO RUN
Open index.html in any browser. No installation or internet connection is needed.
