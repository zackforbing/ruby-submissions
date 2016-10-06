# Game Time Check In # 2

## Instructor Goal Completion

### Bullets/Shooting/Ship movement
- https://github.com/patrickwhardy/asteroids/blob/master/lib/spaceship.js

### Some testing?
- most model level logic is now tested.
- https://github.com/patrickwhardy/asteroids/tree/testing/test

### Collision detection against other objects on canvas
- https://github.com/patrickwhardy/asteroids/blob/master/lib/index.js#L46-L57

### Smaller files for objects
- https://github.com/patrickwhardy/asteroids/tree/master/lib

## Next Steps?
#### What do you feel the next steps should be?
- setup new Game on start
- setup # of player lives
- animate ship destruction/decrement lives
- collision detection for asteroids + bullets
- animate asteroid destruction / change in size
- refactor acceleration incorporate drift?
- incorporate game timer (high scores?)
- increment game level / number of asteroids
- draw polyshape asteroid

### General Questions, Comments, Concerns?

## Instructor Section

### Points for Second Check In (base 50)

50/50

### Instructor's Goals for Next Check In

- setup new Game on start
  - corresponding interface 
- setup # of player lives
  - corresponding interface (decrementing lives)
  - collision of ship and asteroid decrements lives
- A basic end game scenario
- Ship is removed from screen when killed - reacts to death - comes back
- First pass of how you define high score
- First pass of drawing polyshape asteroid

Extra Credit

- refactor acceleration incorporate drift and test happy and sad paths (from stand still, from movement, etc)
- MVP features as defined in Next Steps all completed

### Feedback?
