# GameTime Submission Form

## Basics

### Link to the Github Repository for the Project
[battlezone (Pirate Racer : Destroyer)](https://github.com/afg419/battlezone)

### Link to the Deployed Application
[Pirate Racer Destroyer](http://afg419.github.io/battlezone/)

### Link to Your Commits in the Github Repository for the Project
[Aaron Greenspan](https://github.com/afg419/battlezone/commits?author=afg419)  
[Brant Wellman](https://github.com/afg419/battlezone/commits?author=brantwellman)

### Provide a Screenshot of your Game
![Pirate Racer Destroyer](http://i.imgur.com/QnNDhPW.png)

---

## Completion

### Do You Consider the Application to be Fully Playable?
 - Yes, the game is fully playable (tutorial, Level 1, Level 2, and Level 3). User can start game and the game will end when they collect all of the wealth boxes on the board or are killed by a mine or turret. Game results are tracked.

### What Extensions, as Requested By an Instructor, Did You Complete?
- Tess requested a tutorial level to the game due to complexity of the controls. A player is guided through on screen instructions from purple "message" box to purple "message" box to learn the basic controls of the game.
![Tutorial](http://g.recordit.co/Q2pS8XsrfF.gif)
- Provide a .gif of the extension or a link to the relevant code

### What Features, if Any, Do You Feel Exceed Instructor Expectations?
Per Feature:
 - 3D rendering!
 - (see above gif and screenshot)

----

## Risk Taking
- 3D rendering was the biggest risk that we took during this project. There were MANY hurdles to overcome to make it actually work...starting with rendering single points, then lines, then faces.

- How do you feel about those risks?  
  We feel great having actually accomplished what we had set out to do (and far more). We started with the goal of building Battlezone (3D first person shooter from a tank's perspective) and we ended with a 3D first person shooter in space with mines, fighters, and multiple levels.

----

## Code Quality

### Link to a specific block of your code on Github that you are proud of  
- [Game Loop](https://github.com/afg419/battlezone/blob/master/lib/index.js)

- Why were you proud of this piece of code?
- We had a difficult time trying to figure out how to render each of the needed game screens. This file started with a HUGE amount of code. We ended up breaking each of the screens into their own class and then passing the GameLoop back into them along with the level and inGame state to determine what should be rendering.

### Link to a specific block of your code on Github that you feel not great about
- [Level Library](https://github.com/afg419/battlezone/blob/master/lib/level_library.js)  
- Why do you feel not awesome about the code? What challenges did you face trying to write/refactor it?
- We aren't thrilled with having huge collections of objects in a single file, but we couldn't really figure out how to do it differently.

### Attach a screenshot or paste the output from your terminal of the result of your test-suite running.
![Screenshot 1](http://i.imgur.com/B9KNMw5.png)
![Screenshot 2](http://i.imgur.com/kSdf2Tk.png)
![Screenshot 3](http://i.imgur.com/OXfD5sF.png)
![screenshot 4](http://i.imgur.com/WeKHrbX.png)

### Test Breakdown
  Total Tests - 69
- How Many Unit Tests?
- How Many Feature/Integration Tests?

### Provide a link to an example, if you have one, of a unit test that covers an 'edge case' or 'unhappy path'
 - [Turret Testing - edge case](https://github.com/afg419/battlezone/blob/master/test/turret-test.js#L10-L18)

### Provide a link to an example, if you have one, of a feature test that covers an 'edge case' or 'unhappy path'  

- [edge_testing](https://github.com/afg419/battlezone/blob/master/test/edge-test.js#L37-46)
-----

### Please feel free to ask any other questions or make any other statements below!

-----

## Instructor Feedback

- Points: (base 150)

175

## Playability Features

All present

## Extensions

- 3D Playability - 20
- Tutorial Mode - 20

# Functional Expectations

35 points - Application is fully playable and exceeds the expecations set by instructors

# User Interface

15 points - The application is pleasant, logical, and easy to use. There no holes in functionality and the application stands on it own to be used by the instructor without guidance from the developer.

# Testing

30 points - Project has a running test suite that exercises the application at multiple levels. The test suite covers almost all aspects of the application and uses mocks and stubs when appropriate.

# JavaScript Style

20 points - Application is thoughtfully put together with some duplication and no major bugs. Developer can speak to choices made in the code and knows what every line of code is doing.

# Workflow

25 points - The developer effectively uses Git branches and many small, atomic commits that document the evolution of their application.

# The output from JSHint shows…

10 points - Five or fewer complaints
