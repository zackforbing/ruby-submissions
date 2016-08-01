# Game Time Check In # 3

## Instructor Goal Completion

### GOAL 1
#### More robust tests, more coverage
  - Provide a screenshot or gif or link to code for this goal

  [Link to test directory](https://github.com/brennanholtzclaw/game_time/tree/master/test)

### GOAL 2
#### Clicking a ball gives speed and direction
- Provide a screenshot or gif or link to code for this goal

  [The ball goes where it should](http://g.recordit.co/LsSkFtcpmG.gif)
- Questions, Comments, Concerns?

  This took a long time to figure out, but it turned out to be a simple fix, resetting the ball direction whenever it stops.

### GOAL 3
#### Have a complex level done, defined by clicking on the ball, playing until the ball is in the hole, and getting a score

- Provide a screenshot or gif or link to code for this goal
  [In the Hole!](http://g.recordit.co/5KcDT8P1vA.gif)

- Questions, Comments, Concerns?

  This is actually not as perfect at it may seem. At the moment, when we switch levels we lose some context. The ball color resets, and our physics don't work as expected anymore.
  We're working to figure out exactly why, now.

### GOAL 4
#### Extension: Start up screen with instructions and click to play
- Provide a screenshot or gif or link to code for this goal

  [Enter your name and pick your color!](http://g.recordit.co/0Xw1nzD6N0.gif)

## Next Steps?

- What do you feel the next steps should be?
  I think now we need to do a little more debugging to guarantee that the ball doesn't go through a wall, and make sure that all logic works for every level.
  We also want to start looking into extensions, like adding hills, and a visual indicator of direction to make aiming a little more intuitive.

### General Questions, Comments, Concerns?

-----

## Instructor Section

### Points for Third Check In (base 50)
  50/50

### Instructor's Goals for Next Check In
  - Pull out collision detection class 
  - End screen with final score
  - Visual representation of ball direction
  - Additional obstacles (like tunnels)
  - Continue adding tests for math-heavy methods
  
EXTENSION
  - Sounds! 
  - Grass/Sand/More visual stuff

### Feedback?
   - 25 Tests (vs roughly half from last checking)
