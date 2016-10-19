Complete this Form before the third check in. Delete this line from your version.

# Game Time Check In # 3

## Instructor Goal Completion

### GOAL 1 - Board scroll not crashing and functional

  - Provide a screenshot or gif or link to code for this goal
  - Did you deviate from the instructions? Tell us about it.
      board scrolling is working in a sense - the board scrolls, but the player and the enemy spawn points do not translate with it. so currently you can scroll wherever you want, but the player stays at it's starting position, and enemies don't spawn in the right places.
  - Questions, Comments, Concerns?
      we use the canvas.translate function to scroll the board, and it is working, but we can't figure out how to negate the translation for the player, and for the enemy and bullet spawn points.

### GOAL 2 - Bullets and collision detection

- Provide a screenshot or gif or link to code for this goal
- Did you deviate from the instructions? Tell us about it.
    bullets are implemented, but a bit buggy still, and need some tweaking. basic collision detection has been implemented, but the enemies collide with each other, so there is more to do with that as well. right now I think the collision detection is cancelling out the bullets before they fire, I assume because of collisions with other bullets, maybe.
- Questions, Comments, Concerns?
    with all the enemies, I'm not sure if it would be good or necessary to break the gameboard into zones for collision detection purposes.

### GOAL 3 - Enemies moving and pausing?

- Provide a screenshot or gif or link to code for this goal
- Did you deviate from the instructions? Tell us about it.
    I did not remember talking about pausing, and I was not sure of the context of it, either - did we mean enemies stopping and starting? pausing the game in general? we have enemies generating just off the starting screen and heading in all directions.
- Questions, Comments, Concerns?
    the enemy generation points do not translate with the gameboard for some reason - same with the player. both of these need to be dynamic to the translation of the canvas.

### GOAL 4 - Time mechanism

- Provide a screenshot or gif or link to code for this goal
- Did you deviate from the instructions? Tell us about it.
    this goal was not achieved. with all that we still have to accomplish, I think this goal is out of reach for us before thursday.
- Questions, Comments, Concerns?


## Next Steps?

- What do you feel the next steps should be?
    we have quite a few things to do before turn in on thursday.

    clear enemies that are far offscreen
    keep player stationary along with bullet and enemy spawn points
    add hurdles to increase the difficulty at certain y values
    collision (player-enemy, enemy-bullet)
    scoring and displaying scores
    game start and game over (with reset) - cross first hurdle to begin
    splash screen as starting background
    local high scores
    run code through jshint
    space bullets out using date.now
    deploy, if necessary?

### General Questions, Comments, Concerns?

-----

# Instructor Section

### Points for Second Check In (base 50)

* 60 points: Students documented their work well and completed all base goals or have documented where/why they deviated from the goal in a reasonable way. Students completed additional stretch goals.
* **50 points: Students documented their work well and completed all base goals or have documented where/why they deviated from the goal in a reasonable way.**
* 35 points: Students completed all base goals but did not document the work appropriately in their form || did not complete 1 goal and failed to document why in a reasonable way.
* 25 points: Students did not complete more than 1 goal.
* 0 points: Students did not complete check in form prior to eval.

### Instructor's Goals for Next Check In

These goals should center around wrapping up the game:

- Team has a plan 
- Making the game compelling for players
- Making sure the README and other documentation is up to snuff
- Making sure the game is deployed

### Feedback?
