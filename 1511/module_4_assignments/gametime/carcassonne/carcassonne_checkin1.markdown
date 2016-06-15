# Game Time Check In # 1

## Basics

### Team
- [Kimiko](https://github.com/ksk5280)
- [Scott](https://github.com/scottfirestone)

### Game Name

Carcassonne

### Give a Basic Description of the Game

Tile laying board game. The players develop the area around Carcassonne and deploy their followers on the roads, in the cities, in the cloisters, and in the fields. The skills of the players to develop the area and use their thieves, knights, farmers, and monks will determine who is victorious.

### Include a Link to or Screen Shot of the Game

[Carcassonne](https://subterraneandeathcult.files.wordpress.com/2012/02/carcretina.jpg)

### Link to the Github repository for the project
[Our Repo](https://github.com/scottfirestone/carcassonne)

## The Plan

### Describe Your goals for the finished product

- 2-4 players local, online or against AI
- Players take turns placing tiles and helpers on the board
- Board shows legal moves and prohibits illegal moves
- Score is updated throughout game and totaled at the end
- Board shows number of followers available for each player and the number of tiles remaining
- Tiles can be rotated for placement
- Followers are returned to pull when road, city or monastery is completed
- Scoring at end shows detailed breakdown
- Clickable pop-up that shows rules of the game
- You can drag and drop pieces
- AI - you can choose the difficulty, easy or hard

### What is your MVP, or 'this was harder than I thought' plan?

- 2 players can play locally
- Players take turns placing tiles and helpers on the board
- PLayers can drag pieces into place
- Tiles can be rotated for placement
- Players keep track of their scores
- Board shows number of followers available for each player and the number of tiles remaining
- Clickable pop-up that shows rules of the game

### What have you accomplished so far?

- We have created a board where we can place and rotate tiles. When the tile placement
  is confirmed it can no longer be rotated or moved and a new random tile is rendered.

### Questions, Comments, Concerns?

How should we create the tile objects and should we create a grid for placement?

Concerns: Writing logic for how to tell if fields are connected, ability to zoom in and out on board, showing legal moves for tile and helper placements

-----

## Instructor Section

### Points for first check in (base 50)

50/50

### Instructor's goals for next check in

- Create your tile class
- Limit number of tiles that can be pulled - which may involve a testable TileStore class or array.
  - Calculate number of tiles remaining
- Not allow user to place a tile on top of another tile

### Extension

- Not allow a user to place a tile where another tile isn't touching it
- 50%ish test coverage of major logic
- A pop up box of rules of the game that player can use, open, close, etc. 

### Feedback?
