# GameTime Submission Form

## Basics

### Link to the Github Repository for the Project
[Game Time Repo](https://github.com/kbs5280/game-time)

### Link to the Deployed Application
[UFO](https://kbs5280.github.io/game-time/)

### Link to Your Commits in the Github Repository for the Project
[Kris Sparks](https://github.com/kbs5280/game-time/commits/master?author=kbs5280)
[Matt Packer](https://github.com/kbs5280/game-time/commits/master?author=matthewrpacker)

### Provide a Screenshot of your Game
![UFO GIF](http://recordit.co/LLHJUB8U51.gif)

## Completion

### Do You Consider the Application to be Fully Playable?
 - Yes.  The application is fully playable without external guidance.  There are no gaps in the player experience.  The game exceeds base requirements.

### What Extensions, as Requested By an Instructor, Did You Complete?
- N/A

### What Features, if Any, Do You Feel Exceed Instructor Expectations?
- Obstacle Asteroid Image:
  - All flying danger obstacles have been replaced with asteroid images.
  - [Lines 12 to 19](https://github.com/kbs5280/game-time/blob/9a9a574011ddc5174d7f292de34bcc4e11647c4f/lib/game.js#L12-L19)
  - [Lines 175 to 179](https://github.com/kbs5280/game-time/blob/9a9a574011ddc5174d7f292de34bcc4e11647c4f/lib/game.js#L175-L179)
- Star Image:
  - All flying bonus obstacles have been replaced with star images.
  - [Lines 21 to 28](https://github.com/kbs5280/game-time/blob/9a9a574011ddc5174d7f292de34bcc4e11647c4f/lib/game.js#L21-L28)
  - [Lines 181 to 185](https://github.com/kbs5280/game-time/blob/9a9a574011ddc5174d7f292de34bcc4e11647c4f/lib/game.js#L181-L185)
- Obstacle Asteroid Collision Response:
  - Upon colliding with an asteroid, initiate an explosion sound.
  - [Lines 290 to 295](https://github.com/kbs5280/game-time/blob/9a9a574011ddc5174d7f292de34bcc4e11647c4f/lib/game.js#L290-L295)
- Bonus Star Collision Response:
  - Upon colliding with a star, initiate a bonus sound and increase points.
  - [Lines 315 to 318](https://github.com/kbs5280/game-time/blob/9a9a574011ddc5174d7f292de34bcc4e11647c4f/lib/game.js#L315-L318)

## Risk Taking
- What risks did you feel you took on this project?
  - After we reached MVP:
    - We modified our danger obstacle flight behavior.  For example, instead of just traversing the x-axis at a certain y co-ordinate, we chose to have some danger obstacles traverse both the x and y axis.
    - We added bonus point obstacles.  By adding these obstacles, we had to build in additional collision detection that coordinated with our scoring system.
    - We modified our UFO object from a rectangle to two ellipses, i.e. one ellipse is the top portion of the UFO object and the other ellipse is the bottom portion of the UFO object.  By modifying how we were drawing the UFO, we had to modify our collision detection to account for each ellipse.
- How do you feel about those risks?
  - We feel good that we were able to set challenging goals and accomplish those goals.  Seeing the process from ideation to production was rewarding.

## Code Quality

### Link to a specific block of your code on Github that you are proud of
- Why were you proud of this piece of code?
- [Lines 20 to 22](https://github.com/kbs5280/game-time/blob/9a9a574011ddc5174d7f292de34bcc4e11647c4f/lib/obstacle.js#L20-L22)
- First, we added speed as an attribute to Obstacle.  Then, we created a prototype on Obstacle `speedModifier`.  The speed modifier accepts a number and increases the obstacles speed based on the number passed.  We were proud that we were able to rethink our initial implementation to adhere to object oriented JavaScript principles.

### Link to a specific block of your code on Github that you feel not great about
- Why do you feel not awesome about the code? What challenges did you face trying to write/refactor it?
- [Lines 175 to 185](https://github.com/kbs5280/game-time/blob/9a9a574011ddc5174d7f292de34bcc4e11647c4f/lib/game.js#L175-L185)
- Based on the similarities between these two conditionals, `if(asteroidReady)` and `if(starReady)`, we feel like this was a missed refactoring opportunity.  Our challenge was the we have four variables in a function that is not dynamic.

### Attach a screenshot or paste the output from your terminal of the result of your test-suite running.
![Test Suite](test-suite.png)

### Test Breakdown
- How Many Unit Tests? 19
- How Many Feature/Integration Tests? 4

### Provide a link to an example, if you have one, of a unit test that covers an 'edge case' or 'unhappy path'
- N/A

### Provide a link to an example, if you have one, of a feature test that covers an 'edge case' or 'unhappy path'
- N/A

### Please feel free to ask any other questions or make any other statements below!
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
* **28 points - Application is fully playable without crashes or bugs**
* 10 points - Application has some missing functionality but no crashes
* 0 points - Application crashes during normal usage

### User Interface

* **15 points - The application is pleasant, logical, and easy to use. There are no holes in functionality and the application stands on its own to be used by the instructor without guidance from the developer.**
* 10 points - The application has many strong pages/interactions, but a few holes in lesser-used functionality.
* 5 points - The application shows effort in the interface, but the result is not effective. The evaluator has some difficulty using the application when reviewing the features in the user stories.
* 0 points - The application is confusing or difficult to use.

### Testing

* 30 points - Project has a running test suite that exercises the application at multiple levels. The test suite covers almost all aspects of the application and uses mocks and stubs when appropriate.
* **27 points - Project has a running test suite that tests multiple levels but fails to cover some features. All functionality is covered by tests. The application makes some use of integration testing.**
* 10 points - Project has sporadic use of tests and multiple levels. The application contains numerous holes in testing and/or many features are untested.
* 0 points - There is little or no evidence of testing in this application.

### JavaScript Style

* 30 points - Application has exceptionally well-factored code with little or no duplication and all components are separated out into logical components. There zero instances where an instructor would recommend taking a different approach.
* **20 points - Application is thoughtfully put together with some duplication and no major bugs. Developer can speak to choices made in the code and knows what every line of code is doing.**
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

* **15 points - Zero complaints**
* 10 points - Five or fewer complaints
* 5 points - Six to ten complaints
* 0 points - More than ten complaints
