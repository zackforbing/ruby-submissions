# Game Time Check In # 1

## Basics

### Team
- [Matt Packer](https://github.com/matthewrpacker)
- [Kris Sparks](https://github.com/kbs5280)

### Game Name

UFO

### Give a Basic Description of the Game

Single-player, 2D, flying obstacle-course game. Player can control the flying object using the keyboard. On keydown object ascends and on keyup object descends along the y-axis. Player must avoid danger obstacles in order progress in the game.

### Include a Link to or Screen Shot of the Game

![UFO](check-in-1.png)

### Link to the Github repository for the project
[Game Time Repo](https://github.com/kbs5280/game-time)

## The Plan

### Describe Your goals for the finished product

- UFO ascends and descends along y-axis
- Obstacles move across the x-axis, from the right to the left, toward the UFO.
- UFO must avoid obstacles to progress in the game.
- Score is displayed during play and is adjusted based on performance.
- User can see past top scores.
- User can proceed to next level with increased difficulty.
- Welcome display to start a new game.
- Game over display.
- Games UI is consistent with game's description.

### What is your MVP, or 'this was harder than I thought' plan?

- Player must "start game" from welcome display.
- Welcome display includes instructions.
- Score is based on distance survived (e.g. player survived without colliding with an obstacle for 10 parsecs - earned 100 points).
- If player collides with an obstacle, game is over.
- Game will have two levels, with level 2 being more challenging than level 1.
- Game provides an indication that player has progressed from level 1 to level 2.
- Player can view past scores on the game over screen.
- Game provides basic UI that is consistent with game description.

### What have you accomplished so far?

- Create a world, a flying object and obstacles.
- UFO responds to 'u-key'.
- On keydown UFO ascends.
- On keyup UFO descends.
- Obstacles move at different rates.
- Game registers UFO collisions.

### Questions, Comments, Concerns?

- What is the expectation for UI?
- Project should be hosted on Heroku?
- Are we on the right track?
- Are we missing any required functionality in our plan?
- Do you see any potential pitfalls?
- How do you refactor JS?

-----

# Instructor Feedback Section

### Points for first check in (base 50)

* 50: First check in form and README was completed and pull requested in. Team has a well documented plan for moving forward with their game. Team has completed some wireframing and/or written code.
* 40: First check in form and README was completed and pull requested in. Team has a well documented plan for moving forward with their game. Team has not written any code or created any wireframe documents.
* 25: First check in form completed but shows little effort at documenting/planning and team has not written any code.
* 0: First check in form was not completed.

### Instructor's Goals for Next Check In


* restart game after game-over page
* space bar for ufo flight

stretch: scoring

* Goal 1: game-over page after collision

* Goal 2: restart game after game-over page

* Goal 3: space bar for ufo

_Note: Instructor/Groups can add additional goals beyond 3. Grading for the next check in will be based on completion of goals_

### Stretch Goals

* scoring

### Feedback?
