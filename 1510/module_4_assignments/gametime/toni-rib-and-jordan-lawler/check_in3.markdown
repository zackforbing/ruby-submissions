# Game Time Check In # 3

SUPER HAPPY ANIMAL FOOD TIME! (the most amazing tower defense game ever)

## Instructor Goal Completion

### GOAL 1: Some minimal indication of visual instructions to help the user along

![](http://g.recordit.co/SKpykalgxg.gif)

A lot of things were added to meet this goal:

  - Written instructions on the left side
  - Written descriptions of the towers on the right side
  - Build tile highlighting when you click on a tile & change of tower prompt
  - Tower buttons grey out if you can't afford them
  - Animations when a tower is shooting at an enemy
  - Mousedown on a tower to see it's range
  - Sprite animations for the moving enemies

We are still working on additional animations for tower's shooting, especially the whale tower.

### GOAL 2: Set up the menus for game wins/game losses

When you win the game,

  - You can choose to replay this level/difficulty
  - You can choose to play the next difficulty for this level (unless you're on the last difficulty)
  - You can choose to move on to the next level
  - You receive a number of stars (up to 3) depending on how many lives you lost

![You Win](/1510/module_4_assignments/gametime/toni-rib-and-jordan-lawler/images/you_win.png)

When you lose the game,

  - You can choose to replay this level

![You Lose](/1510/module_4_assignments/gametime/toni-rib-and-jordan-lawler/images/you_lose.png)

### GOAL 3: Implement the concept of levels

(Levels folder)[https://github.com/ToniRib/game_time/tree/master/lib/levels]

We implemented the concept of levels by creating a Level class that allows us to fetch all of the correct data for the current level. This allowed us to separate out the board, enemies, money, etc. by level.

### GOAL 4: Refactor

We definitely did some of this, for example by giving the enemies a type attribute we could [refactor this code](https://github.com/ToniRib/game_time/blob/d0a62426a64bf9bb4022dce39caae1de046c7fff/lib/engine.js#L74-L78) to get rid of if statements which became cumbersome when we started adding more enemeis. However, we have a lot of new animation and sprite loading classes that we haven't refactored much. Similarly, I started repeating a lot of tower code that should be refactored to DRY up the code.

## Next Steps?

- Finish animations
- Build more levels

### General Questions, Comments, Concerns?

-----

## Instructor Section

### Points for Second Check In (base 50)

### Instructor's Goals for Next Check In

### Feedback?
