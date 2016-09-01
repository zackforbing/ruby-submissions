# GameTime Submission Form

## Basics

### Link to the Github Repository for the Project
#### [TyprrBurn Repo](https://github.com/jeneve/typrr-burn)

### Link to the Deployed Application
#### [TyprrBurn Deploy](https://jeneve.github.io/typrr-burn/)

### Link to Your Commits in the Github Repository for the Project
#### [Jeneve's commits](https://github.com/jeneve/typrr-burn/commits/master?author=jeneve)
#### [Marina's commits](https://github.com/jeneve/typrr-burn/commits/master?author=marinacor1)

### Provide a Screenshot of your Game
#### [TyprrBurn Screen Recording](http://recordit.co/bni8wbO2My)

---

## Completion

### Do You Consider the Application to be Fully Playable?
#### Yes, there are 6 levels, each increases in difficulty. The instructions are clear and gameplay is intuitive.

### What Extensions, as Requested By an Instructor, Did You Complete?
#### [he bird and the background are animated](http://recordit.co/hsVk47AOD8)

### What Features, if Any, Do You Feel Exceed Instructor Expectations?
#### Concept:
- We created a game not modeled after any other game. It's intuitive and addictive. It serves a purpose- helping one become a better typist.

#### code:

- [highlighting of players progress through the text they are typing](https://github.com/jeneve/typrr-burn/blob/master/lib/keystroke.js#L52)

----

## Risk Taking
#### Scrolling the screen and layering the canvases was a risk because there weren't examples that were particularly useful.

- [code](https://github.com/jeneve/typrr-burn/blob/master/lib/game.js#L19)

----

## Code Quality

### Link to a specific block of your code on Github that you are proud of

#### [rendering the text](https://github.com/jeneve/typrr-burn/blob/master/lib/level.js#L36)

### Link to a specific block of your code on Github that you feel not great about

#### [There's too many things happening here. It's hard to refactor because it's the moment when all the classes need to collaborate](https://github.com/jeneve/typrr-burn/blob/master/lib/level.js#L92)

### Attach a screenshot or paste the output from your terminal of the result of your test-suite running.

- [Tests](https://s3-us-west-1.amazonaws.com/ideabox/Screen+Shot+2016-07-13+at+3.41.29+PM.png)

### Test Breakdown
#### How Many Unit Tests?
30
#### How Many Feature/Integration Tests?
0

### Provide a link to an example, if you have one, of a unit test that covers an 'edge case' or 'unhappy path'

#### [backspace doesn't blow everything up](https://github.com/jeneve/typrr-burn/blob/master/test/keystroke-test.js#L82)

### Please feel free to ask any other questions or make any other statements below!

-----

## Instructor Feedback

165/150

## Playability Features

## Extensions

* **25 points** - Playable and unique game - beyond expectations

### Functional Expectations

* **35 points** - Application is fully playable and exceeds the expecations set by instructors

### User Interface

* **15 points** - The application is pleasant, logical, and easy to use. There no holes in functionality and the application stands on it own to be used by the instructor _without_ guidance from the developer.

### Testing

* **30 points** - Project has a running test suite that exercises the application at multiple levels. The test suite convers almost all aspects of the application and uses mocks and stubs when appropriate.

### JavaScript Style

* **20 points** - Application is thoughtfully put together with some duplication and no major bugs. Developer can speak to choices made in the code and knows what every line of code is doing.

### Workflow

* **25 points** - The developer effectively uses Git branches and many small, atomic commits that document the evolution of their application.

### Code Sanitation

The output from JSHint shows…

* **15 points** - Zero complaints
