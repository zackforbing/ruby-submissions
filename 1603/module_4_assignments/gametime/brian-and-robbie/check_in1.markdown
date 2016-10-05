# Game Time Check In # 1

## Basics

### Team
- [Robbie Jaeger](https://github.com/robbiejaeger)
- [Brian Sayler](https://github.com/saylerb)

### Game Name

Capture the Flag (Working Name)

### Give a Basic Description of the Game

Players try to capture a flag and return it to their home base to score points.

### Include a Link to or Screen Shot of the Game

[TagPro](http://i.imgur.com/vh5mjA1.png)

### Link to the Github repository for the project

[game-time repo](https://github.com/saylerb/game-time)

## The Plan

### Describe Your goals for the finished product

- Main Menu
  - create new game (or join existing game if sockets)
  - player can select timed game with rounds, or first to 10 points

- Movement
  - player can move around the screen using arrow keys (or WASD)  
  - player can move diagonally (press multiple keys)
  - player movement has realistic physics, arrrow keys accelerate 
  - ball-to-ball collisions are realistic

- Items and Obstacles
  - items: player can pickup powerups to increase speed and invulnerability
  - obstacles: spikes (instant death), barriers

- Multiplayer
  - node server + socket.io allows people to join an existing game
  - 2-4 players can join a game and play simulaneously

- Scoring
  - player captures flag in enemy base and returns flag to home base to score points
  - scoring a point returns the captured flag to its base
  - rounds are timed to 5 minutes, or first to 10 points
  - a scoreboard at bottom of the screen indicates current score

- Tagging
  - when player has the flag opposing players can tag that player
  - tagging player returns the flag to its base
  - player dies and respawns at home base when they get tagged

- Levels
  - there are a couple maps to choose from (2 or 3)

### What is your MVP, or 'this was harder than I thought' plan?

- Main Menu
  - create new game (or join existing game if sockets)
  - player can select timed game with rounds, or first to 10 points

- Movement
  - player can move around the screen using arrow keys (or WASD)  
  - player can only move one axis at a time (no diagonal, cannot press mulitple directional keys at once) 
  - player moves at constant rate, acceration is instant
  - collisions stop players instantly

- Obstacles
  - obstacles: spikes only (instant death)

- Multiplayer
  - 2 players can play using arrow keys and WASD 

- Scoring
  - player captures flag in enemy base and returns flag to home base to score points
  - scoring a point returns the captured flag to its base
  - game is first to ~10 points
  - a scoreboard at bottom of the screen indicates current score

- Tagging
  - when player has the flag opposing players can tag that player
  - tagging player returns the flag to its base
  - player doesn't die, just loses flag

- Levels
  - there is a single map to choose from


### What have you accomplished so far?

### Questions, Comments, Concerns?

- How do we keeping track of scores across sessions (instances of name)?
  - client side without server
  - server side if using sockets

- How to incorporate 'increase in difficulty'?
  - randomize flag 
  - randomize appearance of spikes/mines

- Creating maps, what can we use for sprites/map graphics?
  - where to find assets
  - animations for death

-----

# Instructor Feedback Section

### Points for first check in (base 50)

* 50: First check in form and README was completed and pull requested in. Team has a well documented plan for moving forward with their game. Team has completed some wireframing and/or written code.

### Instructor's Goals for Next Check In

* Goal 1: A ball can move around - collisions with the wall are recognized - a standard velocity. 

* Goal 2: 

Two balls are in the game. Eventlistener shows and moves them both. (Two players can move the balls).

or 

The flag exists and is randomly placed on the map. Ball and a flag collision is recognized

* Goal 3: Some amount of testing was completed for ball.

### Stretch Goals

* Both options of Goal 2 are complete

### Feedback?
