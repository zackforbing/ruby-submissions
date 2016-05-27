# Game Time Check In # 2

## Instructor Goal Completion

### Clean up collision detection

  - https://github.com/adamhundley/block_party/blob/master/src/PartySquare.js#L55
  - Did you deviate from the instructions? Tell us about it.
  - Questions, Comments, Concerns?

### Game stops when you hit a non-safe area

- https://github.com/adamhundley/block_party/blob/master/src/PartySquare.js#L69
- Did you deviate from the instructions? Tell us about it.
- Questions, Comments, Concerns?

### Game visually responds correctly to passing through a safe area

- https://github.com/adamhundley/block_party/blob/master/src/PartySquare.js#L66
- When passing through the pipe entry, your score increases based on state.

### Game in some way begins to keep score

- No concerns here. Score is kept based on width of pipe entry as well as points given for changing colors and hitting upper and lower bounds.  High scores are stored locally.

### Have a plan for deploying the application - take a first pass - look at using node/express if continuing to use React

- We fixed an issue with rescuing errors codes which now allows react to load immediately. Our game will work as planned when deployed statically to github pages.
- We are running express in development with the intention of moving to a full node app next week.

## Next Steps?

- Create levels(increase speed, pipe entry width, gravity on pipe entires, color scheme changes, etc.)
- Implement -> and <- functionality and see if how it affects the enjoyment of the game
- Continue improving motion module(physics of PartySquare gravity)
- Look into preprocessing canvas draws to improve performance
- Continue to up testing coverage

### General Questions, Comments, Concerns?

- we completed full color based gameplay as a check in extension

-----

## Instructor Section

### Points for Second Check In (base 50)
 +  50/50
  
### Instructor's Goals for Next Check In
 +  Increase speed and distance between pipes
 +  Implement some type of level change
 +  For example, 5 then sample
 +  Add additional colors
 +  Pause Game/Start Game
 +  Talk about gravity and movement along x axis

 EXTENSION
 +  Web sockets and figure out how you want to start the game
  
### Feedback?
 +  Figured out the issue with npm run build and pushing to production. All is well in production world. 
