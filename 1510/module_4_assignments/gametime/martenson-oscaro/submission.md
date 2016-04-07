# GameTime Submission Form

## Basics

### Link to the Github Repository for the Project
[Jezz Ball](https://github.com/StevOscar/game_time)

### Link to the Deployed Application
[Jezz Ball Deployed](steveoscar.github.io/game_time)

### Link to Your Commits in the Github Repository for the Project
[Steve's Commits](https://github.com/SteveOscar/game_time/commits?author=SteveOscar)
[Brenna's Commits](https://github.com/SteveOscar/game_time/commits?author=martensonbj)

### Provide a Screenshot of your Game
![JezzBall](http://g.recordit.co/gF4yV6qh4F.gif)

---

## Completion

### Do You Consider the Application to be Fully Playable?
 - Yes. Play moves on to multiple levels and user can lose and save high score.

### What Extensions, as Requested By an Instructor, Did You Complete?
Per Extension:
- No extensions were requested

### What Features, if Any, Do You Feel Exceed Instructor Expectations?
- A ball can escape around a building wall without losing the level.

----

## Risk Taking
- What risks did you feel you took on this project?
  - There were sections of code that we could have left as is and saved a lot of time and debugging, however we chose to dive in and really work on refactoring and understanding what the code was doing to become more familiar with JavaScript.

----

## Code Quality

### Link to a specific block of your code on Github that you are proud of
- Why were you proud of this piece of code?
  [Collision Detection Helper Methods](https://github.com/SteveOscar/game_time/blob/gh-pages/lib/collision-helper.js)
    - This was a great refactoring session for us. It helped us really break down what was happening when and understand which pieces of the puzzle affected each other. It changed how the rest of our application was structured significantly and greatly simplified methods across the app.

### Link to a specific block of your code on Github that you feel not great about
- Why do you feel not awesome about the code? What challenges did you face trying to write/refactor it?
  [Large Game Method](https://github.com/SteveOscar/game_time/blob/gh-pages/lib/zeus.js#L39-L67)
  - This piece of code checks for how much canvas is left. It has a ton of variables and a lot of integrated methods that proved to be very difficult to separate and test. We eventually had to abandon refactoring this method in order to complete game functionality but at some point need to pull out verbose sections into smaller pieces.

### Attach a screenshot or paste the output from your terminal of the result of your test-suite running.
![Testing](http://g.recordit.co/7mm0Es2wV7.gif)

### Test Breakdown
- How Many Unit Tests?
- 38

### Provide a link to an example, if you have one, of a unit test that covers an 'edge case' or 'unhappy path'
[Edge Case Test](https://github.com/SteveOscar/game_time/blob/gh-pages/test/wall-helper-test.js#L22-L31)

-----

## Instructor Feedback

- Points: (base 300)
