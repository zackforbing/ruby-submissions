Complete this Form before the second check in. Delete this line from your version.

# Game Time Check In # 2

## Instructor Goal Completion

### GOAL 1: Map

  - [Screenshot](https://i.imgur.com/VKDzGjs.png)
  - Map is 2D array of `0`'s and `1`'s - `0`'s are open space, `1`'s are walls.
  - Unsure if current design is overkill, definitely needs to be refactored. Nice thing is, it'll allow for custom map submission (possible extension).

### GOAL 2: Collision Detection for Walls

- [Link to Code](https://github.com/notmarkmiranda/game-time/blob/refactor/lib/player.js#L17-21)
- Player check's contents of next block before moving and only moves x or y position if block is 'open' (has a type `0`)

### GOAL 3: Pellet Objects

- [Screenshot](https://i.imgur.com/VKDzGjs.png) (darker colored / smaller blocks are pellets)
- Added basic pellets to map - they are `-1` type.

### GOAL 4: Collision Detection for Pellets

- [Screenshot](https://i.imgur.com/4ljELEf.png)
- When a player passes over the pellet, the pellet disappears (it's block is switched from `-1` to type `0`) and the player gains 1 point.

## Next Steps?

- Add Ghosts that chase the player
- Increase the number of Ghosts over time, in order to increase difficulty
- Score = Time Alive + Points Collected

### General Questions, Comments, Concerns?

-----

## Instructor Section

### Points for first check in (base 50)
50/50

### Steps for Next Checkin
- Game Start/Instructions
- Game End
- Increase of difficulty
- Game End Scoreboard - Time + User Points/Something to score my game
 - Phase 1: Hit ghost (figure out colliison detection with ghost and user) game ends. 
 - Phase 2: Multiple lives, game resets to level you're on.
- Keep Testing :)
 
Extensions:
- Graphics
- Input personal map

### Feedback?
