

# GameTime Submission Form-Nick and Marcella

## Basics

### Link to the Github Repository for the Project
[GitHub Repo](https://github.com/nickpisciotta/game-time)

### Link to the Deployed Application
[Application Link](nickpisciotta.github.io/game-time)

### Link to Your Commits in the Github Repository for the Project
-[Nick's Commits](https://github.com/nickpisciotta/game-time/commits?author=nickpisciotta)


 -[Marcella's Commits](https://github.com/nickpisciotta/game-time/commits?author=marcellawigg)

### Provide a Screenshot of your Game
-![screenshot](http://g.recordit.co/CVw5STlgT4.gif)

---

## Completion

### Do You Consider the Application to be Fully Playable?
 - We do consider this game to be fully playable at this time.

### What Extensions, as Requested By an Instructor, Did You Complete?

  - We did not establish any explicit extensions, but we delivered on our MVP.  We didn't get the full functionality and features we had wanted, however.

### What Features, if Any, Do You Feel Exceed Instructor Expectations?
- We feel that we meet instructor expectations

----

## Risk Taking
- Trying to create two terrains that function differently
- Generate random objects and increase their speeds throughout levels.


----

## Code Quality

### Link to a specific block of your code on Github that you are proud of
- Proud of this code because it shortened reduced the requestAnimationFunction to just 4 lines and was cool to use a switch statement in JS.
  - [Nick's Code](https://github.com/nickpisciotta/game-time/blob/master/lib/index.js#L59-L75)

- Proud of this code because it was logically difficult to figure out how to make object speed and and increasing levels flexible, and infinitely increasing.
  - [Marcella's Code](https://github.com/nickpisciotta/game-time/blob/master/lib/game.js#L133-L143)

### Link to a specific block of your code on Github that you feel not great about
- Why do you feel not awesome about the code? What challenges did you face trying to write/refactor it?
  - This code is long, difficult to read what is happening and could be shortened by extracting some logic out.

  - [Code Link](https://github.com/nickpisciotta/game-time/blob/master/lib/player.js#L36-L49)

### Attach a screenshot or paste the output from your terminal of the result of your test-suite running.

![Link](http://g.recordit.co/JQAd16lulx.gif)

### Test Breakdown
- How Many Unit Tests?
  - 23/27
- How Many Feature/Integration Tests?
 -  4/27
 
### Provide a link to an example, if you have one, of a unit test that covers an 'edge case' or 'unhappy path'

[Unit Sad Path Tests](https://github.com/nickpisciotta/game-time/blob/master/test/player-test.js#L55-L77)

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
* 25 points - Application is fully playable without crashes or bugs
* 10 points - Application has some missing functionality but no crashes
* 0 points - Application crashes during normal usage

### User Interface

* 15 points - The application is pleasant, logical, and easy to use. There are no holes in functionality and the application stands on its own to be used by the instructor without guidance from the developer.
* 10 points - The application has many strong pages/interactions, but a few holes in lesser-used functionality.
* 5 points - The application shows effort in the interface, but the result is not effective. The evaluator has some difficulty using the application when reviewing the features in the user stories.
* 0 points - The application is confusing or difficult to use.

### Testing

* 30 points - Project has a running test suite that exercises the application at multiple levels. The test suite covers almost all aspects of the application and uses mocks and stubs when appropriate.
* 25 points - Project has a running test suite that tests multiple levels but fails to cover some features. All functionality is covered by tests. The application makes some use of integration testing.
* 10 points - Project has sporadic use of tests and multiple levels. The application contains numerous holes in testing and/or many features are untested.
* 0 points - There is little or no evidence of testing in this application.

### JavaScript Style

* 30 points - Application has exceptionally well-factored code with little or no duplication and all components are separated out into logical components. There zero instances where an instructor would recommend taking a different approach.
* 20 points - Application is thoughtfully put together with some duplication and no major bugs. Developer can speak to choices made in the code and knows what every line of code is doing.
* 15 points - Your application has a significant amount of duplication and one or major bugs.
* 5 points - Your client-side application does not function. Developer writes code with unnecessary variables, operations, or steps which do not increase clarity.
* 0 points - There is little or no client-side code. Developer writes code that is difficult to understand. Application logic shows poor decomposition with too much logic mashed together.

### Workflow

* 25 points - The developer effectively uses Git branches and many small, atomic commits that document the evolution of their application.
* 15 points - The developer makes a series of small, atomic commits that document the evolution of their application. There are no formatting issues in the code base.
* 10 points - The developer makes large commits covering multiple features that make it difficult for the evaluator to determine the evolution of the application.
* 5 points - The developer commited the code to version control in only a few commits. The evaluator cannot determine the evolution of the application.
* 0 points - The application was not checked into version control.

### Code Sanitation

The output from JSHint shows…

* 15 points - Zero complaints
* 10 points - Five or fewer complaints
* 5 points - Six to ten complaints
* 0 points - More than ten complaints
