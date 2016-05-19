# Game Time Check In # 2

## Instructor Goal Completion

### GOAL 1

![Cannonz](http://g.recordit.co/YzNLjtq9Mc.gif)
  - We got the power bar working. The velocity is based on where the bar is. The top of the power bar has a much higher functionality.
  _ We will be styling it up a little bit and also give an indication as to what your current velocity is.

### GOAL 2
![Cannonz](http://g.recordit.co/YzNLjtq9Mc.gif)

- We were able to figure out the trajectory of the cannon ball. At first we were using moveTo/lineTo and just drawing a quick line between each points. Getting the cannon ball image to render was difficult. We were using the drawImage function inside of setInterval and not seeing it at all. We found out that it was the clearRect function inside the requestAnimationFrame loop that was deleting it as soon as we were rendering it. So we moved the drawImage function into the requestAnimationFrame loop and that solved our problem.

### GOAL 3

- We didn't get collision detection done just yet, but we will have it done by EOD Thursday. We decided to work on refactoring and testing during our work time on Wednesday.

## Next Steps?

- Finishing up collision detection
- adding targets
- adding new levels, with more targets and towers
- possible power-ups

### General Questions, Comments, Concerns?

-----

## Instructor Section

### Points for Second Check In (base 50)

50/50

### Instructor's Goals for Next Check In

- Have one level complete on the backend 
  - One target - that can move back and forth
  - Be able to hit the target - this is logged somehow
  - Have points be allocated
- More than 20 unit tests - spanning different files
- Refactor code into the Game.js

### Extensions

- Have one level done with all visualizations
- Create Additional Levels
- When the bomb hits something, animation that causes a divot in the tower.

### Feedback?
