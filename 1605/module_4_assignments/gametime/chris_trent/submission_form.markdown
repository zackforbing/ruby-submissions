# GameTime Submission Form

## Basics

### Team
- [Trent](https://github.com/twhitinger)
- [Chris](https://github.com/concach)

### Github Repository
[Github Repository](https://github.com/concach/game-time)

### Deployed Application
[Lyger Woods 2017](http://concach.github.io/game-time)

### Link to Your Commits in the Github Repository for the Project
-[Chris](https://github.com/concach/game-time/commits?author=concach)
 -[Trent](https://github.com/concach/game-time/commits?author=twhitinger)

### Provide a Screenshot of your Game
-![Lyger Woods 2017 Gameplay](figures/game-time-submission-1.png)
-![Lyger Woods 2017 Menu](figures/game-time-submission-2.png)

---

## Completion

### Do You Consider the Application to be Fully Playable?
 - Yes

### What Extensions, as Requested By an Instructor, Did You Complete?
 - none, but we did modify our random obstacle generator to make holes more difficult, randomly

### What Features, if Any, Do You Feel Exceed Instructor Expectations?
- Functional Expectations:
 - The game plays with sounds and interactive user input that requires skill
 - Every hole in the game will be different due to random obstacle generation between the hole and the ball, even though the hole and ball stay in the same place
 - The game has multiple types of obstacles that interact with the ball differently - sand pits slow the ball down, while trees and the hole walls deflect the ball

- JavaScript Style:
 - The game is broken out into logical components based on the requirements of that particular moment in the game. For example, each round includes 9 different instances of PlayHole, and each instance of PlayHole contains up to 10 individual Strokes, and each Stroke has new instances of the power and direction inputs. The "brains" behind the game interactions largely reside in the PlayHole constructor.

- Testing:
 - The game is thoroughly tested for each unit, and integration-tested wherever possible.

----

## Risk Taking
- Having re-rendering of holes during the game without a page refresh was quite a challenge
- We overcame the challenges. Given more time, we could definitely add more features and further refactor our code, but we believe this is a solid foundation for an easily-expandable miniature golf game

----

## Code Quality

### Link to a specific block of your code on Github that you are proud of
[code](https://github.com/concach/game-time/blob/master/test/play-hole-test.js#L32-L77)
- This demonstrates our solid testing of the stroke tallying and instantiation, and the hole-object interactions (including the all-important ball-in-hole). We like this code because it not only demonstrates thorough testing, but it also demonstrates the logical way we broke out functions on the ball to allow for these interactions to play out in an arena with many objects.

### Link to a specific block of your code on Github that you feel not great about
[code](https://github.com/concach/game-time/blob/master/lib/play-golf.js#L30-L58)
- This code is present, in one way or another, in pretty much every one of our .js files. Our game operates on the basis of objects calling .update() and .draw() at the appropriate time. We feel that this is repetitive and could be refactored somehow.

### Test suite
![Test Suite](figures/game-time-submission-tests.png)

### Test Breakdown
- 42 Total Tests + 4 that won't run due to sinon loading problems
- 4 operational, + 4 that won't run due to sinon loading problems

### Provide a link to an example, if you have one, of a unit test that covers an 'edge case' or 'unhappy path'
[link](https://github.com/concach/game-time/blob/master/test/ball-test.js#L51-L65)

### Provide a link to an example, if you have one, of a feature test that covers an 'edge case' or 'unhappy path'
[link](https://github.com/concach/game-time/blob/master/test/play-hole-test.js#L56-L77)
- note: We believe that by providing detailed failure messages, this should count as "sad path" testing

-----

### Please feel free to ask any other questions or make any other statements below!
- Would really like to figure out why sinon won't load with mocha
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
