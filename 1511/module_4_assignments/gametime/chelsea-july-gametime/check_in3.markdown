# Game Time Check In # 3

## Instructor Goal Completion

### Increase Difficulty

  - We added increased difficulty. The sprites' spawn rates and speed progressively increase as the game continues.

  ![game](http://g.recordit.co/Rod7xrRv7S.gif)

### Add Moving Background and Music

- See above gif
- We added a moving background.
- Background music was added, as well as sounds when you hit sprites ("ding" for sushi, "meow" for trash)

### Add High Scores

- We keep track of high scores by using Firebase
- Only top five are added
- User can add their name if they wish. Not entirely clear when they need to do that.

![image-of-scoreboard](images/Scoreboard.png)

### Start Screen and Replay Button
- We have a start screen and a game over screen. Start screen has a "play game" button, game over screen has a "play again" button.

![image-of-start-screen](images/start-screen.png)
![image-of-start-screen](images/game-over.png)

## Next Steps?

- Improve performance
- Refactor
- Prompt user when they need to add name (ex: if they have a winning score)
- Possible extension- laser shooting from eyes.

### General Questions, Comments, Concerns?

-----

## Instructor Section

### Points for Second Check In (base 50)
  50/50

### Instructor's Goals for Next Check In
  - Preload images
  - Add instruction for adding name
  
### EXTENTSION/NOTES
  - How to hide API key?  -- DID IT! Using external file exporting api keys and moving into .gitignore
  - Lasers? 

### Feedback?
  - Got moving background/sprites going!
  - Speed increases, music, etc. Accomplished all goals
  - Refactored multiple draw things into a draw object
