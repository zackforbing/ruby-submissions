# Game Time Check In # 2

## Instructor Goal Completion

### GOAL 1

- Goal: A ball can move around - collisions with the wall are recognized - a standard velocity. 
![Gif of ball moving and colliding with the wall](http://g.recordit.co/RHqY2zCqUF.gif)
- Did you deviate from the instructions?
   - We implemented a system for offsetting movement when wall collisions are detected (exceeds instructions' expectations) 
   - Equal and opposite movement
   - Planning on setting up support for changes in velocities/acceleration

- Questions, Comments, Concerns? 
  - Comments:
    - All tiles are represented by an array in the code
    - Walls/barriers are represented in this array as specific values
    - We added started with 4 points around the ball for checking collisions
    - Robbie added 'resolution' of points around the ball by doing some trig
    - Every 5 degrees, it's some pretty slick math. This might be expensive computationally?
  - Questions:
    - How would sockets affect these collision calculations? Would they be done client side, or server side?
    - How might we handle angled walls (where 1/2 tile is is barrier, the other is a 'movable' area)?

### GOAL 2

- Goal: Two balls are in the game. Eventlistener shows and moves them both.
![Gif of two balls moving](http://g.recordit.co/T7VA3KrA1E.gif)
- Did you deviate from the instructions? 
  - Not really. Instructions didn't indicate _how_ we would move the ball or collisions
  - We implemented WASD as the controls for one ball, and arrow keys for the other ball
- Questions, Comments, Concerns?
  - Questions: 
   - How might we handle the ball-ball collision physics? Should we strive for more force/acceration/realism?
   

### GOAL 3

- Goal: Some amount of testing was completed for ball.
- [Link to testing code on Github](https://github.com/saylerb/game-time/tree/dev/test)
- Did you deviate from the instructions?
  - We implemented tests for the Map, Player and Keyboard classes
- Questions, Comments, Concerns?
 - Should we start using more DOM tests?
 - Will our testing change if we implement websockets?

### GOAL 4

- Stretch Goal (Not Complete): The flag exists and is randomly placed on the map. Ball and a flag collision is recognized
- Did you deviate from the instructions? Tell us about it. -> we didnt' complete it
- Questions, Comments, Concerns?

## Next Steps?

- What do you feel the next steps should be?
  - One of two main paths:
    1. start on sockets with current game
       - get the current features (4 balls move on screen with wall collision detection)
       - basically make a bad game with sockets, then implement the rest of game features later
    2. Finish an MVP 2-4 player game without sockets first
       - implement flag and ability for player to capture flag
       - implement ball-ball collisions and acceleration
       - implement 'scoreboard' 

### General Questions, Comments, Concerns?
 - How to implement OOP for flag ( should map know about location of flag, or should flag be independent)
   - maybe flag should be own class since flag collision logic will significantly different
   - Flag logic will differ a lot from the logic for map barrier collisions
 - Should we implement a scrolling screen (aka to emulate Fog of War)
   - Concerned gameplay will be affected if player can see everyone all-the-time
 - Worried about starting to implement sockets too late vs. having an MVP game without sockets first...
   - Brian reached out to JP and they said they started with sockets relatively early
   - If we don't start soon, there may be too many things to change logically in order to complete it on time
-----

# Instructor Section

### Points for Second Check In (base 50)

* 60 points: Students documented their work well and completed all base goals or have documented where/why they deviated from the goal in a reasonable way. Students completed additional stretch goals.
* 50 points: Students documented their work well and completed all base goals or have documented where/why they deviated from the goal in a reasonable way.
* 35 points: Students completed all base goals but did not document the work appropriately in their form || did not complete 1 goal and failed to document why in a reasonable way.
* 25 points: Students did not complete more than 1 goal.
* 0 points: Students did not complete check in form prior to eval.

### Instructor's Goals for Next Check In

* Goal 1:

* Goal 2:

* Goal 3:

_Note: Instructor/Groups can add additional goals beyond 3. Grading for the next check in will be based on completion of goals_

### Stretch Goals

* _ie. Goals that are not required to meet the checkin, but would be good to have. Completion may result in extra credit points_

### Feedback?
