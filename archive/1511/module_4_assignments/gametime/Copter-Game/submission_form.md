# GameTime Submission Form

## Basics

### Link to the Github Repository for the Project
[Our Repo](https://github.com/damwhit/helicopter-time)

### Link to the Deployed Application
[Our Application](https://damwhit.github.io/helicopter-time/)

### Link to Your Commits in the Github Repository for the Project
-[David](https://github.com/damwhit/helicopter-time/commits?author=damwhit)
 -[Brian](https://github.com/damwhit/helicopter-time/commits?author=brianrip)

### Action shot
![Helicopter Time](./game-action.jpg)

---

## Completion

### Do You Consider the Application to be Fully Playable?
 - Yes, and quite enjoyable!

### What Extensions, as Requested By an Instructor, Did You Complete?
- Gaining bonuses to slow game

### What Features, if Any, Do You Feel Exceed Instructor Expectations?
- Style:
 - Taking the time to implement a smooth and pleasurable UX
 - Spent time on the danger mode and shooting extensions

 [code](https://github.com/damwhit/helicopter-time/blob/master/assets/stylesheets/index.css)
----

## Risk Taking
- We took risks by investing time in extensions such as the shooting and danger mode.
- I feel that we approached the extra time spent wisely so that we still delivered a solid project without sacrificing any functionality.

----

## Code Quality

### Link to a specific block of your code on Github that you are proud of

[code](https://github.com/damwhit/helicopter-time/blob/master/lib/game.js)  
- We spent considerable effort on attempting to follow single responsibility principles by extracting code out of our game loop into respective classes and private functions.

### Link to a specific block of your code on Github that you feel not great about

[code](https://github.com/damwhit/helicopter-time/blob/master/index.html)
- Why do you feel not awesome about the code? What challenges did you face trying to write/refactor it?
- I feel like using more semantic tags would have been useful for arranging content to be more maintainable.

### Attach a screenshot or paste the output from your terminal of the result of your test-suite running.

### Test Breakdown
- How Many Unit Tests?

  _25_

### Provide a link to an example, if you have one, of a unit test that covers an 'edge case' or 'unhappy path'

[code](https://github.com/damwhit/helicopter-time/blob/master/test/boundary-test.js)

-----

### Please feel free to ask any other questions or make any other statements below

- We invested a fair amount of time into extensions that still have bugs but served as a good learning experience

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

14 points - The application is pleasant, logical, and easy to use. There no holes in functionality and the application stands on it own to be used by the instructor without guidance from the developer.
- Really beautiful button.
- Great improvements to visuals, 1 point docked because making fireballs could vary in size to add to visual interest/difficulty

#### Testing

20 points - Project has a running test suite that tests and multiple levels but fails to cover some features. All functionality is covered by tests. The application makes some use of integration testing.

#### JavaScript Style

25 points - Application has exceptionally well-factored code with little or now duplication and all components separated out into logical components. There zero instances where an instructor would recommend taking a different approach.

#### Workflow

25 points - The developer effectively uses Git branches and many small, atomic commits that document the evolution of their application.

#### Code Sanitation

The output from JSHint shows…

10 points - Five or fewer complaints
