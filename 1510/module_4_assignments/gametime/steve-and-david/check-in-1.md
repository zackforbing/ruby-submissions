#Fish in a Barrel || Check-in #1

##Basics

###Team
- [Steve Pentler](https://github.com/stevepentler)
- [David Stinnette](https://github.com/dastinnette)

### [GitHub Repository](https://github.com/stevepentler/GameTime)

### Basic Description

Have you ever wanted to shoot fish in a barrel? Of course you have! Test your aim and see if you can land the trophy fish in the murky deep.

### Fish in a Barrel gif
![](http://g.recordit.co/7JFOYuhgPs.gif)

##The Plan

###User Story
- User will press start game
- instructions appear
- user receives 5 "arrows"
- When user presses spacebar, arrows is shot down vertically until it either hits a fish or the bottom of the sea
- Each time a fish is hit, its (y-coordinate) score is added to the overall score
- Once a user has used all 5 "arrows" game is over and total score is put above leaderboard and on leaderboard if appropriate
- User is able to restart the game

### Difficulty settings
  - fish at surface swim relatively faster and act as obstacles for bigger, more valuable, fish at bottom
  - as time increases for single game session fish swim faster making it harder to reach bottom fish

### MVP
1. Create Canvas (blue rectangle 80% of height)
2. Fish hit boundary and reverse direction along same x axis
3. Create boat stationary in center
5. Boat shoots bullets vertically at fixed velocity when spacebar is pressed
6. Bullet collision with fish results in bullet and fish disappearing 
7. fish's y coordinate added to score
8. Shots remaining counter decreases by 1
9. When shots remaining counter == 0, Game Over
10. Leaderboard appears with newest score presented separately and included in leaderboard if applicable
11. Leaderboard has link to restart
12. In every session, fish move faster as time increases


### Extensions
- Fish move up and down along y-axis while also moving along x-axis
- user adds initials to score on leaderboard

### Crazy Extensions
- p5.js amplitude dependent fish speeds, beginner level is slow song with smooth moving fish, expert is fast song with jerky fish

### Current Accomplishments
- fish move across canvas' x-axis and change direction at boundaries
- stationary boat appears at water's surface
- left and right keydown methods firing

### Questions, Comments, Concerns?
- left and right keydown methods return the canvas as this instead of Boat object for this. Accordingly, we can't adjust the this.x position of the boat in the moveBoatLeft/moveBoatRight method. 

## Instructor Section

### Points for first check-in (50 possible)

### Insructor goals for next checkin

### Feedback