# Game Time Check In # 2

## Instructor Goal Completion

### GOAL 1: Fill space unit by unit with color

- [See code snippet](https://github.com/lucyfox4131/color-wars/blob/39f357c0630affbf34690bf5ddb53daa039f69ae/lib/index.js#L65-L79)
- Rendering an image and getting image data was too difficult because the color variations in the pixels were too great to narrow down. We couldn't differentiate between the shape of the image and the background so we couldn't determine which pixels to change color. We decided instead to render segments of blocks on the canvas, treating them as a doubly linked list. That way, we could start off on a block, change its color, and then recursively change the color of the blocks connected to it.

### GOAL 2: Know How Score the Board

- [See code snippet](https://github.com/lucyfox4131/color-wars/blob/39f357c0630affbf34690bf5ddb53daa039f69ae/lib/index.js#L87-L92)
- We have the logic for determining how many blocks of a given segment are a certain color. We still need to determine how we are going to display the score information. Right now only a final score is logged, since there is no gradual filling of color yet.

### GOAL 3: Demo a Board Filling

- See gif below
- We followed the instructions such that the board can be completely filled with user and computer color. Right now they fill in whole-block chunks and it looks like the whole segment fills at once. We need to smooth out the filling so it appears more gradually.
- Question: We are having trouble getting the computer color and the user color to start filling at the exact same time. Right now the computer color starts filling slightly before the user color because that function is called first. Can we make these two functions happen at the exact same time?

### Stretch Goal: User Places a Color
- We created a click event so that the user can place a color on the board by clicking. This is the event that triggers both colors to start filling.

### Stretch Goal: Log out Percentages of Board filled by Color
- Console logs the percent of board filled by each color after the colors begin filling.  

### Gif of Board Filling, Including Stretch Goals
- ![board fills with color](http://g.recordit.co/maNEmKhfuG.gif)

## Next Steps?

- Smooth out the color filling animation
- Handle logic for boards that involve multiple segments
- Create a basic gameflow, including level design

### General Questions, Comments, Concerns?
- None at the moment

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
