Complete this Form before the final eval. Delete this line from your version.

# GameTime Submission Form

## Basics

### Link to the Github Repository for the Project
[Game Time](https://github.com/brennanholtzclaw/game_time)

### Link to the Deployed Application
[Puts-Puts](https://brennanholtzclaw.github.io/game_time/#)

### Link to Your Commits in the Github Repository for the Project
 - [Heidi's Commits](https://github.com/brennanholtzclaw/game_time/commits/master?author=hhoopes)
 - [Nate's Commits](https://github.com/brennanholtzclaw/game_time/commits/master?author=natevenn)
 - [Brennan's Commits](https://github.com/brennanholtzclaw/game_time/commits/master?author=brennanholtzclaw)

### Provide a Screenshot of your Game
![Get in your hole!](https://drive.google.com/file/d/0BzOa44Ah0W0IaTZ6aWtPeUdRUVU/view?usp=sharing "Fun for the whole family!")

---

## Completion

### Do You Consider the Application to be Fully Playable?
 - Puts-Puts is a fully playable game with three levels, and more in the works. Pull your cursor back from the ball like a club, then click to swing. "Puts" that ball right in the hole!

### What Extensions, as Requested By an Instructor, Did You Complete?
- Sand Traps:
  - We wanted to incorporate something a little more exciting in the design of a hole, so we implemented an obstacle in the form of sand traps on the first level. This involved a special collision detection, and different hampering of movement, but only while in the trap.
  - [Sand Trap!](http://g.recordit.co/wTpqyHbhtS.gif)

### What Features, if Any, Do You Feel Exceed Instructor Expectations?
* Easy addition of new levels
While this was a pattern we saw used elsewhere, level creation required customizing for our own needs. It allows all required elements to be created in a easily repeatable pattern.
[Link](https://github.com/brennanholtzclaw/game_time/tree/master/lib/levels)

----

## Risk Taking
- What risks did you feel you took on this project?

     I think the biggest risk we took was trying to write certain functions for ourselves. When it comes to collision detection, a ball slowing down or being affected by a trap, or even drawing multiple objects, those problems are all solved. We decided we wanted to try and figure them out on our own though to make sure we learned the most we could.

- How do you feel about those risks?
<p>
    Because we had to struggle through some areas that could possibly have been solved faster, I don't think we got as far as we hoped. There are other obstacles that should be much easier to implement now, and other features that we could probably get to fairly quickly, but time escaped us.
</p>
----

## Code Quality

### Link to a specific block of your code on Github that you are proud of
- Why were you proud of this piece of code?
[Bumper Collision](https://github.com/brennanholtzclaw/game_time/blob/master/lib/ball.js#L58-L64)

This code not only iterates over the bumbers and obstacles to detect a collision, but also makes it easy to introduce new `bumper.type`s in the future.

### Link to a specific block of your code on Github that you feel not great about
- Why do you feel not awesome about the code? What challenges did you face trying to write/refactor it?

[That's a lot of variables](https://github.com/brennanholtzclaw/game_time/blob/master/lib/index.js#L1-L27)

Declaring that many variables in the top of a file is the smelliest of code smells that things need to be pulled out into new files/functions, and required differently. Also in this file is the animation loop. Nate did a great job refactoring that, but the whole index is still pretty cluttered with things that need some desperate pruning. We just ran into problems getting specific functions pulled out, and still working correctly in our loop.

### Attach a screenshot or paste the output from your terminal of the result of your test-suite running.
[Link to pastebin](http://pastebin.com/KQPqpvCu)
I was not able to debug this, but one file of my tests only runs when run solo, and fails as a suite. I suspect it's something to do with clean up on the tests, but wasn't able to identify it. This only represents 5 tests.

### Test Breakdown
- How Many Unit Tests?
Roughly 31

- How Many Feature/Integration Tests?
- Roughly 9


### Provide a link to an example, if you have one, of a unit test that covers an 'edge case' or 'unhappy path'
[Unit test of collision detection on (literally) a corner case](https://github.com/brennanholtzclaw/game_time/blob/master/test/balls_in_obstacles_test.js)

### Provide a link to an example, if you have one, of a feature test that covers an 'edge case' or 'unhappy path'

-----

### Please feel free to ask any other questions or make any other statements below!

-----

## Instructor Feedback

- Points: (base 300)
