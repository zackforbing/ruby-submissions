# GameTime Submission Form

## Basics

### Link to the Github Repository for the Project
[zackforbing / game_time](https://github.com/zackforbing/game_time)

### Link to the Deployed Application
[Your Application](https://zackforbing.github.io/game_time/)

### Link to Your Commits in the Github Repository for the Project
-[Zack](https://github.com/zackforbing/game_time/commits?author=zackforbing)
 -[Yoseph](https://github.com/zackforbing/game_time/commits?author=Yoyo2Code)

### Provide a Screenshot of your Game
-[timefreeze](https://postimg.org/image/vye3qs9dd/)

---

## Completion

### Do You Consider the Application to be Fully Playable?
 - Yes, the game is fully functional.

### What Extensions, as Requested By an Instructor, Did You Complete?
- No Extensions

### What Features, if Any, Do You Feel Exceed Instructor Expectations?
- hurdles!

----

## Risk Taking
- What risks did you feel you took on this project?

    I feel like the scope of this project was too much for the time that we had to work with. a lot of cool features ended up being left off, but we did complete the MVP.

- How do you feel about those risks?

    I think we probably should have chosen something a bit simpler and then added
    features to it as we completed the MVP. However, we are happy with how much we accomplished, and given a bit more time, think we could probably implement a lot of the features that our game is missing compared to the original.

----

## Code Quality

### [Link to a block of code you're proud of](https://github.com/zackforbing/game_time/blob/017f27c5092464b044dac5358e43207b0ce1755b/lib/hurdle.js#L1)
- Why were you proud of this piece of code?

    I (Zack) built this entire class from scratch in a code spike, and aside from the draw, it all worked first try, so I was pretty proud of that.

### [Link to a block of code you're not proud of](https://github.com/zackforbing/game_time/blob/017f27c5092464b044dac5358e43207b0ce1755b/lib/game.js#L8)
- Why do you feel not awesome about the code? What challenges did you face trying to write/refactor it?

    time did not allow us to refactor this. and that's really why I'm not proud of it. it seems like some code, the key listeners in particular, could use some serious refactoring.

### Attach a screenshot or paste the output from your terminal of the result of your test-suite running.

### Test Breakdown
- How Many Unit Tests? 37 passing tests.
- How Many Feature/Integration Tests? none.

### Provide a link to an example, if you have one, of a unit test that covers an 'edge case' or 'unhappy path'

    we do not have one.

### Provide a link to an example, if you have one, of a feature test that covers an 'edge case' or 'unhappy path'

    we do not have one.

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
* __25 points - Application is fully playable without crashes or bugs__
* 10 points - Application has some missing functionality but no crashes
* 0 points - Application crashes during normal usage

### User Interface

* 15 points - The application is pleasant, logical, and easy to use. There are no holes in functionality and the application stands on its own to be used by the instructor without guidance from the developer.
* __10 points - The application has many strong pages/interactions, but a few holes in lesser-used functionality.__
* 5 points - The application shows effort in the interface, but the result is not effective. The evaluator has some difficulty using the application when reviewing the features in the user stories.
* 0 points - The application is confusing or difficult to use.

### Testing

* 30 points - Project has a running test suite that exercises the application at multiple levels. The test suite covers almost all aspects of the application and uses mocks and stubs when appropriate.
* 25 points - Project has a running test suite that tests multiple levels but fails to cover some features. All functionality is covered by tests. The application makes some use of integration testing.
* __20 points - use of stubs is good for trying to test features - no collision detection tests which brings this score down a little__
* 10 points - Project has sporadic use of tests and multiple levels. The application contains numerous holes in testing and/or many features are untested.
* 0 points - There is little or no evidence of testing in this application.

### JavaScript Style

* 30 points - Application has exceptionally well-factored code with little or no duplication and all components are separated out into logical components. There zero instances where an instructor would recommend taking a different approach.
* __19 points - Application is thoughtfully put together with some duplication and no major bugs. Developer can speak to choices made in the code and knows what every line of code is doing.__
* 15 points - Your application has a significant amount of duplication and one or major bugs.
* 5 points - Your client-side application does not function. Developer writes code with unnecessary variables, operations, or steps which do not increase clarity.
* 0 points - There is little or no client-side code. Developer writes code that is difficult to understand. Application logic shows poor decomposition with too much logic mashed together.

### Workflow

* __23 points - The developer effectively uses Git branches and many small, atomic commits that document the evolution of their application.__
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

total: 112
