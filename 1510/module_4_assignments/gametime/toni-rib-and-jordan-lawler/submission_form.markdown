# GameTime Submission Form

## Basics

### Link to the Github Repository for the Project
[Your Repo](https://github.com/ToniRib/game_time)

### Link to the Deployed Application
[Your Application](http://tonirib.github.io/game_time/)

### Link to Your Commits in the Github Repository for the Project
[Toni](https://github.com/ToniRib/game_time/commits/master?author=ToniRib)

[Jordan](https://github.com/ToniRib/game_time/commits/master?author=Jlawlzz)

### Provide a Screenshot of your Game
![Super Happy Animal Food Time](/1510/module_4_assignments/gametime/toni-rib-and-jordan-lawler/images/super_happy_animal_food_time.png)

---

## Completion

### Do You Consider the Application to be Fully Playable?

 - Absolutely! And it's fun, too!

### What Extensions, as Requested By an Instructor, Did You Complete?

Per Extension:
- I don't think we ever had extensions explicitly requested. At checkin 3 we were asked to refactor engine.js which we did and removed about 200 lines of code from that file.

### What Features, if Any, Do You Feel Exceed Instructor Expectations?

Per Feature:
 - The gif animations! There's a lot of different animations going on to show when a tower is shooting and most towers are also shooting directly toward the enemies.
 - [Animation](https://github.com/ToniRib/game_time/blob/master/lib/animation.js)
 - [Animation Engine](https://github.com/ToniRib/game_time/blob/master/lib/animation-engine.js)

----

## Risk Taking

- What risks did you feel you took on this project?
  - We chose a game that hadn't been done at Turing before (at least that we had ever seen) and that would require a lot of real time animations and visual feedback. It really let us turn this game from something mildly interesting to something that's actually fun to play!
- How do you feel about those risks?
  - We think they turned out great! We could have easily only done the basics, which is where we were late last week, but the game wasn't much fun to play because you had no idea when a tower was shooting.

----

## Code Quality

### Link to a specific block of your code on Github that you are proud of

[Enemy Shooting Functionality](https://github.com/ToniRib/game_time/blob/ef84e7fa1701a2ac3979b1f68d98142fdfe12533/lib/tower.js#L6-L36)

One of the first things we had to do when making the game was figure out how to get the towers to shoot only at enemies within their range and only after a certain amount of time has passed. I think we did a pretty good job by coming up with a way to determine if they are able to shoot and a way to figure out which enemies are close enough to shoot at (but are also on the visible canvas).

### Link to a specific block of your code on Github that you feel not great about

[Board Tile Highlighting](https://github.com/ToniRib/game_time/blob/ef84e7fa1701a2ac3979b1f68d98142fdfe12533/lib/board.js#L60-L72)

This code got messy pretty quickly because there are so many cases to consider. We wanted to highlight build tiles one color if they were vacant and another color if they had a tower on them, but we also had to make sure we would only have one tile highlighted at a time. Since there are so many possibilities, we ended out having this big if statement in the Board object which I don't like it.

### Attach a screenshot or paste the output from your terminal of the result of your test-suite running.

It's easier to show it in the browser since that is what we used.

![Game Time Tests](/1510/module_4_assignments/gametime/toni-rib-and-jordan-lawler/images/game_time_tests.png)

### Test Breakdown
- How Many Unit Tests?
- How Many Feature/Integration Tests?

I don't really know how to answer this because we didn't split them up into separate folders. We had 188 tests overall.

### Provide a link to an example, if you have one, of a unit test that covers an 'edge case' or 'unhappy path'

[Tower Cannot Fire Case](https://github.com/ToniRib/game_time/blob/99fd221221aa04c690d3108259a99b8242ef2eab/test/continuous-fire-tower-test.js#L58-L63)

### Provide a link to an example, if you have one, of a feature test that covers an 'edge case' or 'unhappy path'

[Edge Case](https://github.com/ToniRib/game_time/blob/99fd221221aa04c690d3108259a99b8242ef2eab/test/board-test.js#L59-L73)

-----

### Please feel free to ask any other questions or make any other statements below!

-----

## Instructor Feedback

- Points: (base 300)
