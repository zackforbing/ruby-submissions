# GameTime Submission Form

## Basics

### Link to the Github Repository for the Project
[Qbert Repo](http://github.com/s-espinosa/qbert)

### Link to the Deployed Application
[Qbert.rocks](http://www.qbert.rocks)

### Link to Your Commits in the Github Repository for the Project
-[Sal Espinosa](https://github.com/s-espinosa/qbert/commits?author=s-espinosa)
 -[Ling Tran](https://github.com/s-espinosa/qbert/commits?author=lingtran)
 -[Kami Boers](https://github.com/s-espinosa/qbert/commits?author=kamiboers)

### Provide a Screenshot of your Game
-![Qbert](http://g.recordit.co/Fp6N3jXEEG.gif)

---

## Completion

### Do You Consider the Application to be Fully Playable?
 Yes

### What Extensions, as Requested By an Instructor, Did You Complete?
- Animation of characters moving between squares:
  - Q*bert and enemies move jumpily between squares and off of the game board when they die.


### What Features, if Any, Do You Feel Exceed Instructor Expectations?
- Mobile Implementation:
  - Game can be played by touch on a mobile device.
  ![Mobile Interface](http://g.recordit.co/RgFsTL0wK7.gif)

----

## Risk Taking
- What risks did you feel you took on this project? How do you feel about those risks?
  We set ambitious goals and were able to achieve most of them. The game turned out well and is fun to play. We've gotten positive feedback after sharing it on slack.

----

## Code Quality

### Link to a specific block of your code on Github that you are proud of
[Ball Class](https://github.com/s-espinosa/qbert/blob/master/lib/ball.js)

- Why were you proud of this piece of code?
There's a considerable amount of work going on to make sure that a ball can both make decisions about where to move and then move itself from block to block. The update method contains the high level logic for these operations, but they are each broken out into smaller more digestible methods.

### Link to a specific block of your code on Github that you feel not great about
[index.js](https://github.com/s-espinosa/qbert/blob/master/lib/index.js)

- Why do you feel not awesome about the code? What challenges did you face trying to write/refactor it?
We spent quite a time working on our method to update the top scores at the end of each game. Ultimately this method calls on other functions that are left out in the open. We considered refactoring into another class. We liked the idea that these buttons are in the same file, but it might have helped to move all of the button-setting out into another file.


### Attach a screenshot or paste the output from your terminal of the result of your test-suite running.

```
> game-time-starter-kit@1.0.0 test /Users/Kami/turing/4module/qbert
> ./node_modules/mocha/bin/mocha --compilers js:babel/register



  Ball
    when initialized
      ✓ defaults to the second row of cubes
      ✓ defaults to alive
    death
      ✓ sets alive to false when it dies

  Board
    when initialized
      ✓ defaults to empty cube array
    initializing cubes
      ✓ populates with cube objects
      ✓ assigns neighbors relative to cube position

  Cube
    attributes without params
      ✓ defaults status to inactive
    attributes with params
      ✓ has an id
      ✓ has an x
      ✓ has an y
      ✓ has an upLeftId
      ✓ has an upRightId
      ✓ has an downLeftId
      ✓ has an downRightId

  Qbert
    when initialized
      ✓ defaults to the top cube
      ✓ defaults to no next position
      ✓ initializes with 3 lives
    on board
      ✓ moves down right
      ✓ moves down right
      ✓ moves down left
      ✓ moves up right

  Score
    when initialized
      ✓ defaults to a total of zero
    increments
      ✓ increments by any amount
    resets
      ✓ is zero after reset


  24 passing (26ms)
```


### Test Breakdown
- How Many Unit Tests?
19
- How Many Feature/Integration Tests?
5 - the On Board tests for Qbert and the "defaults to second row of cubes" each deal with both the characters they reference, and the board that they live on.


-----

## Instructor Feedback

- Points: (base 300)
- 
Functional Expectations

35 points - Application is fully playable and exceeds the expecations set by instructors

User Interface

15 points - The application is pleasant, logical, and easy to use. There no holes in functionality and the application stands on it own to be used by the instructor without guidance from the developer.

Testing

30 points - Project has a running test suite that exercises the application at multiple levels. The test suite convers almost all aspects of the application and uses mocks and stubs when appropriate.

JavaScript Style

25 points - Application is thoughtfully put together with some duplication and no major bugs. Developer can speak to choices made in the code and knows what every line of code is doing.

Workflow

25 points - The developer effectively uses Git branches and many small, atomic commits that document the evolution of their application.


The output from JSHint shows…

15 points - Zero complaints

295/300
