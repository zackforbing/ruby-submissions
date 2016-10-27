# GameTime Submission Form

## Basics

### Link to the Github Repository for the Project
[Your Repo](https://github.com/chompasina/gametime)

### Link to the Deployed Application
[Your Application](https://chompasina.github.io/gametime/)

### Link to Your Commits in the Github Repository for the Project
-[Tommasina](https://github.com/chompasina/gametime/commits?author=chompasina)
 -[Karina](https://github.com/chompasina/gametime/commits?author=karinamzalez)
 -[Deb](https://github.com/chompasina/gametime/commits?author=deborahleehamel)

### Provide a Screenshot of your Game
-![Empty Calorie Overlord and the Healthy Food Revival](http://g.recordit.co/H0IIYTd0YT.gif)
---

## Completion

### Do You Consider the Application to be Fully Playable?
 - Yes.
 * It has agreed upon functionality.
 * Player can collect healthy foods on tray which increases health points on meter/progress bar.
 * Player can collect junk foods on tray but this decreases health points on meter/progress bar.
 * There are 3 levels. Players move to next level and win the game when their health food points reach >=600.
 * Scores are tracked and displayed on screen.
 * High scores board(scores above 600) on screen.
 

### What Extensions, as Requested By an Instructor, Did You Complete?
- Per Feature:
 - No assigned extensions.

### What Features, if Any, Do You Feel Exceed Instructor Expectations?
- Per Feature:
 - Our Healthy Foods/Empty Calorie Overlord progress bar was difficult to implement but adds to user experience as an intuitive feature.
 - The oscillation of the "Empty Calorie Overlord" gave us substantial challenge in coordinating the movement of the junk food. We hope that our initial sprite for "el Cheeto Diablo" (Donald Trump starring as "Empty Calorie Overlord") exceeded instructor expectations as well.

----

## Risk Taking
- We took a risk with the oscillating overlord and associating the junk food objects with the overlord's position.
- We tackled the challenges and learned so much about coordinating timed events and managing intervals and the states that every little piece are in at different moments in the game. 
- We wanted this project to be connected to our Pahlka posse and got a good start on special documentation specifically geared toward the posse project. We prioritized building functionality and will be able to follow up with a playable game that the posse can integrate and continue to work on.
- So many sprites! Dealing with assets, transparency, sizing, image quality, etc. was more than we realized.
----

## Code Quality

### Link to a specific block of your code on Github that you are proud of
https://github.com/chompasina/gametime/blob/development/lib/index.js#L64-L83
 * We are proud of this code because it was really hard to figure out how to make the junk food increase in a random way. We had to play around with timing in three spots: setInterval for the Overlord, the requestAnimationFrame timing, and the new timing interval for oscillating the overlord for increasing difficulty throughout the game. We had to play around with the numbers a lot to make sure the overlord didn't speed up too quickly and overpopulate the board with junk food objects. We think what resulted was a very natural evolution to a more difficult game towards the end. 


### Link to a specific block of your code on Github that you feel not great about
https://github.com/chompasina/gametime/blob/development/lib/index.js#L85-L101
 * This code feels like a cop-out because it feels like there should be a better way to reset the requestAnimationFrame (the cancel function is an "experimental" function that didn't work consistently for us even though we passed in the requestAnimationFrame ID). Instead we are looping through the window and clearing all of the setIntervals for every object. We also just manually wipe the health food and junk food arrays clean which could have been handled by a master stop-game-play function instead. Because we don't know true game conventions, we're not sure if this is an acceptable way to end the game or not. 

### Attach a screenshot or paste the output from your terminal of the result of your test-suite running.
![testing](http://g.recordit.co/eDDKpnS17E.gif)

### Test Breakdown
- How Many Unit Tests?
 * 56 passing
- How Many Feature/Integration Tests?
 * 4 passing

### Provide a link to an example, if you have one, of a unit test that covers an 'edge case' or 'unhappy path'
[Edge Case](https://github.com/chompasina/gametime/blob/development/test/junk-food-test.js#L33-L36)

### Provide a link to an example, if you have one, of a feature test that covers an 'edge case' or 'unhappy path'
[Edge Case](https://github.com/)

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

* __33 points - Application is fully playable and exceeds the expectations set by instructors__ - Documentation was really solid. Definitely above and beyone expectations
* 25 points - Application is fully playable without crashes or bugs
* 10 points - Application has some missing functionality but no crashes
* 0 points - Application crashes during normal usage

### User Interface

* __15 points - The application is pleasant, logical, and easy to use. There are no holes in functionality and the application stands on its own to be used by the instructor without guidance from the developer.__
* 10 points - The application has many strong pages/interactions, but a few holes in lesser-used functionality.
* 5 points - The application shows effort in the interface, but the result is not effective. The evaluator has some difficulty using the application when reviewing the features in the user stories.
* 0 points - The application is confusing or difficult to use.

### Testing

* 30 points - Project has a running test suite that exercises the application at multiple levels. The test suite covers almost all aspects of the application and uses mocks and stubs when appropriate.
* __23 points - Project has a running test suite that tests multiple levels but fails to cover some features. All functionality is covered by tests. The application makes some use of integration testing.__ 

* dropped a few points for missing some core functionality from the tests (capturing food on tray/collision)

* 10 points - Project has sporadic use of tests and multiple levels. The application contains numerous holes in testing and/or many features are untested.
* 0 points - There is little or no evidence of testing in this application.

### JavaScript Style

* 30 points - Application has exceptionally well-factored code with little or no duplication and all components are separated out into logical components. There zero instances where an instructor would recommend taking a different approach.
* __17 points - Application is thoughtfully put together with some duplication and no major bugs. Developer can speak to choices made in the code and knows what every line of code is doing.__
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

total = 128
