# GameTime Submission Form

## Basics

### Link to the Github Repository for the Project
[Asteroids Repo](https://github.com/seeker105/asteroids)

### Link to the Deployed Application
[Asteroids](https://annacw.github.io/asteroids/)

### Link to Your Commits in the Github Repository for the Project
-[Anna Weisbrodt](https://github.com/seeker105/asteroids/commits?author=AnnaCW)
 -[Christopher Soden](https://github.com/seeker105/asteroids/commits?author=seeker105)

### Provide a Screenshot of your Game
-![Asteroids](https://cloud.githubusercontent.com/assets/15236021/18174700/affdde04-702b-11e6-9dba-ee033641a572.png)

---

## Completion

### Do You Consider the Application to be Fully Playable?
 - Yes

### What Extensions, as Requested By an Instructor, Did You Complete?
- None

### What Features, if Any, Do You Feel Exceed Instructor Expectations?
- Smooth ship movement
  - [code](https://github.com/seeker105/asteroids/blob/master/lib/index.js#L56-L99)

----

## Risk Taking
- The project was fairly straightforward. One of the challenges was working with arrays in localStorage for the first time. Another was the issue of testing and the decision to move the render control to a separate module to make the logic testable.
- We feel that the experience from this has given us the experience to take on more complex challenges.

----

## Code Quality

### Link to a specific block of your code on Github that you are proud of
[insertScore](https://github.com/seeker105/asteroids/blob/master/lib/game_runner.js#L114-L126)
I did research on sort algorithms for another exercise. The insert sort is not the most efficient sort, but it works very well in this case.

### Link to a specific block of your code on Github that you feel not great about
[index.js](https://github.com/seeker105/asteroids/blob/master/lib/index.js#L20-L28)
- This logic would make more sense in the GameRunner class.

### Attach a screenshot or paste the output from your terminal of the result of your test-suite running.
![screenshot](https://cloud.githubusercontent.com/assets/15236021/18178672/847a2902-703c-11e6-93cb-4fc2155e6ca7.png)

### Test Breakdown
- How Many Unit Tests? 31
- How Many Feature/Integration Tests? 0

### Provide a link to an example, if you have one, of a unit test that covers an 'edge case' or 'unhappy path'
[Unhappy Path](https://github.com/seeker105/asteroids/blob/2fa3f02843dac0a6921416591897a53439ffe600/test/collision-detection-test.js#L6-L17)

### Provide a link to an example, if you have one, of a feature test that covers an 'edge case' or 'unhappy path'

-----

### Please feel free to ask any other questions or make any other statements below!
We wanted to write feature tests, but we cannot test graphics on the canvas directly. The best we could do was separate the render logic and test the code that determines what the graphics should be. This resulted in straight unit tests.

-----

# Instructor Feedback

- Points: (base 150)

135/150

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

### User Interface

* 10 points - The application has many strong pages/interactions, but a few holes in lesser-used functionality.

### Testing

* 30 points - Project has a running test suite that exercises the application at multiple levels. The test suite covers almost all aspects of the application and uses mocks and stubs when appropriate.

### JavaScript Style

* 20 points - Application is thoughtfully put together with some duplication and no major bugs. Developer can speak to choices made in the code and knows what every line of code is doing.

### Workflow

* 25 points - The developer effectively uses Git branches and many small, atomic commits that document the evolution of their application.

### Code Sanitation

The output from JSHint shows…

* 15 points - Zero complaints
