# Game Time Check In # 2

## Instructor Goal Completion

### GOAL 1 - Second slime on screen moving

  - Provide a screenshot or gif or link to code for this goal
 
 * [Code Link](https://github.com/dtinianow/slime_volleyball/blob/master/lib/scripts/game.js#L42-L44)
 
 * [Code Link](https://github.com/dtinianow/slime_volleyball/blob/master/lib/scripts/slime.js#L18-L35)
 
  - Did you deviate from the instructions? Tell us about it.
  - Questions, Comments, Concerns?
  
      *  The slimes are alive

### GOAL 2 -Get net on canvas

- Provide a screenshot or gif or link to code for this goal

* [Code Link](https://github.com/dtinianow/slime_volleyball/blob/master/lib/scripts/net.js)

* [Code Link](https://github.com/dtinianow/slime_volleyball/blob/master/lib/scripts/game.js#L28)

- Did you deviate from the instructions? Tell us about it.
- Questions, Comments, Concerns?

     *  We were able to render the net, but it has the color of the second slime, while the second slime has the color of the net.  This occurs even though we set default values for both the slime and the net

### GOAL 3 - Colision detection for slimes vs net***

- Provide a screenshot or gif or link to code for this goal

* [Code Link](https://github.com/dtinianow/slime_volleyball/blob/master/lib/scripts/slime.js#L23-L35)

- Did you deviate from the instructions? Tell us about it.
- Questions, Comments, Concerns?

    * We added collision detection for each slime between the net and the walls.  Each slime can only stay on their own respective side of the volleyball court

### STRETCH GOAL - One working (and the understanding why) DOM test

- Provide a screenshot or gif or link to code for this goal

* [Code Link](https://github.com/dtinianow/slime_volleyball/blob/master/test/slime-test.js#L90-118)
* [Code Link](https://github.com/dtinianow/slime_volleyball/blob/master/test/net-test.js#L44-55)

- Did you deviate from the instructions? Tell us about it.
- Questions, Comments, Concerns?

     * We wrote several working tests using the stub technique we learned in class

## Next Steps?

- What do you feel the next steps should be?

    * Our next steps are listed on our waffle [here.](https://waffle.io/dtinianow/slime_volleyball)
    * Top three steps include 1) rendering a ball, 2) making the ball move, and 3) fixing the color rendering bug

### General Questions, Comments, Concerns?

   *  Trying to fix the bug of why color net and slime colors swap 
   *  Understanding why and if we need to use beginPath and closePath in our gameloop
   *  We think these problems are likely related

-----

# Instructor Section

### Points for Second Check In (base 50)

* **60 points: Students documented their work well and completed all base goals or have documented where/why they deviated from the goal in a reasonable way. Students completed additional stretch goals.**
* 50 points: Students documented their work well and completed all base goals or have documented where/why they deviated from the goal in a reasonable way.
* 35 points: Students completed all base goals but did not document the work appropriately in their form || did not complete 1 goal and failed to document why in a reasonable way.
* 25 points: Students did not complete more than 1 goal.
* 0 points: Students did not complete check in form prior to eval.

### Instructor's Goals for Next Check In

* Goal 1: Render and move a ball with no gravity

* Goal 2: Ball collides with walls, ground and net, and reacts accordingly

* Goal 3: Ball collides with player, and reacts accordingly

### Stretch Goals

* Scoreboard (cards 20, 21, and persistence)


### Feedback?
