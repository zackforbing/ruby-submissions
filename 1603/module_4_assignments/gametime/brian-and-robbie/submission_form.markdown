# GameTime Submission Form

## Basics

### Link to the Github Repository for the Project
[GameTime repo link](https://github.com/saylerb/game-time)

### Link to the Deployed Application
[Deployed application on gh-pages](https://saylerb.github.io/game-time/)

### Link to Your Commits in the Github Repository for the Project

-[Brian's commits](https://github.com/saylerb/game-time/commits?author=saylerb)
-[Robbie's commits](https://github.com/saylerb/game-time/commits?author=robbiejaeger)

### Provide a Screenshot of your Game

![Home Screen](http://i.imgur.com/f2WzIKf.jpg)
![Level Three](http://i.imgur.com/UEjhdEZ.jpg)

---

## Completion

### Do You Consider the Application to be Fully Playable?

 - Yes!

### What Extensions, as Requested By an Instructor, Did You Complete?
  - Multiplayer support with shared a keyboard 
     - blue is WASD
     - red is arrow keys
     -[Link to Keyboard Class that takes two inputs](https://github.com/saylerb/game-time/blob/master/lib/keyboard.js)

### What Features, if Any, Do You Feel Exceed Instructor Expectations?
 - Moving Spikes in Level 3: Difficult
   - The real game doesn't even have spikes!
 - Timed rounds with reverse progress bar, indicating how much time is left

----

## Risk Taking

- What risks did you feel you took on this project?
  - Websockets
    - we looked into doing websockets, and we got a setup to build with `nodemon` and `webpack --watch`
    - we probably should have looked into gulp if we wanted to develop a websockets game from the beginning 
    - realized at the beginning of this week that we wanted to work on polishing the existing game rather than trying to rush to get socket.io to work
  - Ball Physics 
    - implementing a game with somewhat realistic ball physics was a challenge
    - trig math for collisions was fun 
  - ES6 
    - We used classes and modules provided in ES6, which made OOP a little more enjoyable
    - ES6 caused some probablems with buidling in the beginning, but we figured it out pretty quickly 

----

## Code Quality

### Link to a specific block of your code on Github that you are proud of

- [Frictionless and inelastic collision detection](https://github.com/saylerb/game-time/blob/dev/lib/ball-collisions.js#L28)
- To make ball-ball collisions semi-realistic, we had to do some trig!
- Basically the equivalent of pool balls on perfectly frictionless ice-skating rink
- To simplify physics we took the following liberties:
    - No force/energy absorption on collisions (that would be more realistic)
    - No rolling or consideration of angular momentum

### Link to a specific block of your code on Github that you feel not great about

- [index.js in general](https://github.com/saylerb/game-time/blob/dev/lib/index.js)
- The challenge was removing the animation loop logic from within our game class, and we weren't sure how to design
  it so that it would be the more intuitive and flexible
- We wanted to be able to start new games outside the game class, previously the game class initiated itself

### Attach a screenshot or paste the output from your terminal of the result of your test-suite running.

![Game time testing suite](http://i.imgur.com/nECHWOY.png)

### Test Breakdown
- We have 41 total tests, unit vs. integration was about 50%-50%.

### Provide a link to an example, if you have one, of a unit test that covers an 'edge case' or 'unhappy path'

[Person cannot move left if colliding with wall](https://github.com/saylerb/game-time/blob/dev/test/player-test.js#L72)

### Provide a link to an example, if you have one, of a feature test that covers an 'edge case' or 'unhappy path'

-None

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

* **35 points - Application is fully playable and exceeds the expectations set by instructors**
* 25 points - Application is fully playable without crashes or bugs
* 10 points - Application has some missing functionality but no crashes
* 0 points - Application crashes during normal usage

### User Interface

* **15 points - The application is pleasant, logical, and easy to use. There are no holes in functionality and the application stands on its own to be used by the instructor without guidance from the developer.**
* 10 points - The application has many strong pages/interactions, but a few holes in lesser-used functionality.
* 5 points - The application shows effort in the interface, but the result is not effective. The evaluator has some difficulty using the application when reviewing the features in the user stories.
* 0 points - The application is confusing or difficult to use.

### Testing

* **30 points - Project has a running test suite that exercises the application at multiple levels. The test suite covers almost all aspects of the application and uses mocks and stubs when appropriate.**
* 25 points - Project has a running test suite that tests multiple levels but fails to cover some features. All functionality is covered by tests. The application makes some use of integration testing.
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
