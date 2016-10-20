# GameTime Submission Form

## Basics

### Link to the Github Repository for the Project
[Your Repo](https://github.com/dtinianow/slime_volleyball)

### Link to the Deployed Application
[Your Application](https://dtinianow.github.io/slime_volleyball/)

### Link to Your Commits in the Github Repository for the Project
-[David](https://github.com/dtinianow/slime_volleyball/commits?author=dtinianow)
 -[Matt](https://github.com/dtinianow/slime_volleyball/commits?author=matthewecampbell)

### Provide a Screenshot of your Game
-![](https://camo.githubusercontent.com/6538c3d74a65d54fdb4ec5ea2ff9e5404db0d315/687474703a2f2f672e7265636f726469742e636f2f7032344c7732496746332e676966)

---

## Completion

### Do You Consider the Application to be Fully Playable?
 - Our application is fully playable and, in our humble opinion, think it is quite fun!  Users have the option of competing head to head in normal or insane mode. A single player user also has the option of taking on the computer in normal mode.  If we had more time, an extension we would have liked to implement would have been using websockets to create multi-player capability.

### What Extensions, as Requested By an Instructor, Did You Complete?
- Multiplayer support
  - Two users can play each other using the keyboard.  The user on the left uses the WASD keys to move, and the user of the right uses the arrow keys move.  The first slime to reach seven points wins.  Our game keeps track of the match score.
  - [Code Link](https://github.com/dtinianow/slime_volleyball/blob/master/lib/scripts/slime.js#L108-#L118)
  
- Create an AI player that can play as the second player
  - We created a slime AI that an individual player can play against in both normal mode and insane mode.  The slime responds fairly well to ball movement, and can even jump when the ball is close.  The AI has some slight bugginess, and vibrates too much when trying to decide whether to move left or right.  Overall though, this behavior does not affect gameplay, and the AI behavior serves as a good challenge to an individual human player.
  - [Code Link](https://github.com/dtinianow/slime_volleyball/blob/master/lib/scripts/slime.js#L109-#L151)

### What Features, if Any, Do You Feel Exceed Instructor Expectations?
- Slime Jumping:
  - For our MVP, our plan was to make each slime be able to move horizontally along the ground.  In our final game, each slime can jump and is properly affected by gravity.  The slimes also have full ball collision detection while they are airborn.  This was tricky to implement since the user is controlling the slime and  we had to make sure that the slime falls back down to the ground even if the user continues to push the up arrow key.
  - [Code Link](https://github.com/dtinianow/slime_volleyball/blob/master/lib/scripts/slime.js#L205-#L217)
 
 - Extensions
   - We felt we went above the standard project expectations by implementing the two extensions listed above.  It was a good challenge and it makes the game more enjoyable for the user, since it can be played by either one or two players.
   - Check the extension section above for relevant code snippets
   
- Bonus features:
   - We could have made a simple Slime Volleyball clone, but decided to level up our game by adding some bonus features.  In normal mode, a user can change the background of their environment by pushing any key 1-9.  In insane mode, the background changes color when the ball collides with the walls, the slimes change color when they collide with the ball, the ball becomes huge when it collides with the net, and on game point the winning slime shrinks to give the losing slime an advantage.  We think these details make the game much more vibrant and visually exciting and had a lot of fun implementing them.
----

## Risk Taking
- What risks did you feel you took on this project?
   - We felt the project as a whole was a pretty big risk.  Initially we thought the scope of Slime Volleyball might be too large to complete in under two weeks.  The main risks we imagined were getting the slimes to jump, implementing collision detection for the slimes with the ball, adding AI, and making our game compatible for two players. 
- How do you feel about those risks?
   - We were excited to take on these challenges and they were fun to figure out.  Implementing the two player functionality was easier than we imagined, but the other risks were about on par with what we expected.

----

## Code Quality

### Link to a specific block of your code on Github that you are proud of
- [Code Link](https://github.com/dtinianow/slime_volleyball/blob/master/lib/scripts/slime.js#L205-#L217)
- Why were you proud of this piece of code?
- This link goes to the code that allows a Slime to jump.  We mentioned this code above in the section we feel exceeds expectations too, because this was one of the more challenging components of this project.  Figuring out this code was particularily gratifying.

### Link to a specific block of your code on Github that you feel not great about
- [Code Link](https://github.com/dtinianow/slime_volleyball/blob/master/lib/scripts/slime.js#L122-#L151)
- Why do you feel not awesome about the code? What challenges did you face trying to write/refactor it?
- We feel mixed about this code, because while figuring out the AI was pretty cool, it's still a bit buggy and could use refactoring.  This was an extension so it was the most recent feature we added.  If we had more time, we would certainly be able to work out the kinks and refactor this code.

### Attach a screenshot or paste the output from your terminal of the result of your test-suite running.
![](http://i.imgur.com/jgHFCJj.png)
### Test Breakdown
- How Many Unit Tests?
55
- How Many Feature/Integration Tests?
0

### Provide a link to an example, if you have one, of a unit test that covers an 'edge case' or 'unhappy path'

[Sad Path](https://github.com/dtinianow/slime_volleyball/blob/master/test/game-test.js#L89-L110)

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

* **29 points - Project has a running test suite that exercises the application at multiple levels. The test suite covers almost all aspects of the application and uses mocks and stubs when appropriate.**
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
