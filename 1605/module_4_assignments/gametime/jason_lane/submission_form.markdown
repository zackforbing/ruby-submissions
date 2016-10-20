# GameTime Submission Form

## Basics

### Link to the Github Repository for the Project
[Your Repo](https://github.com/Automatic365/gametime)

### Link to the Deployed Application
[Your Application](https://automatic365.github.io/gametime/)

### Link to Your Commits in the Github Repository for the Project
-[Jason Hanna](https://github.com/Automatic365/gametime/commits/master?author=Automatic365)
 -[Lane Winham](https://github.com/Automatic365/gametime/commits/master?author=Laner12)

### Provide a Screenshot of your Game
![](http://i.imgur.com/sFpGkyx.gif)

---

## Completion

### Do You Consider the Application to be Fully Playable?
 - Yes, judging by the rubric we believe it to be fully playable.

### What Extensions, as Requested By an Instructor, Did You Complete?
- No extensions were executed

### What Features, if Any, Do You Feel Exceed Instructor Expectations?
As a group we exceeded what we thought we would produced, however being new to JavaScript I am not sure where an instructor would fall.

- Per Feature:
 - random generation of enemies and powerups
 -[generation code](https://github.com/Automatic365/gametime/blob/master/lib/game.js#L14-L26)

 - enemies looping the canvas
 -[enemy loop](https://github.com/Automatic365/gametime/blob/master/lib/enemy.js#L19-L37)

 - player moves with mouse
 -[player update](https://github.com/Automatic365/gametime/blob/master/lib/player.js#L18-L28)

----

## Risk Taking

- What risks did you feel you took on this project?

    * Picking a game that relies heavily on trajectory and speed


- How do you feel about those risks?

    * I think we executed the mimicked functionality well, and the final product is fun to play

----

## Code Quality

### Link to a specific block of your code on Github that you are proud of
![](http://i.imgur.com/cU5pw5Z.png)
- Why were you proud of this piece of code?
    * We had two similar methods and had a successful refactor by finding the difference and making those differences the arguments for the new method.

### Link to a specific block of your code on Github that you feel not great about
![](http://i.imgur.com/KV0LLgy.png)
- Why do you feel not awesome about the code? What challenges did you face trying to write/refactor it?
    * Our attempt to refactor the methods, however we ran out of time to get this method functioning
![](http://i.imgur.com/FdPoCym.png)

### Attach a screenshot or paste the output from your terminal of the result of your test-suite running.

### Test Breakdown
![](http://i.imgur.com/ZDAYuYE.png)

- How Many Unit Tests?
    * 24
    
- How Many Feature/Integration Tests?

    * 1 attempted commented out

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
* __27 points - Application is fully playable without crashes or bugs__
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
* __20 points - Application is thoughtfully put together with some duplication and no major bugs. Developer can speak to choices made in the code and knows what every line of code is doing.__
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

total = 122
