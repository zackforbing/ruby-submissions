# GameTime Submission Form

## Basics

### Link to the Github Repository for the Project
[Your Repo](https://github.com/danjwinter/game-time-t-rex)

### Link to the Deployed Application
[Your Application](http://danjwinter.github.io/game-time-t-rex/)

### Link to Your Commits in the Github Repository for the Project
[Commits](https://github.com/danjwinter/game-time-t-rex/commits/master)

### Provide a Screenshot of your Game
![Jumpy the dino](http://g.recordit.co/XIrK0crUQI.gif)

---

## Completion

### Do You Consider the Application to be Fully Playable?

 - Only if you are a fan of dinosaurs with guns.

### What Extensions, as Requested By an Instructor, Did You Complete?

- We were not given a specific extension but we did incorporate Firebase to track scores. We added sounds to the game and were able to give the dino a gun and ability to shoot.

### What Features, if Any, Do You Feel Exceed Instructor Expectations?

- The gun and shooting feature. Implementing firebase.

----

## Risk Taking

- What risks did you feel you took on this project?
  - We went above and beyond with features compared to the original game.
- How do you feel about those risks?
  - We think it turned out great and we learned a lot while implementing those features.

----

## Code Quality

### Link to a specific block of your code on Github that you are proud of

[Duck typing](https://github.com/danjwinter/game-time-t-rex/blob/master/lib/session.js#L73-L86)

We’re proud of this code because we were able to employ duck typing for all of our game objects to respond to an update() method call. This enables us to easily incorporate other game objects into the game in the future like flying pterodactyls and we’re pretty sure Sandi Metz would be proud.

### Link to a specific block of your code on Github that you feel not great about

[Scoreboard Testing](https://github.com/danjwinter/game-time-t-rex/blob/master/lib/scoreboard.js)

We did not know how to test the dynamic scoreboard, therefore not happy about lack of TDD.

### Attach a screenshot or paste the output from your terminal of the result of your test-suite running.

![Tests!!](http://g.recordit.co/qgB6M4Oux3.gif)

### Test Breakdown
- How Many Unit Tests?
- How Many Feature/Integration Tests?

We had about 10 integration tests for collision detection and 71 tests total.

### Provide a link to an example, if you have one, of a unit test that covers an 'edge case' or 'unhappy path'

[Dino cannot double jump](https://github.com/danjwinter/game-time-t-rex/blob/master/test/dino-test.js#L112-L117)


-----

### Please feel free to ask any other questions or make any other statements below!

-----

## Instructor Feedback

- Points: (base 300)
