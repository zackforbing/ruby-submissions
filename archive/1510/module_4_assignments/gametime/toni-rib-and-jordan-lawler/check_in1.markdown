# Game Time Check In # 1

## Basics

### Team
- [Toni Rib](https://github.com/ToniRib)
- [Jordan Lawler](https://github.com/jlawlzz)

### Game Name

Tower Defense (but we need a better name)

### Give a Basic Description of the Game

Place towers to destroy the enemies before they make it to the end of the path.

### Include a Link to or Screen Shot of the Game

We don't have anything rendered for our game yet, but here's a few other TD games.

[Tower Raiders](https://i.ytimg.com/vi/m9w3XmcUUrQ/maxresdefault.jpg)

[Alien Creeps](http://resource.appgamer.com/library/2015/142854074319_pharaoh2b.jpg)

[Retro Tower Defense](http://pygame.org/shots/1688.png)

### Link to the Github repository for the project

[Repo](https://github.com/ToniRib/game_time)

## The Plan

### Describe Your goals for the finished product

- Level based game with at least one level (path and build sites change per level)
- Multiple waves of enemies, different enemies or number of enemies per wave
- Different kinds of enemies have different speeds and health (5 total)
- Different kinds of towers have different ranges, fire rates, and damage (4 total)
- User places towers on specific building squares based on their paper monies (purchase towers)
- Towers fire at a specific rate at enemies within their range (100% hit rate)
- Accrue more paper monies as enemies are destroyed
- For each level, specific number of 'lives' which is how many enemies can reach the end of the path before you lose
- Different difficulty levels will allow different number of 'lives'

### What is your MVP, or 'this was harder than I thought' plan?

- One level, all enemies in one wave (but spread out so they come through at different times)
- Straight horizontal path
- One type of enemy
- One type of tower
- Very few build paths
- No paper monies :(

### What have you accomplished so far?

- Built out a class for SimpleTower and SimpleEnemy to start testing logic. Started on class for a Tile which will eventually become part of a Board which will be part of a Level.

### Questions, Comments, Concerns?

- Not at this point, though we haven't started working on the game engine yet that will actually run/render the game.

-----

## Instructor Section

### Points for first check in (base 50)

50

### Instructor's goals for next check in

Build a board that has tiles and render that on the canvas

### Feedback?

Looks good so far. Make sure you're rendering onto the canvas along the way. Don't wait to render the board until the end.
