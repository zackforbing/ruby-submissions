# GameTime Submission Form

## Basics

### Link to the Github Repository for the Project
[Your Repo](https://github.com/kjs222/gametime)

### Link to the Deployed Application
[Your Application](https://kjs222.github.io/gametime/)

### Link to Your Commits in the Github Repository for the Project
-[Kerry](https://github.com/kjs222/gametime/commits?author=kjs222&since=2016-10-01T06:00:00Z&until=2016-10-20T06:00:00Z)

 -[Jenny](https://github.com/kjs222/gametime/commits?author=MsJennyGiraffe&since=2016-10-01T06:00:00Z&until=2016-10-20T06:00:00Z)

### Provide a Screenshot of your Game
![binarysnake](http://img.photobucket.com/albums/v466/soulfire3490/BinarySnake.png)

---

## Completion

### Do You Consider the Application to be Fully Playable?
 - Yes
   * It has all traditional snake functionality decided upon:
    * If you hit a wall you die.
    * Get bigger when eating food
  * New rules for gameplay:
    * Two bits available. Eat the correct bit in the conversion of a decimal number to binary.
    * If you incorrectly eat a bit you get smaller, if you eat the correct one you get bigger.
  * It has a sorted leaderboard that displays the top ten players.
  * It has a scoring system.
    * One point per correct bit eaten as well as when you covert a number correctly, the number translated in decimal gets added to your score.
  * It gets increasingly more difficult as the game progresses.

### What Extensions, as Requested By an Instructor, Did You Complete?
- Per Extension:
  - We didn't think of an extension to do, and we mostly wanted to focus on polish.

### What Features, if Any, Do You Feel Exceed Instructor Expectations?
- Per Feature:
 - I don't think any particular feature exceeds Instructor expectations. I think the game is impressive as a whole, and there are a lot of little things that make this game great between the twist on traditional snake and the theme that ties it together.

----

## Risk Taking
- What risks did you feel you took on this project?
    - I think it was a risk to try to make an educational game. We both wanted to do it, but educational games risk being boring, and unimpressive. I think taking the traditional snake game and making it into something else was a risk. It's something neither of us had seen before and didn't know exactly what it could be.
    (Especially Kerry because she didn't know what snake was before this project.)
- How do you feel about those risks?
  * I feel great. I am so proud of what we have accomplished in the past week and a half. We were able to be creative and create our own game within something known, and we have gotten positive responses so far. I'm glad others seem to enjoy it too.

----

## Code Quality

### Link to a specific block of your code on Github that you are proud of
- https://github.com/kjs222/gametime/blob/master/lib/render.js#L37
  * We are proud of this recursive method of drawing the snake on the canvas. Because we used a linked list, we were able to take concepts from module 1 and implement them into a project. It's been awhile since we've had projects that contain hard logic and data structures, this project is full of them and I'm proud of that.

### Link to a specific block of your code on Github that you feel not great about
- https://github.com/kjs222/gametime/blob/master/lib/snake.js#L44

  * I'm not so happy with this code. It's a giant case statement, and the variables are named in a certain way because the linter complained about them. We tried refactoring this.tail out of the method because it's repeated multiple times, but it didn't work the way we thought it would.

### Attach a screenshot or paste the output from your terminal of the result of your test-suite running.

![testing](http://g.recordit.co/bZ5d9skopE.gif)

### Test Breakdown
- How Many Unit Tests?
72

- How Many Feature/Integration Tests?
34

### Provide a link to an example, if you have one, of a unit test that covers an 'edge case' or 'unhappy path'

[Edge Case](https://github.com/kjs222/gametime/blob/master/test/snake-test.js#L52-58)

### Provide a link to an example, if you have one, of a feature test that covers an 'edge case' or 'unhappy path'

[Edge Case](https://github.com/kjs222/gametime/blob/master/test/game-test.js#L326)
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
* **25 points - Application is fully playable without crashes or bugs**
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
* **23 points - Application is thoughtfully put together with some duplication and no major bugs. Developer can speak to choices made in the code and knows what every line of code is doing.**
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

* **14 points - One complaints**
* 10 points - Five or fewer complaints
* 5 points - Six to ten complaints
