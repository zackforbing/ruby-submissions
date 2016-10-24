# GameTime Submission Form

## Basics

### Link to the Github Repository for the Project
[Bomberman](https://github.com/roscalabrin/bomberman)

### Link to the Deployed Application
[BomberApp](https://roscalabrin.github.io/bomberman/)

### Link to Your Commits in the Github Repository for the Project
-[Commits](https://github.com/roscalabrin/bomberman/commits/master)

### Provide a Screenshot of your Game
-![bomberman](./submission_screenshot.png)

---

## Completion

### Do You Consider the Application to be Fully Playable?
- Yes, we even incorporated level selection and quit game features.

### What Extensions, as Requested By an Instructor, Did You Complete?
- Multiplayer.

### What Features, if Any, Do You Feel Exceed Instructor Expectations?
- Overall complexity of project idea. Did our best to stick to recreating
a classic game by mimicking collision effects and other gameplay features.

- Second level included multiple components that adjusted the dynamics
of the game:
  - smaller map size
  - larger bombs
  - bigger explosion radius (ie another collision detection algorithm)
  - seperate block alignment and collision detection for those
----

## Risk Taking

- What risks did you feel you took on this project?
  - Taking on a project that has a grid-like layout (as opposed to a side-scroller) forced
    developers to write collision detection from all four angles.
  - Nature of game called for developers to write collision detection for smaller objects running into larger ones,
    larger objects colliding with smaller objects, and many, many other collision scenarios.
  - Codebase written exclusively using ES6 syntax.
- How do you feel about those risks?
  - (Pat) I'm happy with the fact that we were able to stick with our idea and execute an MVP without making a drastic
    pivot - or switching to a simpler project. I was also pleased with our game's ability to mimic some effects actually
    seen in Bomberman games. With that said, I'm disappointed we had to prioritize writing code
    for another level that makes the players faster, and the bombs bigger in order to meet the spec because it still
    doesn't allow someone to pick up and play by themselves.

----

## Code Quality

### Link to a specific block of your code on Github that you are proud of
- Why were you proud of this piece of code?
  +[Code](https://github.com/roscalabrin/bomberman/blob/master/lib/player.js#L35-L49)
  +[Code](https://github.com/roscalabrin/bomberman/blob/master/lib/game.js#L47-L61)

  We thought this was a neat refactor. Before we had 4 different draw methods on each player subclass
  since the numbers needed were dynamic. What we instead did was moving the sprite coords as props on
  the instance of the subclasses - and then have a draw method on the player superclass. This way,
  we could call the function by passing the type of sprite as an arg (ie leftSprite, rightSprite) -
  and then use bracket notation to access that property on the instance.

### Link to a specific block of your code on Github that you feel not great about
- Why do you feel not awesome about the code? What challenges did you face trying to write/refactor it?
  +[Code](https://github.com/roscalabrin/bomberman/blob/master/lib/helpers/collisionEngine.js#L7-L31)
  +[Code](https://github.com/roscalabrin/bomberman/blob/master/lib/defaultMap.js#L38-L50)

  This is the end result of an attempted refactor after our refactor tractor lesson. We think the attempt,
  at the very least, makes the code more readable. The reason it's here is that becuase there is no 
  difference between calling the individual methods themselves, and calling them from within the object literal.
  We knew there was repeated code that we could extrapolate, however each use case was so particular that we figured
  trying to refactor it into a few clever methods would ultimately make the code less readable.

### Attach a screenshot or paste the output from your terminal of the result of your test-suite running.
-![bomberman](./submission_test_suite.png)

### Test Breakdown

- (Roberta) We used TDD throughout this project and tested all collision logic and player movements to its full extension.
  However, when implemented multi-levels and the ability to start a new game after the end of a game, we extracted the logic from the index.js
  and made the game class dependent on more classes we run into an issue with stubbing that we could not figure it out prior to deadline.

- How Many Unit Tests?

30

- How Many Feature/Integration Tests?

15

### Provide a link to an example, if you have one, of a unit test that covers an 'edge case' or 'unhappy path'
  +[Code](https://github.com/roscalabrin/bomberman/blob/master/test/score.js#L9-L13)

### Provide a link to an example, if you have one, of a feature test that covers an 'edge case' or 'unhappy path'
  +[Code](https://github.com/roscalabrin/bomberman/blob/master/test/collisionEngine.js#L12-L103)

-----

### Please feel free to ask any other questions or make any other statements below!

-----

# Instructor Feedback

- Points: (base 150)

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

* 35 points - Application is fully playable and exceeds the expectations set by instructors
* **25 points - Application is fully playable without crashes or bugs**
* 10 points - Application has some missing functionality but no crashes
* 0 points - Application crashes during normal usage

### User Interface

* 15 points - The application is pleasant, logical, and easy to use. There are no holes in functionality and the application stands on its own to be used by the instructor without guidance from the developer.
* **12 points - The application has many strong pages/interactions, but a few holes in lesser-used functionality.**
* 5 points - The application shows effort in the interface, but the result is not effective. The evaluator has some difficulty using the application when reviewing the features in the user stories.
* 0 points - The application is confusing or difficult to use.

### Testing

* 30 points - Project has a running test suite that exercises the application at multiple levels. The test suite covers almost all aspects of the application and uses mocks and stubs when appropriate.
* **27 points - Project has a running test suite that tests multiple levels but fails to cover some features. All functionality is covered by tests. The application makes some use of integration testing.**
* 10 points - Project has sporadic use of tests and multiple levels. The application contains numerous holes in testing and/or many features are untested.
* 0 points - There is little or no evidence of testing in this application.

### JavaScript Style

* 30 points - Application has exceptionally well-factored code with little or no duplication and all components are separated out into logical components. There zero instances where an instructor would recommend taking a different approach.
* **25 points - Application is thoughtfully put together with some duplication and no major bugs. Developer can speak to choices made in the code and knows what every line of code is doing.**
* 15 points - Your application has a significant amount of duplication and one or major bugs.
* 5 points - Your client-side application does not function. Developer writes code with unnecessary variables, operations, or steps which do not increase clarity.
* 0 points - There is little or no client-side code. Developer writes code that is difficult to understand. Application logic shows poor decomposition with too much logic mashed together.

### Workflow

* **25 points - The developer effectively uses Git branches and many small, atomic commits that document the evolution of their application.**
* 15 points - The developer makes a series of small, atomic commits that document the evolution of their application. There are no formatting issues in the code base.
* 10 points - The developer makes large commits covering multiple features that make it difficult for the evaluator to determine the evolution of the application.
* 5 points - The developer commited the code to version control in only a few commits. The evaluator cannot determine the evolution of the application.
* 0 points - The application was not checked into version control.

### Code Sanitation

The output from JSHint shows…

* 15 points - Zero complaints
* 10 points - Five or fewer complaints
* 5 points - Six to ten complaints
* **0 points - More than ten complaints**
