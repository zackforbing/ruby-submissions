# GameTime Submission Form

## Basics

### Link to the Github Repository for the Project
[Color Wars](https://github.com/lucyfox4131/color-wars)

### Link to the Deployed Application
[Deployed Application](https://lucyfox4131.github.io/color-wars/)

### Link to Your Commits in the Github Repository for the Project
-[Lucy Fox](https://github.com/lucyfox4131/color-wars/commits?author=lucyfox4131)
-[Erin Greenhalgh](https://github.com/lucyfox4131/color-wars/commits?author=ErinGreenhalgh)

### Provide a Screenshot of your Game
-![Color Wars](http://g.recordit.co/QtXL7hYGHU.gif)

---

## Completion

### Do You Consider the Application to be Fully Playable?
 - The application is fully playable, minus a button that lets you replay the game. Right now users just have to refresh to replay the game.

### What Extensions, as Requested By an Instructor, Did You Complete?
- No extensions.

### What Features, if Any, Do You Feel Exceed Instructor Expectations?
- Our user interface looks baller, if we do say so ourselves.

----

## Risk Taking
- We took on the game without any idea of what it would entail and found it much more difficult than we expected.

----

## Code Quality

### Link to a specific block of your code on Github that you are proud of
- [DomManager](https://github.com/lucyfox4131/color-wars/blob/master/lib/dom_manager.js)
- We put a great effort into refactoring, because our game class contained most of the logic for rendering the pattern, determining whether the level was over, scoring, moving on to the next level, and rendering the appropriate things on the DOM. We broke out the logic for rendering onto the DOM into a DOM manager to make things much more isolated and easier to debug down the line.

### Link to a specific block of your code on Github that you feel not great about
- [Calculating Color Values](https://github.com/lucyfox4131/color-wars/blob/995130e2b36965c2db7330fa937f241c11c11d64/lib/color_filler.js#L72-L89)
- This is a pretty long method that takes in many things and then makes variables from those things, which we're not a big fan of. It iterates through each block on the pattern and then checks if the block is either the user color, or one of the computer colors. Ideally this method would be flexible to iterate through any number of colors, thus getting rid of some repetition and making this more flexible. We just couldn't get this figured out in time. 

### Attach a screenshot or paste the output from your terminal of the result of your test-suite running.
``` javascript 
Block
    with default attributes
      ✓ should have an x value
      ✓ should have a y value
      ✓ should have a width value
      ✓ should have a height value
      ✓ should have a default shape value of false
      ✓ should have a default null child
      ✓ should have a default null parent
    with given attributes
      ✓ should have an x value
    with some attributes given
      ✓ should have an x value
    can change a blocks color
      ✓ should have default grey
      ✓ should be blue if color is changed
    knows its coordinates
      ✓ should return a single coordinates
      ✓ should return correct coordinates
    knows if it contains coordinate
      ✓ should return true if it contains given coordinate
      ✓ should return false if not contained
    can change the color of its neighbor block
      ✓ to its own color

  Color Filler
    has the correct attributes
      ✓ with a pattern
      ✓ with a current block
    can handle connections
      ✓ by determining if a block is a connection
      ✓ by returning all the copies of a block for a given connection

  Segment
    has default attributes
      ✓ has a default length of zero
      ✓ has a default head position of 0,0
      ✓ has a default orientation of null
    can create a new horizontal segment
      ✓ with one block
      ✓ with 2 blocks
    can create a new vertical segment
      ✓ with one block
      ✓ with two blocks
    can give all blocks in segment
      ✓ returns an array of blocks

  Pattern
    with default attributes
      ✓ has no segment data
      ✓ has no segments
    takes in information to build segments
      ✓ and builds the segments
      randomly places computer colors on the pattern
        ✓ changes the color of the selected computer blocks


  32 passing (28ms)

```

### Test Breakdown
- How Many Unit Tests? 24
- Integration Tests: 8

### Provide a link to an example, if you have one, of a unit test that covers an 'edge case' or 'unhappy path'
[Unit Test - Sad Path](https://github.com/lucyfox4131/color-wars/blob/995130e2b36965c2db7330fa937f241c11c11d64/test/block_test.js#L98-L103)

### Provide a link to an example, if you have one, of a feature test that covers an 'edge case' or 'unhappy path'
None :(
-----

### Please feel free to ask any other questions or make any other statements below!

-----

# Instructor Feedback

- Points: (base 150)

### Playability Features

We want your game to be full-featured and playable -- not just a proof of concept of the gameplay and rendering features.

To this end, make sure to include sufficient UX to allow the user to fully interact with the game. This would include:

- Indicate when the game is over and won or lost
- Allow the user to start a new game
- Include a clean UI surrounding the actual game interface itself
- Score Tracking: How this works will vary by game, but at the end of the game, generate a score for the winning player
- Scoreboard -- track scores across multiple game sessions. Since we aren't incorporating a server for our games, client-side storage like a cookie or LocalStorage will suffice.
- Create multiple rounds of difficulty. (consider increasing factors such as game speed, randomness of starting setup, etc)

### Features

* 35 points - Application is fully playable and exceeds the expectations set by instructors
* 25 points - Application is fully playable without crashes or bugs
* 10 points - Application has some missing functionality but no crashes
* 0 points - Application crashes during normal usage

### User Interface

* 15 points - The application is pleasant, logical, and easy to use. There are no holes in functionality and the application stands on its own to be used by the instructor without guidance from the developer.
* 10 points - The application has many strong pages/interactions, but a few holes in lesser-used functionality.
* 5 points - The application shows effort in the interface, but the result is not effective. The evaluator has some difficulty using the application when reviewing the features in the user stories.
* 0 points - The application is confusing or difficult to use.

### Testing

* 30 points - Project has a running test suite that exercises the application at multiple levels. The test suite covers almost all aspects of the application and uses mocks and stubs when appropriate.
* 25 points - Project has a running test suite that tests multiple levels but fails to cover some features. All functionality is covered by tests. The application makes some use of integration testing.
* 10 points - Project has sporadic use of tests and multiple levels. The application contains numerous holes in testing and/or many features are untested.
* 0 points - There is little or no evidence of testing in this application.

### JavaScript Style

* 30 points - Application has exceptionally well-factored code with little or no duplication and all components are separated out into logical components. There zero instances where an instructor would recommend taking a different approach.
* 20 points - Application is thoughtfully put together with some duplication and no major bugs. Developer can speak to choices made in the code and knows what every line of code is doing.
* 15 points - Your application has a significant amount of duplication and one or major bugs.
* 5 points - Your client-side application does not function. Developer writes code with unnecessary variables, operations, or steps which do not increase clarity.
* 0 points - There is little or no client-side code. Developer writes code that is difficult to understand. Application logic shows poor decomposition with too much logic mashed together.

### Workflow

* 25 points - The developer effectively uses Git branches and many small, atomic commits that document the evolution of their application.
* 15 points - The developer makes a series of small, atomic commits that document the evolution of their application. There are no formatting issues in the code base.
* 10 points - The developer makes large commits covering multiple features that make it difficult for the evaluator to determine the evolution of the application.
* 5 points - The developer commited the code to version control in only a few commits. The evaluator cannot determine the evolution of the application.
* 0 points - The application was not checked into version control.

### Code Sanitation

The output from JSHint shows…

* 15 points - Zero complaints
* 10 points - Five or fewer complaints
* 5 points - Six to ten complaints
* 0 points - More than ten complaints
