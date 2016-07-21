Complete this Form before the final eval. Delete this line from your version.

# GameTime Submission Form

## Basics

### Link to the Github Repository for the Project
[Your Repo](https://github.com/patrickwhardy/asteroids)

### Link to the Deployed Application
[Your Application](http://asteroids123.herokuapp.com/)

### Link to Your Commits in the Github Repository for the Project
-[Team](https://github.com/patrickwhardy/asteroids/commits/master)

### Provide a Screenshot of your Game
-![spacejam](https://files.slack.com/files-pri/T029P2S9M-F1RRJNRU3/asteroids.png)

## Completion

### Do You Consider the Application to be Fully Playable?
 - Yes its awesome

### What Extensions, as Requested By an Instructor, Did You Complete?
- Per Extension:
  - Hand Rolled Node Server
  - Alien SpaceShips w/ bullets
  - Buffs w/ power ups

### What Features, if Any, Do You Feel Exceed Instructor Expectations?
- Ship physics, audio, all extensions

----

## Risk Taking
- Spent two days setting up node and sockets and sockets were unsuccessful

----

## Code Quality

### Link to a specific block of your code on Github that you are proud of
- Why were you proud of this piece of code?

### Link to a specific block of your code on Github that you feel not great about
- Why do you feel not awesome about the code? What challenges did you face trying to write/refactor it?

### Attach a screenshot or paste the output from your terminal of the result of your test-suite running.

Asteroid
  with default attributes
    ✓ starts with a center off screen
    ✓ has a random size
    ✓ has a random slope
    ✓ moves in random direction
    ✓ checks if its off screen

Bullet
  with default attributes
    ✓ has default size
    ✓ has center
    ✓ has speed of 1
    ✓ accelerates

Game
  it is a game
    ✓ has a level
    ✓ creates a ship off screen
    ✓ creates asteroids with random slope
    ✓ it creates smaller asteroids with unique attributes
    ✓ removes asteroids
    ✓ checks game time on condition
    ✓ levels up after time reaches 1000
    - checks ship collision
    ✓ breaks asteroids into pieces
    ✓ respawns the ship
    ✓ calculates score on level and astroids destroyed

Spaceship
  with default attributes
    ✓ should have a point
    ✓ should have rightSide
    ✓ should have leftSide
    ✓ should have no speed
    ✓ should be oriented vertically
    ✓ calculates slope
    ✓ accelerates properly
    ✓ decelerates properly
    ✓ stops decelerating at 0
    ✓ fires bullets
    ✓ checks checks position when exiting screen
    ✓ finds center
    ✓ clears bullets every 100
    ✓ finds its sides
    ✓ calculates intertia
    ✓ hides the ship
    ✓ unhides the ship


36 passing (27ms)
1 pending

### Test Breakdown
- How Many Unit Tests?: 36
- How Many Feature/Integration Tests?: 0

### Provide a link to an example, if you have one, of a unit test that covers an 'edge case' or 'unhappy path'

[check ship collision](https://github.com/patrickwhardy/asteroids/blob/troubleshoot/test/game.js#L92-L114)

### Provide a link to an example, if you have one, of a feature test that covers an 'edge case' or 'unhappy path'

-----

### Please feel free to ask any other questions or make any other statements below!

-----

## Instructor Feedback

- Points: 145/150

## Extensions

* ***25 points***

### Functional Expectations

* **35 points** - Application is fully playable and exceeds the expecations set by instructors

### User Interface

* **15 points** - The application is pleasant, logical, and easy to use. There no holes in functionality and the application stands on it own to be used by the instructor _without_ guidance from the developer.

### Testing

* **20 points** - Good testing of what present, multiple features untested

### JavaScript Style

* **20 points** - Application is thoughtfully put together with some duplication and no major bugs. Developer can speak to choices made in the code and knows what every line of code is doing.

### Workflow

* **25 points** - The developer effectively uses Git branches and many small, atomic commits that document the evolution of their application.

### Code Sanitation

The output from JSHint shows…

* **5 points** - Six to ten complaints
