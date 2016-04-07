#Shrimpin' Ain't Easy || Submission Form

## Basics

### Link to the Github Repository for the Project
[GameTime](https://github.com/stevepentler/GameTime)

### Link to the Deployed Application
[Shrimpin' Ain't Easy](http://stevepentler.github.io/GameTime/)

### Link to Your Commits in the Github Repository for the Project
[Steve](https://github.com/stevepentler/GameTime/commits?author=stevepentler)
[David](https://github.com/stevepentler/GameTime/commits?author=dastinnette)

### Provide a Screenshot of your Game
[Shrimpin' Ain't Easy](http://i.imgur.com/kDdYfDo.png?1)

---

## Completion

### Do You Consider the Application to be Fully Playable?
 - Yes

### What Extensions, as Requested By an Instructor, Did You Complete?
Implement p5.js library:
- Describe the extension
- Provide a .gif of the extension or a link to the relevant code

### What Features, if Any, Do You Feel Exceed Instructor Expectations?
Per Feature:
 - Describe the feature
 - Provide a .gif of the feature in action or a link to the relevant code

----

## Risk Taking
- What risks did you feel you took on this project?
  - Implementing the p5 library
- How do you feel about those risks?
  - Memory leakage...

----

## Code Quality

### Link to a specific block of your code on Github that you are proud of
[Extracting functions from Game file](https://github.com/stevepentler/GameTime/blob/3aa670cb349737941a84ceaedb8ba5ffcd2b2875/lib/game.js#L42-L52)
- We extracted object move and draw functions into separate files reducing clutter in the main Game file.

### Link to a specific block of your code on Github that you feel not great about
[Bullet functions within Game file](https://github.com/stevepentler/GameTime/blob/3aa670cb349737941a84ceaedb8ba5ffcd2b2875/lib/game.js#L54-L73)
- We struggled extracting bullet functions out of the game file because each bullet relies on knowing the canvas height before another can be fired.

### Attach a screenshot or paste the output from your terminal of the result of your test-suite running.
[Tests on tests](http://i.imgur.com/sKnhN64.png?1)

### Test Breakdown
- How Many Unit Tests?
  - 22
- How Many Feature/Integration Tests?
  - 21

### Provide a link to an example, if you have one, of a unit test that covers an 'edge case' or 'unhappy path'
- All objects were given default values if none were explicitly provided, eliminating the need for most edge case testing.
### Provide a link to an example, if you have one, of a feature test that covers an 'edge case' or 'unhappy path'
[Ignores false collision](https://github.com/stevepentler/GameTime/blob/fd00c98af2c1b8caa89218856a58bc0323345fc7/test/collision-test.js#L95-L104)
- We tested direct hit collisions and partial collisions in the code above this segment and successfully tested misses report no collision here.

-----

### Please feel free to ask any other questions or make any other statements below!

-----

## Instructor Feedback

- Points: (base 300)
