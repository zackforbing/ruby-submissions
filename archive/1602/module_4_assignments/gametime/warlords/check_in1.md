# Game Time Check In # 1

## Basics

### Team
- [Jared](https://github.com/JaredRoth)
- [Drew](https://github.com/drew-t)
- [Josh](https://github.com/jwashke)

### Game Name

Warlords

### Give a Basic Description of the Game

4 player pong/breakout game. Each player starts in one corner with walls around him and a paddle in front of his walls.
A single ball bounces around the screen. If it hits a paddle, it bounces off, if it hits a wall it destroys the piece and bounces off.
The objective is to destroy enough of the wall in front of a player to hit the player with the ball, which knocks them out of the game.
The winner is the last player standing.

### Include a Link to or Screen Shot of the Game

![warlord](http://www.hardcoregaming101.net/warlords/2600_06.png)

### Link to the Github repository for the project
[Your Repo](https://github.com/drew-t/gametime)

## The Plan

### Describe Your goals for the finished product

- four users connect to the server
- a ball is dropped in the middle moving in a random direction
- players can move paddles around their walls
- if a ball hits the paddle it bounces off
- if a ball hits a wall it bounces off and destroys the piece
- If a ball hits the player then that player is out of the game
- the winner is the last player standing
- lobbies or rooms for more than 1 game at a time
- multiple balls after certain amount of time passes in game
- power ups embedded in players walls, when a ball hits them, the player who hit them get the power up.


### What is your MVP, or 'this was harder than I thought' plan?

- four users connect to the server
- a ball is dropped in the middle moving in a random direction
- players can move paddles around their walls
- if a ball hits the paddle it bounces off
- if a ball hits a wall it bounces off and destroys the piece
- If a ball hits the player then that player is out of the game
- the winner is the last player standing

### What have you accomplished so far?

- we individually worked through a couple appropriate tutorials (like the mozilla breakout tutorial and another for websocket basics)
- other than that, we only did some additional research and messed around with some concepts. No actual work on the project.

### Questions, Comments, Concerns?
-----

## Instructor Section

### Points for first check in (base 50)

50/50

### Instructor's goals for next check in

#### Drew

- Node server started or (code) spike on websockets being used with webpack
  - If Node:
    - Replicate base functionality of Webpack
      - Mocha testing wired up with dummy code
      - .jshintrc
      - Ability to use babel/es6
      - Match ability to use CSS/Sass (if team is using sass)
      - First pass at deploying to heroku or other deployment
- Initial spike on Websockets

Extra Credit
  - Port over and get working the code of team members in this server

#### Jared

- If implementing Game class, pair on this

- Moving the ball logic into the project
  - Refactoring as a function of adding testing
  - Rendering within the project
  - Ball starts moving when it shows up on screen
  - Ball bounces off wall (maybe infinite loop instead)
  - Ball reacting to a set of bricks

#### Josh

- If implementing Game class, pair on this

- Paddle Object
    - Responds to key events
    - Has an axis/track it can move on
    - Can't move past borders or track
    - Testing for something in here, yo

Extra Credit

Hooking up the collision detection between the paddle and the ball - with a ball reaction

### Feedback?

Entire Damn Thing
 
- Rendering in a purdy way
- Score per player which is rendered on the screen
  - Some way, since websockets/multiple players drive difficulty to make the game compelling - drive competition
- Actual mechanics of deploying and managing multiple players
- Testing! Woo!

- Board Drawn on Canvas
  - Single Player Object
    - has flag
    - has zone of wall pieces
    - has paddle
    - if zone of wall pieces is compromised (ball hits flag zone) then lose condition
  - Paddle Object
    - Can collide with the ball
    - responds to key events
    - Has an axis/track it can move on
    - Can't move past borders or track
    - Four players control paddles
      - Seperate key inputs
      - Next step - feed that data in by websockets
  - Ball Object
    - Ball starts moving when it shows up on screen
    - Ball bounces off wall (maybe infinite loop instead)
    - spawned on screen
    - just one for initial mvp
    - Can be hit by player's paddle
    - Ball changes movement based on paddle location
    - Collides with blocks
    - Speed variation on ball to increase difficulty
