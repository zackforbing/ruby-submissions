# GameTime Submission Form

## Basics

### Link to the Github Repository for the Project
[Seven Levels of Code](https://github.com/Riizu/sloc)

### Link to the Deployed Application
[Production Link](http://riizu.github.io/sloc)

### Link to Your Commits in the Github Repository for the Project
-[Ryan Batty](https://github.com/Riizu/sloc/commits/master?author=Riizu)
 -[Parker Phillips](https://github.com/Riizu/sloc/commits/master?author=ExCaelum)

### Provide a Screenshot of your Game
- [Gallery](http://imgur.com/gallery/sCuDa)

---

## Completion

### Do You Consider the Application to be Fully Playable?
 - It is fully playable.

### What Extensions, as Requested By an Instructor, Did You Complete?
- Per Extension:
  - Describe the extension
  - Provide a .gif of the extension or a link to the relevant code

### What Features, if Any, Do You Feel Exceed Instructor Expectations?
- Procedural Generation:
 - All of our levels are generated on the fly using a combination of a number of procedural generation algorithms. These algorithms randomly place rooms, corridors, enemies, health pack keys, exits, and the player placement. Furthermore they are easily adjustable with a single method call, allowing us to scale it to player level or any progressive math formula.
 - [Game Engine - Where the generation is started]()
 - [Generator - All of the generation methods]()
- Replayability:
 - Because of the procedural generation, the only limit to our replayability is the overall efficiency of the game and the power of the machine running it. So far we've been able to cheat ourselves to levels above 100, but it gets incredibly difficult going into level 15 with regular play.
 - Provide a .gif of the feature in action or a link to the relevant code
- Camera:
 - Because of the eventual size of the game map, it became critical that we have a way to zoom in and show only relevant portions of the map. Using dynamic cell grabbing and transalation of coordinates to relative canvas placement.
 - [DisplayHandler - Draw methods](https://github.com/Riizu/sloc/blob/master/lib/display_handler.js)
 - [Camera - Specific camera details](https://github.com/Riizu/sloc/blob/master/lib/camera.js)

----

## Risk Taking
- During this project, a number of heavy risks were taken, primarily the procedural generation. Considering the amount of prior experience with JS and the general difficulty of procedural generation, it was a daunting task. While we ended up scrapping our original approach, we feel it was still wildly successful. It was incredibly gratifying to see that pay off into a game that is truly different every time you play.

----

## Code Quality

### Link to a specific block of your code on Github that you are proud of
- [Grid Abstraction](https://github.com/Riizu/sloc/blob/master/lib/grid.js)
- Our grid is really the foundation of the game. We spent a solid two days early on cleaning it up and getting it ready to build upon. We knew that it was necessary to have this incredibly polished in order to use well, and that work really paid off going forward.

### Link to a specific block of your code on Github that you feel not great about
- [Cell.hasNeighbors(directionArray)](https://github.com/Riizu/sloc/blob/master/lib/cell.js)
- On the other hand, the grid is built with cells and while they were fully functional, they just weren't as flexible as we would of wished. In particular hasNeighbors is pretty frequently used but the code is ugly, messy, and just not easily used. In the end, it was something we stomached to be able to complete other features on time.

### Attach a screenshot or paste the output from your terminal of the result of your test-suite running.

- [Test Suite](http://i.imgur.com/hpIyPCP.png)
- We had two failures due to a strange require failure on Image(), yet the call works fine in the actual program.

### Test Breakdown
- Unit Tests: 11
- Integration Tests: 22

### Provide a link to an example, if you have one, of a unit test that covers an 'edge case' or 'unhappy path'

- [Cell should determine it has one neighbor if a single solid cell is north of it](https://github.com/Riizu/sloc/blob/master/test/cell_test.js#L45)

### Provide a link to an example, if you have one, of a feature test that covers an 'edge case' or 'unhappy path'

- [Grid should pull all rooms in the grid when no rooms are present](https://github.com/Riizu/sloc/blob/master/test/grid_test.js#L63)

-----

# Instructor Feedback

- Points: (base 150)

140/150

### Playability Features

We want your game to be full-featured and playable -- not just a proof of concept of the gameplay and rendering features.

To this end, make sure to include sufficient UX to allow the user to fully interact with the game. This would include:

- Indicate when the game is over and won or lost
- Allow the user to start a new game
- Include a clean UI surrounding the actual game interface itself
- Score Tracking: How this works will vary by game, but at the end of the game, generate a score for the winning player
- Scoreboard -- track scores across multiple game sessions. Since we aren't incorporating a server for our games, client-side storage like a cookie or LocalStorage will suffice.
- Create multiple rounds of difficulty. (consider increasing factors such as game speed, randomness of starting setup, etc)

### Features

* 45 points - Application is fully playable and exceeds the expectations set by instructors

### User Interface

* 15 points - The application is pleasant, logical, and easy to use. There are no holes in functionality and the application stands on its own to be used by the instructor without guidance from the developer.

### Testing

* 20 points - Project has sporadic use of tests and multiple levels. The application contains numerous holes in testing and/or many features are untested.

### JavaScript Style

* 20 points - Application is thoughtfully put together with some duplication and no major bugs. Developer can speak to choices made in the code and knows what every line of code is doing.

### Workflow

* 25 points - The developer effectively uses Git branches and many small, atomic commits that document the evolution of their application.

### Code Sanitation

The output from JSHint shows…

* 15 points - Zero complaints
