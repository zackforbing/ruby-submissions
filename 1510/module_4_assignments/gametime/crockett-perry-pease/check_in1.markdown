Complete this Form and the README.md before the first check in. Delete this line from your version.

# Game Time Check In # 1

## Basics

### Team
- [Joe Perry](https://github.com/jwperry)
- [Justin Pease](https://github.com/Jpease1020)
- [James Crockett](https://github.com/jecrockett)

### Game Name

Agar.io

### Give a Basic Description of the Game

 Player moves a round blob across a screen eating small static "food" blobs which make the player's blob bigger and slower. The game is multiplayer, and other players move their blobs around also eating the static blobs. Players can eat each other. If you eat another player, you acquire their mass  If another player eats you, you lose and your game is over.

### Include a Link to or Screen Shot of the Game

[Agar.io](http://i64.tinypic.com/b8wf83.png)
[Actual Game](www.agar.io)

### Link to the Github repository for the project
[Our Repo](https://github.com/jecrockett/gametime)

## The Plan

### Describe Your goals for the finished product

- Player sphere moves around a large canvas
- Player sphere consumes smaller food spheres
- Player sphere gets larger and slower as it consumes the food spheres
- Player's scale zooms out as it gets larger
- Multiplayer, so several players can connect at once
- If two players collide and one is a certain amount larger than the other, the larger player consumes the smaller player
- If two players collide and the difference in their sizes does not surpass the threshold, nothing happens.
- Leaderboard shows top scorers

### What is your MVP, or 'this was harder than I thought' plan?

- Player moves around the screen eating food
- Eating food makes the players get bigger and slower
- If you get eaten, you lose the game.  
- If you eat another player they lose and your blob grows bigger

### What have you accomplished so far?
- Set up Repo
- Set up Waffle
- DTR
- Did research on websockets and feasibility of our idea
-

### Questions, Comments, Concerns?
- Size of the canvas
- Potential issues with using massive canvas and number of players involved
- Where do we start? Getting websockets set up? Or game logic? Is it possible to

-----

## Instructor Section

### Points for first check in (base 50)

50

### Instructor's goals for next check in
- get a player on the screen
- incorporate boundaries on the canvas
- allow the player to consume food dots to get bigger.

### Feedback?

Game is super ambitious - instructor recommends tackling making the game with a few automated 'death' pieces or two players on one computer first.

Then, look at making the canvas of the game larger than the canvas 'window' or implementing websockets for the second player.
