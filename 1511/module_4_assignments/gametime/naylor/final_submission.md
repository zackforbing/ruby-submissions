# GameTime Submission Form

## Team Naylor

## Basics

### Link to the Github Repository for the Project

[GameTime](https://github.com/Tman22/game-time)

### Link to the Deployed Application

[Cannonz](http://tman22.github.io/game-time/)

### Link to Your Commits in the Github Repository for the Project

- [tman22](https://github.com/Tman22/game-time/commits?author=tman22)
- [NickyBobby](https://github.com/Tman22/game-time/commits?author=NickyBobby)

### Provide a Screenshot of your Game

- ![Cannonz](./images/new_game.png)
- ![GamePlay](http://g.recordit.co/MTt0kmvPYy.gif)
- ![HighScore](./images/new_game.png)

---

## Completion

### Do You Consider the Application to be Fully Playable?
 - Yes. We fixed all bugs around collision detection. We have a definite beginning and end. Also, the game gets increasingly difficult as it goes on.

### What Extensions, as Requested By an Instructor, Did You Complete?
- Per Extension:
  - We were given a stretch goal of having a third level. We added the third level and made it super difficult to complete. All targets move.
  - ![GamePlay](http://g.recordit.co/MTt0kmvPYy.gif)

### What Features, if Any, Do You Feel Exceed Instructor Expectations?
- Per Feature:
 - Not sure if anything exceeds instructor expectations

----

## Risk Taking
- The risks that we took on this project were mainly getting the trajectory of the cannon ball to look realistic and mimic gravity.
- We feel the risk was well worth it. It took us a long time in the beginning to figure that out, but we did it. We then tinkered with it til it was just right.

----

## Code Quality

### Link to a specific block of your code on Github that you are proud of
- Why were you proud of this piece of code?
- [super clean index.js](https://github.com/Tman22/game-time/blob/master/lib/index.js#L1-38)

### Link to a specific block of your code on Github that you feel not great about
- Nothing really comes to mind, but I'm sure you will tell us what's wrong. Mainly we're just a little bummed that we couldn't get the high score board implemented but we'll do it in the next few days just for funzies.

### Attach a screenshot or paste the output from your terminal of the result of your test-suite running.

### Test Breakdown
- 55 Unit tests
- ![55](http://g.recordit.co/j5jSxrG6bN.gif)

### Provide a link to an example, if you have one, of a unit test that covers an 'edge case' or 'unhappy path'
- [Crucial Unhappy Paths](https://github.com/Tman22/game-time/blob/master/test/collision_test.js#L10-38)
- These tests were crucial for figuring out what was wrong with our collision detection woes.

### Provide a link to an example, if you have one, of a feature test that covers an 'edge case' or 'unhappy path'

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
Evaluation Rubric

There are 300 total available points for this project.

150 are available at each of three check-ins and are at instructor descretion.

Teams must complete the submission form prior to each check-in.

150 out of a total of 300 points are included in the rubric below. The additional 150 feature points will be determined during iteration planning with instructors during check-ins.

#### Functional Expectations

35 points - Application is fully playable and exceeds the expecations set by instructors

#### User Interface

13 points - The application is pleasant, logical, and easy to use. There no holes in functionality and the application stands on it own to be used by the instructor without guidance from the developer.

#### Testing

30 points - Project has a running test suite that exercises the application at multiple levels. The test suite convers almost all aspects of the application and uses mocks and stubs when appropriate.

#### JavaScript Style

30 points - Application has exceptionally well-factored code with little or now duplication and all components separated out into logical components. There zero instances where an instructor would recommend taking a different approach.

#### Workflow

25 points - The developer effectively uses Git branches and many small, atomic commits that document the evolution of their application.

#### Code Sanitation

The output from JSHint shows…

15 points - Zero complaints
