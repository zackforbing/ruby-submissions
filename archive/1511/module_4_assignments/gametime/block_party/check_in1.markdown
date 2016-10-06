# Game Time Check In # 1

## Basics

### Team
- [Adam Hundley](https://github.com/adamhundley)
- [Nick Weiland](https://github.com/weilandia)

### Game Name

Block Party

### Give a Basic Description of the Game

Block Party is a similar concept to flappy bird. A user moves an object up and down on the screen to maneuver through 'holes' in oncoming pipes by matching your color to the color on the 'hole'

### Include a Link to or Screen Shot of the Game

![Flappy Bird](https://techlab.education/image/java/flappy-bird/unique-design.gif)

### Link to the Github repository for the project
[Your Repo](https://github.com/adamhundley/block_party)

## The Plan

### Describe Your goals for the finished product

- Base functionality for flappy-bird
- user must not only line up with opening, but also match its color to the opening
- there are certain openings that require a user to "flatten" themselves
- user can unlock black and white mode
- user can move along the x axis as well and gravity toggles between all 4 directions
- music in the background
- game progressively speeds up according to score
- scored board in top corner

### What is your MVP, or 'this was harder than I thought' plan?

- User block moves through opening in block pipes
- Block goes up and down
- When a pipe is passed, the user gets a point
- When the user block runs into a pipe the game is over

### What have you accomplished so far?

- We have a block that moves up and down on the Y axis. Its gravity changes when it hits the bottom of the screen. Also currently the up and down arrows reverse its gravity.
- We also have pipes that generate every 2 seconds with an "opening" that is a different color than the pipe they are in.
- Once you pass a 'pipe' the pipe disappears

### Questions, Comments, Concerns?
- We can't figure out why our pipe entry is shifting on the page after it goes by

-----

## Instructor Section

### Points for first check in (base 50)

50/50

### Instructor's goals for next check in

- Clean up collision detection 
  - Game stops when you hit a non-safe area
  - Game visually responds correctly to passing through a safe area
  - Game in some way begins to keep score
- Have a plan for deploying the application - take a first pass - look at using node/express if continuing to use React

# Extensions

- Full color based game play
- Game play ~ 50% tested

### Feedback?
