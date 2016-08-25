# Game Time Check In # 2

## Instructor Goal Completion

### GOAL 1 - Unit Tested Procedural Generation of Dungeons

  - Accomplished the first step and attempted the second step of procedural generation algorithm which can be found [here](http://journal.stuffwithstuff.com/2014/12/21/rooms-and-mazes/).
  - Procedural generation gave a lot of headaches involving making sure rooms weren't out of bounds.
  - Very pleased with whats done so far, just would of liked to have finished more, and hit the goal.
  - ![screenshot](http://i.imgur.com/kTLbPN3.png)

### GOAL 2 - Basic rendering of dungeon. Differentiate between walls, cooridors and rooms

- Completed.
- Dungeon renders based on whatever cell values are, with defaults of 0 (empty) and 1 (wall), though support for other types are built in.
- All cells know what room they belong to, which is also checkable when it comes to calling draws for hollowing out rooms later.

### GOAL 3 - Player can move through cooridors and rooms, but not walls.

- Not completed.
- Still feel this will be relatively simple, once generation is done.

### GOAL 4 - Player can spawn and exit. Placements are random.

- Not completed.
- Still will be a definite goal for the next check in.

## Next Steps?

- We would like to continue on to see all of our MVP finished by Monday, along with the stretch goal of distance taken into account for start and ends.
- Monday - Thur of next week should be Enemies, Camera, and Field of View.

### General Questions, Comments, Concerns?

> Ryan: Procedural generation is surprisingly challenging, even at the most basic level. We eventually came away with a well written Grid abstraction layer (built on top of a 2d array) that functions quite well, as well as a fantastic render and very solid room generator. Overall, what was done feels very complete and well tested, with room to expand. That said, it is unfortunate we weren't able to complete as much as we would of liked in the time alotted. I'm not really sure what could of been done differently though. If we chose to cut corners now, we would of had to make up for it later, and a large portion of our time was just wrapping our heads around the challenge I think.

> Parker: I think the foundation of the project was much more daunting than anticipated, there are a lot of small pieces that go into it, which inevitably opens the door for some issues. I think getting randomly generated rooms to appear within bounds on a grid is a good accomplishment. I know that I learned a lot about JS and ES6 through doing so. I have a deeper understanding of functions in JS as well as looping, drawing, and `this`. The small pieces of code led to quite a few hairy bugs, but we were able to effectively dive into the dev tools and solve any issues we ran into. I’m concerned about how difficult the rest of the procedural generation will be, the rooms at face value seemed to be the easiest to me, and it took us a large chunk of time to complete those. The procedural generation is cornerstone to success in the project, but it is not the goal of GameTime. I would love advice on how to set this up quickly but effectively so we can start diving into the game aspects of the project.

-----

# Instructor Section

### Points for Second Check In (base 50)

* 50 points: Students documented their work well and completed all base goals or have documented where/why they deviated from the goal in a reasonable way.

### Instructor's Goals for Next Check In

Show progress on 2 out of the 3 things.

* Goal 1: Continue working to nail down procedural generation
  * Firm up the rest of the maze
  * Build the connections
  * Remove dead ends

* Goal 2: Player Movement first start - ie a block that moves around and has some form of collision

* Goal 3: Documenting your work and the code and talk about, in the README, what you've written so far

### Stretch Goals

* Complete all goals (HERMEGERD)

### Feedback?

Discussion in person regarding the score. 
