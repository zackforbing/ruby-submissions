# GameTime Submission Form

## Basics

### Link to the Github Repository for the Project
[Bomber Person](https://github.com/julsfelic/bomber_person)
[Bomber Person Server](https://github.com/amaxwellblair/bomber_go)

### Link to the Deployed Application
[Deployed Bomber Person](http://162.243.248.192:2015/)

### Link to Your Commits in the Github Repository for the Project
[Julian](https://github.com/julsfelic/bomber_person/commits?author=julsfelic)

[Allan](https://github.com/julsfelic/bomber_person/commits?author=amaxwellblair)

### Provide a Screenshot of your Game
![Bomber Person](checkin.gif)

## Completion

### Do You Consider the Application to be Fully Playable?

The game itself is not as polished as we would have liked to get it to, but the
mechanics of the game are fully functioning as well as the main goal of implementing
websocket multiplayer.

### What Extensions, as Requested By an Instructor, Did You Complete?

* Websocket online multiplayer for up to 4 bomber people.

### What Features, if Any, Do You Feel Exceed Instructor Expectations?

* Being able to play against 3 other friends online.
* The canvas gif generator.

## Risk Taking

- What risks did you feel you took on this project?

The biggest risk was banking on getting websockets up and running. Instead of
approaching websockets as an extension we looked at it as a key component of the
game that needed to be implemented in order to fully replicate the original game.

- How do you feel about those risks?

Fantasitc! Though there is still some edge cases like a bad internet connection
that can cause some problems the web socket implementation works as expected!

## Code Quality

### Link to a specific block(s) of your code on Github that you are proud of

[Go Websocket](https://github.com/amaxwellblair/bomber_go/blob/5d2c76add43bcdcc1eb2f77a91acc478df738972/main.go#L32-L48)
[Gif Generator]()https://github.com/julsfelic/bomber_person/blob/75a1b8f1261da612bc97751562b632a6f4286a8e/lib/generate_gif.js#L1-L10

- Why were you proud of these pieces of code?

* Able to use GO to implement the server portion of the web socket connection
* Ran into a problem where the canvas does not support gifs, so had to create a
script that refreshes through a list of images to emulate gif like behavior.

### Link to a specific block of your code on Github that you feel not great about

[The for loop of death](https://github.com/julsfelic/bomber_person/blob/75a1b8f1261da612bc97751562b632a6f4286a8e/lib/map.js#L52-L87)

To generate the destoryable blocks, we had to use a hard coded for loop. It
definitely isn't the prettiest thing and we never got around to abstracting it
into smaller classes.

### Attach a screenshot or paste the output from your terminal of the result of your test-suite running.

![Test Suite](final_tests.png)

### Test Breakdown
- How Many Unit Tests?

26

- How Many Feature/Integration Tests?

About that...

### Provide a link to an example, if you have one, of a unit test that covers an 'edge case' or 'unhappy path'

[Edge Case](https://github.com/julsfelic/bomber_person/blob/75a1b8f1261da612bc97751562b632a6f4286a8e/test/map.js#L39-L43)

-----

### Please feel free to ask any other questions or make any other statements below!

We're tired. We need some sleep.

-----

## Instructor Feedback

- Points: (base 300)

### Functional Expectations
  - 35 points - Application is fully playable and exceeds the expecations set by instructors

### User Interface
  - 10 points - The application has many strong pages/interactions, but a few holes in lesser-used functionality.


### Testing
  - 25 points - Project has a running test suite that tests and multiple levels but fails to cover some features. All functionality is covered by tests. The application makes some use of integration testing.

### JavaScript Style
  - 27 points - Some chances to refactor loops of death etc. 

### Workflow
  - 25 points - The developer effectively uses Git branches and many small, atomic commits that document the evolution of their application.

### Code Sanitation
The output from JSHint shows…  
  - 15 points - Zero complaints

### Final Scores
  - Final Assessment: 137
  - Completed Checkins: 150  + 5 Extra
  - SubTotal: 292
  - +5 for Extensions
  - **Total: 297**
