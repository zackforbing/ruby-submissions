# GameTime Submission Form

## Basics

### Link to the Github Repository for the Project
[Gametime Repo](https://github.com/Caleb9193/gametime)

### Link to the Deployed Application
[Ricochet](https://caleb9193.github.io/gametime/)

### Link to Your Commits in the Github Repository for the Project
-[Caleb](https://github.com/Caleb9193/gametime/commits/master?author=Caleb9193)
 -[Garret](https://github.com/Caleb9193/gametime/commits/master?author=GSmes)

### Provide a Screenshot of your Game
-![Ricochet](http://i.imgur.com/dH55Edj.gif)

---

## Completion

### Do You Consider the Application to be Fully Playable?
 - Yes

### What Extensions, as Requested By an Instructor, Did You Complete?
- None

### What Features, if Any, Do You Feel Exceed Instructor Expectations?


----

## Risk Taking
- What risks did you feel you took on this project?
 - Choosing a project that relied heavily on math and equations
 - Not using any styling packages such as bootstrap, styling it all by hand
 - Implementing setTimeout very soon after we learned it, before we were really familiar with it
- How do you feel about those risks?
 - I feel like they were important to take when trying to build anything involving animation

----

## Code Quality

### Link to a specific block of your code on Github that you are proud of
[Collision detection](https://github.com/Caleb9193/gametime/blob/master/lib/bullet.js#L36)
- Why were you proud of this piece of code?
  -It was broken into small, easy to read parts, despite having very complicated logic

### Link to a specific block of your code on Github that you feel not great about
 - [Levels](https://github.com/Caleb9193/gametime/blob/master/lib/level_one.js#L4)
- Why do you feel not awesome about the code? What challenges did you face trying to write/refactor it?
  - Feel like all the levels could've been put into one constructor somehow, but wasn't really sure if that would just</br>
  result in one big messy file

### Attach a screenshot or paste the output from your terminal of the result of your test-suite running.
  - ```Bullet
    default attributes
      ✓ has a default height
      ✓ has a default width
      ✓ has a default y-coordinate
      ✓ has a default x-coordinate
      ✓ has a default radius
      ✓ has a default beginning bounce count
    given attributes
      ✓ has a given context
      ✓ has a given x-coordinate direction
      ✓ has a given y-coordinate direction
    draw
      ✓ should call arc on the canvas
      ✓ should pass x-coordinate, y-coordinate, and radius to arc
    move
      ✓ should increment the x coordinate by directionX
      ✓ should increment the y coordinate by directionY
    collisionCheck
      ✓ should be defined

  Shooter
    given attributes
      ✓ should have a given context

  Obstacle
    given attributes
      ✓ should have a given x-coordinate
      ✓ should have a given y-coordinate
      ✓ should have a given height
      ✓ should have a given width
      ✓ should have a given context

  Target
    default attributes
      ✓ should have a default width
      ✓ should have a default height
      ✓ should have a default display attribute of true
    given attributes
      ✓ should have a given x-coordinate
      ✓ should have a given y-coordinate
      ✓ should have a given context

  LevelOne
    default attributes
      ✓ has a default ammo amount
      ✓ has a default array of targets
      ✓ has a default array of obstacles

  LevelThree
    default attributes
      ✓ has a default ammo amount
      ✓ has a default array of targets
      ✓ has a default array of obstacles

  LevelTwo
    default attributes
      ✓ has a default ammo amount
      ✓ has a default array of targets
      ✓ has a default array of obstacles

  Scoreboard
    given attributes
      ✓ it should have a given context


  36 passing (25ms)```

### Test Breakdown
- How Many Unit Tests?
 - 36
- How Many Feature/Integration Tests?
 - 0

### Provide a link to an example, if you have one, of a unit test that covers an 'edge case' or 'unhappy path'

### Provide a link to an example, if you have one, of a feature test that covers an 'edge case' or 'unhappy path'

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
* __24 points - Application is fully playable without crashes or bugs__
* 10 points - Application has some missing functionality but no crashes
* 0 points - Application crashes during normal usage

### User Interface

* __15 points - The application is pleasant, logical, and easy to use. There are no holes in functionality and the application stands on its own to be used by the instructor without guidance from the developer.__
* 10 points - The application has many strong pages/interactions, but a few holes in lesser-used functionality.
* 5 points - The application shows effort in the interface, but the result is not effective. The evaluator has some difficulty using the application when reviewing the features in the user stories.
* 0 points - The application is confusing or difficult to use.

### Testing

* 30 points - Project has a running test suite that exercises the application at multiple levels. The test suite covers almost all aspects of the application and uses mocks and stubs when appropriate.
* __20 points - Project has a running test suite that tests multiple levels but fails to cover some features. All functionality is covered by tests. The application makes some use of integration testing.__
* 10 points - Project has sporadic use of tests and multiple levels. The application contains numerous holes in testing and/or many features are untested.
* 0 points - There is little or no evidence of testing in this application.

### JavaScript Style

* 30 points - Application has exceptionally well-factored code with little or no duplication and all components are separated out into logical components. There zero instances where an instructor would recommend taking a different approach.
* __25 points - Application is thoughtfully put together with some duplication and no major bugs. Developer can speak to choices made in the code and knows what every line of code is doing.__
* 15 points - Your application has a significant amount of duplication and one or major bugs.
* 5 points - Your client-side application does not function. Developer writes code with unnecessary variables, operations, or steps which do not increase clarity.
* 0 points - There is little or no client-side code. Developer writes code that is difficult to understand. Application logic shows poor decomposition with too much logic mashed together.

### Workflow

* __25 points - The developer effectively uses Git branches and many small, atomic commits that document the evolution of their application.__
* 15 points - The developer makes a series of small, atomic commits that document the evolution of their application. There are no formatting issues in the code base.
* 10 points - The developer makes large commits covering multiple features that make it difficult for the evaluator to determine the evolution of the application.
* 5 points - The developer commited the code to version control in only a few commits. The evaluator cannot determine the evolution of the application.
* 0 points - The application was not checked into version control.

### Code Sanitation

The output from JSHint shows…

* __15 points - Zero complaints__
* 10 points - Five or fewer complaints
* 5 points - Six to ten complaints
* 0 points - More than ten complaints

total = 124
