# GameTime Submission Form

## Basics

### Link to the Github Repository for the Project
[Your Repo](https://github.com/PenneyGadget/game-time)

### Link to the Deployed Application
[Your Application](http://penneygadget.github.io/game-time/)

### Link to Your Commits in the Github Repository for the Project
[Penney](https://github.com/PenneyGadget/game-time/commits?author=PenneyGadget)

[Beth](https://github.com/PenneyGadget/game-time/commits?author=bethsebian)

### Provide a Screenshot of your Game
![Infinite Loop](http://i.imgur.com/twLFagW.png?1)

## Completion

### Do You Consider the Application to be Fully Playable?

 - Yes absolutely. We are super proud of this project and considered it complete even
 _before_ Beth built out the algorithm for levels to auto-generate themselves. In 24 hours
 no less. Amazeballs.

### What Extensions, as Requested By an Instructor, Did You Complete?

- Timing the player - you can see in the above screenshot that as a player finishes putting a pattern back together they are told how long it took them to complete the level.
- [Starting Timer](https://github.com/PenneyGadget/game-time/blob/master/lib/scripts/game.js#L111-L113#L139-L142)
- [Ending Timer/Game Length Calculation](https://github.com/PenneyGadget/game-time/blob/master/lib/scripts/game.js#L139-L142)


- We also added audio.

### What Features, if Any, Do You Feel Exceed Instructor Expectations?

 - Automatic level generator
 - [Pattern Generator Class](https://github.com/PenneyGadget/game-time/blob/master/lib/scripts/pattern-generator.js)

## Risk Taking

- What risks did you feel you took on this project?

Automating levels for sure. Beth took this on in the last 36 hours and rocked it. In that time I refactored, dealt with production, and added the level timer. It was really nice to be able to be the support and take care of "the laundry" while she explored her creative vision for finishing up the game. It was a huge risk because it very much could have failed, but it didn't and I'm so glad we went for it!

- How do you feel about those risks?

Awesome. Beth and I had a great dynamic. She is by far my favorite person I've worked with at Turing and I learned tons from her on this project.

## Code Quality

### Link to a specific block of your code on Github that you are proud of

[Tadpoles!](https://github.com/PenneyGadget/game-time/blob/master/lib/scripts/tadpole.js)
- Why were you proud of this piece of code?

Because of the logistical challenge it presented.

### Link to a specific block of your code on Github that you feel not great about

The 2 classes of code above... (Tadpole and Pattern Generator)
- Why do you feel not awesome about the code? What challenges did you face trying to write/refactor it?

Simply because this was done in a bit of a haste / in the 11th hour ad we have not yet had the chance to walk back through it to refactor.

[Game Class](https://github.com/PenneyGadget/game-time/blob/master/lib/scripts/game.js)

The above class could still use cleaning up and refactoring, despite the fact that (believe it or not), it has already been heavily refactored. The `playLevel` function used to be 2-3 times longer and, while it felt super great to extract the logic out of there, I know there's more that could be done and more that could be extracted from this class in general.

### Attach a screenshot or paste the output from your terminal of the result of your test-suite running.

![Test Suite](http://i.imgur.com/w794jR9.png?1)

### Test Breakdown
- How Many Unit Tests?

16

- How Many Feature/Integration Tests?

What was that? I can't hear you.

### Provide a link to an example, if you have one, of a unit test that covers an 'edge case' or 'unhappy path'

Could you please stop mumbling? I have no idea what you're saying.

-----

### Please feel free to ask any other questions or make any other statements below!

JavaScript yeeeeaaaahhHH!
Oh, why isn't my audio file working in production????

-----

## Instructor Feedback

- Points: (base 300)
