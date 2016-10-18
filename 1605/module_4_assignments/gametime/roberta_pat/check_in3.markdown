Complete this Form before the third check in. Delete this line from your version.

# Game Time Check In # 3

## Instructor Goal Completion

### Finish Collision detection between blocks & players
- added additional collisions for player and fire, player and bombs, and fire and blocks.

Players cannot go through immovable blocks:
![Screenshot](./check-in-3/player-block-collision.png)

Players cannot go through bombs:
![Screenshot](./check-in-3/player-bomb-collision.png)

Players cannot go through breakable blocks:
![Screenshot](./check-in-3/player-breakable-block-collision.png)

Explosions cannot expand past immovable blocks:
![Screenshot](./check-in-3/explosion-horizontal.png)
![Screenshot](./check-in-3/explosion-vertical.png)
![Screenshot](./check-in-3/explosion-all.png)

Explosions can go through breakable blocks:
![Screenshot](./check-in-3/explosion-breakable-block-collision-before.png)
![Screenshot](./check-in-3/explosion-breakable-block-collision-during.png)
![Screenshot](./check-in-3/explosion-breakable-block-collision-after.png)


### Players can place bombs
- implement logic to place bombs,
- added fix so bombs cannot be placed inside of blocks,

### Bombs Explode
- implement bombs exploding,
- added logic for bombs creating explosions and explosions creating fire blocks.
- bombs explode in game-like manner

### If a player hits an explosion, the game ends
- implemented game ending after fire block collides with player.

### Stretch: Score based on timer
- implemented score based on time remaining
- not yet persistent in between refreshes.

### Additional Implementations:
- added sprites for all aspects of game except background.
- implemented breakable boxes and all logic behind them.

## Next Steps?

- Add different levels ( canvas gets smaller, or explosions get larger, or both )
- High scores/scores persist past refresh
- ability to start a new game after previous one ends.
- AI!!
- movement animations w/ sprites

### General Questions, Comments, Concerns?

-----

# Instructor Section

### Points for Second Check In (base 50)

* 60 points: Students documented their work well and completed all base goals or have documented where/why they deviated from the goal in a reasonable way. Students completed additional stretch goals.
* 50 points: Students documented their work well and completed all base goals or have documented where/why they deviated from the goal in a reasonable way.
* 35 points: Students completed all base goals but did not document the work appropriately in their form || did not complete 1 goal and failed to document why in a reasonable way.
* 25 points: Students did not complete more than 1 goal.
* 0 points: Students did not complete check in form prior to eval.

### Instructor's Goals for Next Check In

These goals should center around wrapping up the game:

- Matching the [rubric](https://github.com/turingschool/lesson_plans/blob/master/ruby_04-apis_and_scalability/gametime_project.markdown) requirements
- Refactoring/Cleaning up test coverage
- Making the game compelling for players
- Making sure the README and other documentation is up to snuff
- Making sure the game is deployed

_Note: Instructor/Groups can add additional goals beyond 3. Grading for the next check in will be based on completion of goals_

### Feedback?
