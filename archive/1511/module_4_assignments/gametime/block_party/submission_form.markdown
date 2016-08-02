# GameTime Submission Form

## Basics

### Link to the Github Repository for the Project
[Your Repo](https://github.com/adamhundley/block_party)

### Link to the Deployed Application
[Your Application](http://adamhundley.github.io/block_party/)

### Link to Your Commits in the Github Repository for the Project
[Adam](https://github.com/adamhundley/block_party/commits?author=adamhundley) [Nick](https://github.com/adamhundley/block_party/commits?author=weilandia)

### Provide a Screenshot of your Game
![Block Party](http://i.imgur.com/mfoNqhx.png)

## Completion

### Do You Consider the Application to be Fully Playable?

 - Yes. The game is fully functioning with 6 different levels of gameplay.

### What Extensions, as Requested By an Instructor, Did You Complete?

- #### Colorpack Extension
  - We refactored our game to have a ColorManager that now can pull in any color pack we create. The object takes a string for the theme and the rest happens in the background. Currently we have 4 different themes: default, moma, retro and tron. The game is set up for someone to easily open source contribute different color packs for different levels.
  - [ColorManager](https://github.com/adamhundley/block_party/blob/master/src/ColorManager.js)
  - ![GIF](http://g.recordit.co/K3ovgQifhm.gif)

- #### Lateral movement
  - This is a feature where the user can move laterally along the x axis, which is often over looked due to the concentration needed for up and down movement and color changes.
  - [LateralJetPack](https://github.com/adamhundley/block_party/blob/master/src/Motion.js#L51)
  - ![GIF](http://g.recordit.co/iNEwwmjdLE.gif)

### What Features, if Any, Do You Feel Exceed Instructor Expectations?

 - React
 - Fullscreen, responsive to resize mid game
 - mobile adaptation
 - Every file under 100 lines
 - NEW GAME

## Risk Taking

- What risks did you feel you took on this project?

We feel we took quite a few risks on this project. From the beginning we used React without knowing how it worked or having many resources for wiring the game up. We also didn't use the starter kit provided for our game. This caused a slower start to the game as we figured out how to configure everything. We ended up using express for the dev server. One thing we prided ourselves on throughout the whole project was code quality. It was a risk to take time to refactor and still be able to deliver features and extensions on time.

- How do you feel about those risks?

GREAT! We learned a lot about React, ES6 and improved our OOP.

## Code Quality

### Link to a specific block of your code on Github that you are proud of

[Da Best Codes](https://github.com/adamhundley/block_party/blob/master/src/LevelManager.js)
- Why were you proud of this piece of code?

We are proud of the LevelManager because of the use of duck typing and how it serves as the delegator of many different objects. By creating this, we have set ourselves up to easily create new levels or have them submitted by game

### Link to a specific block of your code on Github that you feel not great about

[CurrentLevel](https://github.com/adamhundley/block_party/blob/master/src/LevelManager.js#L47)
- Why do you feel not awesome about the code? What challenges did you face trying to write/refactor it?

We don't love this function. We had it so it changed levels dynamically but then you love flexibility on calibrating level changes. Ideally we can set the current level outside of this function, making the functions only purpose to return a level object. This way we can get more creative on how we assign levels based on state. Basically it's not as dynamic as the rest of our code.


### Attach a screenshot or paste the output from your terminal of the result of your test-suite running.

![Test Suite](http://i.imgur.com/Yh6ezrX.png)

### Test Breakdown
- How Many Unit Tests?

  - 42 tests
-----

### Please feel free to ask any other questions or make any other statements below!

- How would you structure the code differently?
- Would adding a file that's sort of like environment.rb that requires all the files in src be a waste?  Essentially, is it ok to have long lists of imports at the top of js files?
- What are some things we could do to make this as ES6 as possible?
- What should we change before we start creating a course around an introduction to react and es6 through gaming?

-----

## Instructor Feedback

- Points: 160/150
