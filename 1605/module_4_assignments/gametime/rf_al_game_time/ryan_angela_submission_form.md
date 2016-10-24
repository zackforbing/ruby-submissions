# GameTime Submission Form

## Basics

### Link to the Github Repository for the Project
[Jeepney Jump on GitHub](https://www.github.com/ryanflach/jeepney_jump)

### Link to the Deployed Application
[Play Jeepney Jump](https://ryanflach.github.io/jeepney_jump)

### Link to Your Commits in the Github Repository for the Project
- [Ryan Flach](https://github.com/ryanflach/jeepney_jump/commits?author=ryanflach)
- [Angela Lindow](https://github.com/ryanflach/jeepney_jump/commits?author=allindow)

### Provide a Screenshot of your Game
![JeepneyJump](http://i.imgur.com/dCy2sTS.jpg)

---

## Completion

### Do You Consider the Application to be Fully Playable?
 - Yes, and somewhat beyond an MVP. There was additionally going to be functionality that enabled the player to pick up and drop off passengers; however, this idea was scrapped somewhat early on, as the new direction of the game didn't really lend itself to that functionality.

### What Extensions, as Requested By an Instructor, Did You Complete?
- Parallax Scrolling:
  - Early on, it was suggested that we attempt to implement some parallax scrolling, to add more convincing movement along the 2D boulevard. Originally, we had anticipated implementing this at the bottom of the canvas, but this did not fully make sense within the context of our game and was distracting to the user experience. Instead, we chose to implement as clouds at the top of the canvas. This may have not fully achieved the principle behind parallax scrolling, but it had the desired effect.
  - [Link to low-quality GIF of effect](http://recordit.co/BE27HeqQOG)

### What Features, if Any, Do You Feel Exceed Instructor Expectations?
- Bonus Items:
 - A player's primary objective is to survive as long as possible by avoiding obstacles. Points are earned based on time survived. Bonus items were introduced to regenerate health or provide point bonuses. Bonus items are introduced at a different interval than all other objects (every 5 seconds) and float vertically. An additional graphical enhancement to bonus items provides visual feedback to the user as to whether or not the bonus netted them health or points. This is accomplished by changing the graphic to either a heart or text of '+500 pts' that stops at the x position where the collision occurred and then floats up and out of the top of the canvas.
 - [Same GIF as above](http://recordit.co/BE27HeqQOG)

----

## Risk Taking
- What risks did you feel you took on this project?
  - Truly, this project was intentionally played somewhat safe. Somewhat from inspiration from the talk given by Tom Dale, we decided early on that our priority was to complete a simple, enjoyable and good-looking web application, rather than a feature-rich game that was not visually appealing or enjoyable for those without any understanding of the code behind the project.
- How do you feel about those risks?
  - This was still a strong learning experience, and we were able to explore many things that we were previously entirely unfamiliar with. Although I am satisfied with our final product, I believe the game's simplicity will be apparent to those familiar with JavaScript, and in that respect I believe it could have been beneficial to have attempted something more difficult, even if it had led to partial failure.

----

## Code Quality

### Link to a specific block of your code on Github that you are proud of
- [Game startUp prototype method](https://github.com/ryanflach/jeepney_jump/blob/master/lib/game.js#L33-L38)
- Why were you proud of this piece of code?
  - There were not an overwhelming amount of times in this project where we produced clean, efficient, readable code that did not at least partially repeat itself elsewhere. This is an instance of clean, readable code that serves a single responsibility and is not coupled or reproduced elsewhere. Additionally, the use of `setInterval` is unique to this method, and allowed for functionality that would have been more expensive if implemented within the various `set` or `generate` prototype methods that exist for generating other objects.

### Link to a specific block of your code on Github that you feel not great about
- [Game generateClouds & generateBackgroundObjects prototype methods](https://github.com/ryanflach/jeepney_jump/blob/master/lib/game.js#L56-L76)
- Why do you feel not awesome about the code? What challenges did you face trying to write/refactor it?
  - This code smells, and it is an example of a theme that ran throughout the project. Both of these methods are performing nearly identical tasks, with subtle differences. Refactoring would have been possible, but due to time restrictions, refactoring was limited to (even) more low-hanging fruit, so to speak.

### Attach a screenshot or paste the output from your terminal of the result of your test-suite running.
![Test Suite Results](http://i.imgur.com/DmX1qF1.png)
- Note that the test suite _only_ runs in the browser.

### Test Breakdown
- How Many Unit Tests?
  - 120
- How Many Feature/Integration Tests?
  - 0

### Provide a link to an example, if you have one, of a unit test that covers an 'edge case' or 'unhappy path'
- [Jeepney does not jump if currently jumping](https://github.com/ryanflach/jeepney_jump/blob/master/test/jeepney_test.js#L89-L98)

### Provide a link to an example, if you have one, of a feature test that covers an 'edge case' or 'unhappy path'
- N/A

-----

### Please feel free to ask any other questions or make any other statements below!

Due to life circumstances beyond the control of either team member, it was not possible to attain full engagement of the team. With that in mind, I am happy with and proud of the final product; however, the code has obvious weaknesses: testing is not robust, it is restricted to the unit level, and it is available only in the browser; code is not as DRY as it could be; refactoring was not done to the extent that I would have liked.

Despite these limitations, the final product features nearly every feature we had initially hoped to produce, and the user experience is both pleasant and, I believe, somewhat professional. The use of images and sound effects helped greatly in this regard. Although not specified in any user story, the addition of sprites, in place of static images, would be a welcomed addition.

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
* __30 points - Application is fully playable without crashes or bugs__
* 10 points - Application has some missing functionality but no crashes
* 0 points - Application crashes during normal usage

### User Interface

* __15 points - The application is pleasant, logical, and easy to use. There are no holes in functionality and the application stands on its own to be used by the instructor without guidance from the developer.__
* 10 points - The application has many strong pages/interactions, but a few holes in lesser-used functionality.
* 5 points - The application shows effort in the interface, but the result is not effective. The evaluator has some difficulty using the application when reviewing the features in the user stories.
* 0 points - The application is confusing or difficult to use.

### Testing

* 30 points - Project has a running test suite that exercises the application at multiple levels. The test suite covers almost all aspects of the application and uses mocks and stubs when appropriate.
* __25 points - Project has a running test suite that tests multiple levels but fails to cover some features. All functionality is covered by tests. The application makes some use of integration testing.__
* 10 points - Project has sporadic use of tests and multiple levels. The application contains numerous holes in testing and/or many features are untested.
* 0 points - There is little or no evidence of testing in this application.

### JavaScript Style

* 30 points - Application has exceptionally well-factored code with little or no duplication and all components are separated out into logical components. There zero instances where an instructor would recommend taking a different approach.
* __25 points - Application is thoughtfully put together with some duplication and no major bugs. Developer can speak to choices made in the code and knows what every line of code is doing.__
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

total = 135
