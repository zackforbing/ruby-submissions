# GameTime Submission Form

## Basics

### Link to the Github Repository for the Project
[Repo](https://github.com/cheljoh/game-time)

### Link to the Deployed Application
[Game Link](http://cheljoh.github.io/game-time/)

### Link to Your Commits in the Github Repository for the Project
[Chelsea](https://github.com/cheljoh/game-time/commits/master?author=cheljoh)

[July](https://github.com/cheljoh/game-time/commits/master?author=julyytran)

### Provide a Screenshot of your Game
![GO GO NYAN CAT](http://g.recordit.co/Wt9UG9rpVn.gif)

## Completion

### Do You Consider the Application to be Fully Playable?

 - Yes, very user friendly and easy to understand! Simply move up and down to eat sushi or avoid trash. Use spacebar to deploy bomb and clear all sprites.

### What Extensions, as Requested By an Instructor, Did You Complete?

- We discussed hiding an API key which we were able to successfully complete. We also discussed having lasers or bombs- we decided on bombs. July also worked on having a moving cat gif to the game- adds a lot! Moving background was also  not completely necessary but it adds a lot to the experience.
- See above gif for bombs and moving cat gif. We wouuld add a link to how we hid API key, but it's in .gitignore- SUCCESS!


### What Features, if Any, Do You Feel Exceed Instructor Expectations?

 - Bombs, cat gif, audio, Firebase, and moving background. See above gif!

## Risk Taking

- What risks did you feel you took on this project?

Adding a moving background involved stacking two canvases on top of each other and increasing overall complexity of the game. Moving cat gif also increased complexity for collision and drawing the object. We also spent a lot of time configuring Firebase and allowing users to enter their name.

- How do you feel about those risks?

Learned a lot from them! Glad we did them.

## Code Quality

### Link to a specific block of your code on Github that you are proud of

[refreshSprites](https://github.com/cheljoh/game-time/blob/refactoring-party-3/lib/game.js#L64-L74)
- Why were you proud of this piece of code?

Small function that is very important to the game. We reset sprites array in each frame so we don't have a memory issue. 

### Link to a specific block of your code on Github that you feel not great about

[moveSpites](https://github.com/cheljoh/game-time/blob/refactoring-party-3/lib/game.js#L76-L92)

- Why do you feel not awesome about the code? What challenges did you face trying to write/refactor it?

This is a important function that is long by necessity and difficult to test. We broke out as many functions as we could.

### Attach a screenshot or paste the output from your terminal of the result of your test-suite running.

![Test Suite](images/test-suite.png)

### Test Breakdown
- How Many Unit Tests?
40

- How Many Feature/Integration Tests?
1


### Provide a link to an example, if you have one, of a unit test that covers an 'edge case' or 'unhappy path'

[Sad path](https://github.com/cheljoh/game-time/blob/refactoring-party-3/test/cat-test.js#L29-L40)

-----

### Please feel free to ask any other questions or make any other statements below!


-----

## Instructor Feedback

- Points: (base 300)

#### Playability Features

We want your game to be full-featured and playable -- not just a proof of concept of the gameplay and rendering features.

To this end, make sure to include sufficient UX to allow the user to fully interact with the game. This would include:

Indicate when the game is over and won or lost
Allow the user to start a new game
Include a clean UI surrounding the actual game interface itself
Score Tracking: How this works will vary by game, but at the end of the game, generate a score for the winning player
Scoreboard -- track scores across multiple game sessions. Since we aren't incorporating a server for our games, client-side storage like a cookie or LocalStorage will suffice.
Create multiple rounds of difficulty. (consider increasing factors such as game speed, randomness of starting setup, etc)

#### Extensions

Create an AI player that can play as the second player (except in 2048).
Multiplayer support -- either by sharing a keyboard (2 sets of key inputs) or, as an extra-difficult extension, via websockets between multiple browsers

#### Evaluation Rubric

There are 300 total available points for this project.

150 are available at each of three check-ins and are at instructor descretion.

Teams must complete the submission form prior to each check-in.

150 out of a total of 300 points are included in the rubric below. The additional 150 feature points will be determined during iteration planning with instructors during check-ins.

#### Functional Expectations

35 points - Application is fully playable and exceeds the expecations set by instructors
- Bombs are a great addition, really fun game, works very well. Great job!

#### User Interface

15 points - The application is pleasant, logical, and easy to use. There no holes in functionality and the application stands on it own to be used by the instructor without guidance from the developer.
- SO GOOD. Great use of imagery, good color use, really great job. Very fun game.

#### Testing

30 points - Project has a running test suite that exercises the application at multiple levels. The test suite convers almost all aspects of the application and uses mocks and stubs when appropriate.
25 points - Project has a running test suite that tests and multiple levels but fails to cover some features. All functionality is covered by tests. The application makes some use of integration testing.
10 points - Project has sporadic use of tests and multiple levels. The application contains numerous holes in testing and/or many features are untested.
0 points - There is little or no evidence of testing in this application.

#### JavaScript Style

30 points - Application has exceptionally well-factored code with little or now duplication and all components separated out into logical components. There zero instances where an instructor would recommend taking a different approach.
20 points - Application is thoughtfully put together with some duplication and no major bugs. Developer can speak to choices made in the code and knows what every line of code is doing.
15 points - Your application has a significant amount of duplication and one or major bugs.
5 points - Your client-side application does not function. Developer writes code with unnecessary variables, operations, or steps which do not increase clarity.
0 points - There is little or no client-side code. Developer writes code that is difficult to understand. Application logic shows poor decomposition with too much logic mashed together.

#### Workflow

25 points - The developer effectively uses Git branches and many small, atomic commits that document the evolution of their application.
15 points - The developer makes a series of small, atomic commits that document the evolution of their application. There are no formatting issues in the code base.
10 points - The developer makes large commits covering multiple features that make it difficult for the evaluator to determine the evolution of the application.
5 points - The developer commited the code to version control in only a few commits. The evaluator cannot determine the evolution of the application.
0 points - The application was not checked into version control.

#### Code Sanitation

The output from JSHint shows…

15 points - Zero complaints
10 points - Five or fewer complaints
5 points - Six to ten complaints
0 points - More than ten complaints
