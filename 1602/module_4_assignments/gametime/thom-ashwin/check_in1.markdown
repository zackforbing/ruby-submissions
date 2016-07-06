# Game Time Check In # 1

## Basics

### Team
- [Thom](https://github.com/thompickett)
- [Ashwin](https://github.com/theonlyrao)

### Game Name

1942

### Give a Basic Description of the Game

You fly a plane and try to shoot down enemy planes increasing your score for every enemy plane shot down

### Include a Link to or Screen Shot of the Game

[1942 youtube](https://www.youtube.com/watch?v=WRnn-bhv-AE)

### Link to the Github repository for the project

[Repo](https://github.com/theonlyrao/1942)
[Waffle](https://waffle.io/theonlyrao/1942)

## The Plan

### Describe Your goals for the finished product

- multiplayer being two planes at the bottom of the screen
- two player leaderboard
- 5% of enemy planes can be a large plane
- large plane takes two shots before it dies
- large plane shoots three times as often
- players score increases 500 for large plane
- pick up weapons packages
- small plane can enter anywhere on top half of screen, and changes direction
- planes explode when killed
- add landmasses to background

### What is your MVP, or 'this was harder than I thought' plan?
- one player - controls plane that starts at bottom of screen
- background is blue
- enemy has small planes
  - small plane is shot down with one of your bullets
  - small plane can enter anywhere on top half of screen, and goes in a straight line
  - players score increases 100 for small plane
  - after 20 planes go across the screen the boss plane comes in
- player beats level by beating boss plane
  - boss plane stays at top of screen, and moves side to side
  - boss plane worth 2000 points
  - boss plane has to be shot 8 times and shoots gun at 3 times the rate as a small plane
- different levels
  - all enemies shoot 10% more often, move 10% faster, and there are 10% more planes with each level increase
- players turn ends when they get shot
- leaderboard

### What have you accomplished so far?

  We've built an irregularly shaped object that looks like a red plane that sits on a blue canvas. It is able to move in all directions. The east and west border have the plane continue through to the other side. The north and south border make the plane stop before hitting them. The plane is controlled by the keys [w,d,s,a] => [north,east,south,west]. You can also hold two keys down and move diagonally.

### Questions, Comments, Concerns?

1) do we automatically get credit at checkins for just completing the forms, or do we need to have met the goals?
2) generally are we graded on quality or completion?
3) does this need to get pushed to heroku for checkins/submission?
4) what is the leaderboard supposed to be? do we just need to keep track of all high scores or let users type in name, or remember old scores by current user?
5) what url exactly are we supposed to hit to deliver this project?
6) what is correct directory structure for stylesheets and js files?
-----

## Instructor Section

### Points for first check in (base 50)

50/50

### Instructor's goals for next check in

- Begin refactoring the plane class or function
  - Move it out of the index
  - See if you can get it rendering and moving within a game loop instead of adhoc
  - First pass at testing plane movement

- Figure out jshint story

- First pass at enemy crossing screen
  - Doesn't have to be visually rendered per se, but should be moving x and y coordinates appropriately

Extra Credit

- Refactoring the script.js such that almost all logic is removed - should only be animation loop, finding the canvas, and event listeners (but minimal logic around what event listeners do)

### Feedback?
