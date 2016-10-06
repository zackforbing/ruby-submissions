Complete this Form before the third check in. Delete this line from your version.

# Game Time Check In # 3

## Instructor Goal Completion

### setup new Game on start
https://github.com/patrickwhardy/asteroids/blob/master/lib/game.js#L63-L74

### corresponding interface
https://github.com/patrickwhardy/asteroids/blob/master/lib/game.js#L359-L370

### setup # of player lives
https://github.com/patrickwhardy/asteroids/blob/master/lib/game.js#L63-L74

### corresponding interface (decrementing lives)
https://github.com/patrickwhardy/asteroids/blob/master/lib/game.js#L352

### collision of ship and asteroid decrements lives
https://github.com/patrickwhardy/asteroids/blob/master/lib/game.js#L182-L198

### A basic end game scenario
https://github.com/patrickwhardy/asteroids/blob/master/lib/game.js#L328-L337

### Ship is removed from screen when killed - reacts to death - comes back
https://github.com/patrickwhardy/asteroids/blob/master/lib/game.js#L314-L326

### First pass of how you define high score
https://github.com/patrickwhardy/asteroids/blob/master/lib/game.js#L355-L357

### First pass of drawing polyshape asteroid
https://github.com/patrickwhardy/asteroids/blob/master/lib/asteroid.js#L33-L56


## Next Steps?

- alien bullet collision detection
- store high score (local storage)
- add thruster sound
- improve alien bullet aiming (maybe)
- possible bug - undefined in lives
- possible bug - hit by asteroid and 2 lives removed?

##### Once all this is done we want to experiment with websocket/multiplayer mode
- multiplayer mode, add another ship and add lives to accordingly
  - cooperative version
- players can shoot eachother and have independent lives etc.
  - vs version

### General Questions, Comments, Concerns?
- ask about testing with Audio
- how to investigate for frame rate glitch?
- steps for migrating to node

### Extra Credit
- MVP features as defined in Next Steps all completed

## Instructor Section

### Points for Second Check In (base 50)
62/50
### Instructor's Goals for Next Check In
- deploy to github pages 
- style the page and have instructions on how to play 
- define conrols 
- refactor some of the large methods. 

### Feedback?

game ui and ux are great! 
logic behind game is also super great 
look into adding your extesnion if you have time. 
check out higher order functions in javascript
