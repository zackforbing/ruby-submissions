
# Game Time Check In # 2

## Instructor Goal Completion

### GOAL 1 - Asteroids drift randomly around screen and warp off/on screen

  - Provide a screenshot or gif or link to code for this goal
   * [Link](https://github.com/seeker105/asteroids/blob/81b664cdcc5e4a2bd9227a8e0ef35a6bdadc553a/lib/asteroid.js#L13-L37)
  - Did you deviate from the instructions? Tell us about it.
   * No 
  - Questions, Comments, Concerns?
   * None at this time

### GOAL 2 - Player/ship moves in direction of rotation & ship warps off/on screen 

- Provide a screenshot or gif or link to code for this goal
  * [Link](https://github.com/seeker105/asteroids/blob/81b664cdcc5e4a2bd9227a8e0ef35a6bdadc553a/lib/ship.js#L30-L51)
- Did you deviate from the instructions? Tell us about it.
  * No 
- Questions, Comments, Concerns? 
  * None at this time

### GOAL 3 - Collision detection - ship disappears when it 'dies'

- Provide a screenshot or gif or link to code for this goal
- <img width="300" alt="game over" src="https://cloud.githubusercontent.com/assets/17806544/17954226/ae47a112-6a36-11e6-83ef-9fb073c62515.png">
- Did you deviate from the instructions? Tell us about it.
  * No 
- Questions, Comments, Concerns?
  * None at this time

### GOAL 4 - Add an image to canvas

- Provide a screenshot or gif or link to code for this goal
- <img width="300" alt="images" src="https://cloud.githubusercontent.com/assets/17806544/17954211/91fbaba2-6a36-11e6-9b97-95493b453b52.png">
- Did you deviate from the instructions? Tell us about it.
  * No 
- Questions, Comments, Concerns?
  * None at this time

### GOAL 5 - Add some unit tests

- Provide a screenshot or gif or link to code for this goal
  * [Link](https://github.com/seeker105/asteroids/blob/81b664cdcc5e4a2bd9227a8e0ef35a6bdadc553a/test/ship-test.js#L47-L71)
- Did you deviate from the instructions? Tell us about it.
  * No 
- Questions, Comments, Concerns?
 * Problem with test suite finding canvas variable null, but only in some places; works fine in others. 

## Next Steps?

- What do you feel the next steps should be?

  * Add functionality so that ship can shoot
  * Handle asteroid/bullet collisions
  * Add tests for asteroid functions
  * Make game consist of more than 1 ship
  * Add scoring

### General Questions, Comments, Concerns?
  * Discussion of refactoring strategies would be helpful, especially re: asteroid functions/setup as we will need to identify/change specific asteroids

-----

# Instructor Section

### Points for Second Check In (base 50)

* 50 points: Students documented their work well and completed all base goals or have documented where/why they deviated from the goal in a reasonable way.

### Instructor's Goals for Next Check In

* Goal 1: Refactor and test some uncovered things - like asteroids - doesn't have to look nice

* Goal 2: Add shooting functionality, register the collision in some way

* Goal 3: Have more than one ship life per game or a next level/round - whatever you decide on that causes a new ship to show up. 

_Note: Instructor/Groups can add additional goals beyond 3. Grading for the next check in will be based on completion of goals_

### Stretch Goals

  * Make ship movement smoother - similar to how asteroids move - doesn't have to be perfect
    or
  * Add scoring - and score that calculates score board that shows up at the end
    or 
  * Begin increasing difficulty with advanced things - like power ups or whatever you have in mind

### Feedback?
