# GameTime Submission Form

## Basics

### Link to the Github Repository for the Project
[Repo Link](https://github.com/scottfirestone/carcassonne)

### Link to the Deployed Application
[Our Application](https://scottfirestone.github.io/carcassonne/)

### Link to Your Commits in the Github Repository for the Project
 -[Scott](https://github.com/scottfirestone/carcassonne/commits?author=scottfirestone)
 -[Kimi](https://github.com/scottfirestone/carcassonne/commits?author=ksk5280)

### Provide a Screenshot of your Game
![carcassonne](https://github.com/scottfirestone/carcassonne/blob/master/carcassonne-screenshot.png)

---

## Completion

### Do You Consider the Application to be Fully Playable?
 - Yes, but it requires players to play by the rules.

### What Extensions, as Requested By an Instructor, Did You Complete?
- Per Extension:
 - Multiple Players - Selectable number of players (2-5) at start of game, can enter names.
 - [Link to Code](https://github.com/scottfirestone/carcassonne/blob/master/lib/game.js#L96-L111)

 - Force tile placement adjacency - Tiles must be placed adjacent and abutting previously placed tiles.
 - [Link to Code](https://github.com/scottfirestone/carcassonne/blob/master/lib/tileInventory.js#L74-L106)

 - Players can increment and deincrement their scores.
 - [Link to Code](https://github.com/scottfirestone/carcassonne/blob/master/lib/playerInfo.js#L57-L70)
 
 - Popup Rules - Clickable button to popup the rules of the game.
 - [Link to Code](https://github.com/scottfirestone/carcassonne/blob/master/lib/rules.js)

### What Features, if Any, Do You Feel Exceed Instructor Expectations?
- Per Feature:
 - Animations - Pretty Stuff.
 - [Link to Code](https://github.com/scottfirestone/carcassonne/blob/master/lib/animations.js)

 - Board grows dynamically with tile placement.
 - [Link to Code](https://github.com/scottfirestone/carcassonne/blob/master/lib/grid.js)

----

## Risk Taking
- What risks did you feel you took on this project?  
Javascript is very new to us both, so, the sheer magnitude of this project was a risk.  
The use of animations involved using GreenSock, which neither of us have used before.  

- How do you feel about those risks?  
We feel good that we were able to successfully implement all pieces of the game, which has lots of different pieces and rules, especially in a new language.

----

## Code Quality

### Link to a specific block of your code on Github that you are proud of  
We're proud of our ability to test that positions are open and valid based on tile adjacency.
- [Link to Code](https://github.com/scottfirestone/carcassonne/blob/master/lib/tileInventory.js#L74-L106)

### Link to a specific block of your code on Github that you feel not great about
- Why do you feel not awesome about the code? What challenges did you face trying to write/refactor it?  
Our game class is pretty beefy. While we refactored out some of the code into other classes, it could have probably benefited from some more extraction. We found it difficult to decouple some of the javascript logic from the DOM manipulation as the game is so dependent on DOM manipulation.
- [Link to Code](https://github.com/scottfirestone/carcassonne/blob/master/lib/game.js)

### Attach a screenshot or paste the output from your terminal of the result of your test-suite running.
```
$ npm test

> game-time-starter-kit@1.0.0 test /Users/scottfirestone/Turing/4module/carcassonne
> ./node_modules/mocha/bin/mocha --compilers js:babel/register



  MeepleInventory
    ✓ returns an object
    ✓ has a color

  Meeple
    ✓ returns an object
    ✓ has attributes

  Player
    ✓ returns an object
    ✓ has a name
    ✓ has a color
    addToScore
      ✓ increments the score
    subtractFromScore
      ✓ decrements the score, does not go below zero

  TileInventory
    ✓ returns an object
    isPositionOpen
      ✓ returns true if tile not in given position
    addAdjacentCoordinates
      ✓ adds x and y coordinates of position around tile to adjacentPositions array

  Tile
    ✓ returns an object
    ✓ has attributes
    ✓ has x and y that both default to zero


  15 passing (24ms)
```

### Test Breakdown
- How Many Unit Tests? -15
- How Many Feature/Integration Tests? -Zero.

### Provide a link to an example, if you have one, of a unit test that covers an 'edge case' or 'unhappy path'

### Provide a link to an example, if you have one, of a feature test that covers an 'edge case' or 'unhappy path'

-----

### Please feel free to ask any other questions or make any other statements below!

-----

## Instructor Feedback

- Points: (base 300)

#### Playability Features

We want your game to be full-featured and playable -- not just a proof of concept of the gameplay and rendering features.

To this end, make sure to include sufficient UX to allow the user to fully interact with the game. This would include:

Indicate when the game is over and won or lost
Allow the user to start a new game
Include a clean UI surrounding the actual game interface itself
Score Tracking: How this works will vary by game, but at the end of the game, generate a score for the winning player
Scoreboard -- track scores across multiple game sessions. Since we aren't incorporating a server for our games, client-side storage like a cookie or LocalStorage will suffice.
Create multiple rounds of difficulty. (consider increasing factors such as game speed, randomness of starting setup, etc)

#### Extensions

Create an AI player that can play as the second player (except in 2048).
Multiplayer support -- either by sharing a keyboard (2 sets of key inputs) or, as an extra-difficult extension, via websockets between multiple browsers
Evaluation Rubric

There are 300 total available points for this project.

150 are available at each of three check-ins and are at instructor descretion.

Teams must complete the submission form prior to each check-in.

150 out of a total of 300 points are included in the rubric below. The additional 150 feature points will be determined during iteration planning with instructors during check-ins.

#### Functional Expectations

33 points - Application is fully playable and exceeds the expecations set by instructors
- tiles placement isn't aware of correct side matching. small ding, would help with difficulty levels. Overall, really great game! Good job!

#### User Interface

15 points - The application is pleasant, logical, and easy to use. There no holes in functionality and the application stands on it own to be used by the instructor without guidance from the developer.

-------

### Testing

* **25 points** - Project has a running test suite that tests and multiple levels but fails to cover some features. All functionality is covered by tests. The application makes some use of integration testing.

### JavaScript Style

* **20 points** - Application is thoughtfully put together with some duplication and no major bugs. Developer can speak to choices made in the code and knows what every line of code is doing.

### Workflow

* **25 points** - The developer effectively uses Git branches and many small, atomic commits that document the evolution of their application.

### Code Sanitation

The output from JSHint shows…

* **10 points** - Five or fewer complaints
