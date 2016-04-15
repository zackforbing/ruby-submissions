# GameTime Submission Form

## Basics

### Link to the Github Repository for the Project
[Your Repo](https://github.com/ShannonPaige/turing-invaders)

### Link to the Deployed Application
[Your Application](http://shannonpaige.github.io/turing-invaders/)

### Link to Your Commits in the Github Repository for the Project
[Shannon](https://github.com/ShannonPaige/turing-invaders/commits?author=ShannonPaige)
[Slota](https://github.com/ShannonPaige/turing-invaders/commits?author=slotaj)

### Provide a Screenshot of your Game
![In Action](http://g.recordit.co/0wDW0O5E6S.gif)

---

## Completion

### Do You Consider the Application to be Fully Playable?
 - For Slota - yes. For Shannon - well, she feels it is difficult.

### What Extensions, as Requested By an Instructor, Did You Complete?
Alien Tentacles Moving:
- As the aliens move across the screen, we check which frame they are on and render the appropriate image.
- (Code)[https://github.com/ShannonPaige/turing-invaders/blob/master/lib/alien.js#L43-L47]

Multiple Types of Aliens:
- Each row is a different alien. We accomplish this by checking which part of the for loop we're in.
- (Code)[https://github.com/ShannonPaige/turing-invaders/blob/master/lib/alien.js#L9-L11]

Crazy Mode:
- The game keeps getting harder and harder until it's impossible to beat.
We did this by passing in the speed, fireRate and fireSpeed as variables that increase
each time a level is passed.
- (Code)[https://github.com/ShannonPaige/turing-invaders/blob/master/lib/level.js#L26-L32]

### What Features, if Any, Do You Feel Exceed Instructor Expectations?
Audio:
 - When the window loads, Bill Pullman's speech from Independence Day plays. We didn't think we were going
 to have time to implement audio, but we made it work
 - (Code)[https://github.com/ShannonPaige/turing-invaders/blob/master/lib/index.js#L3-L4]

----

## Risk Taking
- Working with Slota was a risk. :)
- We both felt really weak in js before the project started, so we didn't take too many crazy chances.
We just tried to write good code and make sure we understood it all.

----

## Code Quality

### Link to a specific block of your code on Github that you are proud of
- We think we did a good job of breaking up our code. It made it easy to implement new levels. In (this code)[https://github.com/ShannonPaige/turing-invaders/blob/master/lib/draw.js#L25-L47] we check the status of
game and update the tick function accordingly.

### Link to a specific block of your code on Github that you feel not great about
- There are so many variables declared in Draw that get passed around (code) [https://github.com/ShannonPaige/turing-invaders/blob/master/lib/draw.js#L25-L47], but there didn't seem to be away around that.

### Attach a screenshot or paste the output from your terminal of the result of your test-suite running.
!(Tests)[http://g.recordit.co/W603oNT4PJ.gif]

### Test Breakdown
- 28

### Provide a link to an example, if you have one, of a unit test that covers an 'edge case' or 'unhappy path'
- (Code)[https://github.com/ShannonPaige/turing-invaders/blob/master/test/alien-test.js#L55-L60]

### Provide a link to an example, if you have one, of a feature test that covers an 'edge case' or 'unhappy path'
- No
-----

### Please feel free to ask any other questions or make any other statements below!
- We set out to make a version of Space Invaders that was as close as possible to the original. I think we
accomplished that, while both learning a lot about JavaScript and how to write good oo code.
- We still don't feel super confident about testing in JavaScript and would have like to have done better on that.

-----

## Instructor Feedback

- Points: (base 300)
