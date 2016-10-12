# Game Time Check In # 1

## Basics

### Team
- [Tommasina](https://github.com/chompasina)
- [Karina](https://github.com/karinamzalez)
- [Deb](https://github.com/deborahleehamel)

### Game Name

Empty Calorie Adventure

### Give a Basic Description of the Game

* Empty calorie overlord drops junkfood while oscillating across top of canvas.
* Healthy food is also randomly falling from the top to the bottom of the canvas.
* Player with "lunch" tray moves left and right along the botton of the canvas to collect food items, try to only collect healthy food items.
* Healthometer displays on left side of canvas increasing or decreasing level based on how many healthy food items are collected on the tray.


### Include a Link to or Screen Shot of the Game

[Snek](http://imgur.com/gallery/owNiA)

### Link to the Github repository for the project
[Your Repo](https://github.com/chompasina/gametime)

## The Plan

### Describe Your goals for the finished product

e.g.

- cheeto overlord oscillates and releases junk food in intervals
- if user accidentally catches a junk food item: 
  * it deletes the healthy item on top of the tray(the one it collided with)
  * it removes health from the health-o-meter 
- Health added/removed to health-o-meter should correspond with actually health point of food item 
- User wins game if he/she stacks enough food to touch the overlord with his healthy food stack
- User loses if he/she catches unhealthy food item with no healthy food items on tray
- User can choose out of three levels of difficulty: 
  * easy - overlord is bigger, oscillates slowly, fewer unhealthy items are dispensed from overlord
  * medium - overlord is medium, oscillates at medium speed, medium amount of items are dispensed 
  * hard - overlord is small, oscillates quickly, more unhealthy items dispensed from overlord
- user ability to move quickly is enhanced when health-o-meter is filled (three speeds)
- High Scores logged and shown on game over (potentially)

### What is your MVP, or 'this was harder than I thought' plan?

e.g.

- tray moves across screen
- overlord drops junkfood
- player collects foods (score reflected on health-o-meter-- i.e. no stack)
- score determines wether they win or lose  (timed) 

### What have you accomplished so far?
- tray move back and forth on keypress(rightArrow & leftArrow)
- tray doesn't move past canvas border
- overlord oscillates 
- canvas 
- 36 unit tests passing
### Questions, Comments, Concerns?
- concern: stacking (how long will it take?) -- i.e. collison detection, how difficult?
- question: good resources for collision detection 
-----

# Instructor Feedback Section

### Points for first check in (base 50)

* 50: First check in form and README was completed and pull requested in. Team has a well documented plan for moving forward with their game. Team has completed some wireframing and/or written code.
* **45: First check in form was completed and pull requested in. Team has a well documented plan for moving forward with their game. Team has completed some wireframing and/or written code.**
* 40: First check in form and README was completed and pull requested in. Team has a well documented plan for moving forward with their game. Team has not written any code or created any wireframe documents.
* 25: First check in form completed but shows little effort at documenting/planning and team has not written any code.
* 0: First check in form was not completed.

### Instructor's Goals for Next Check In

* Goal 1: Health foods fall from the top

* Goal 2: Junk Foods fall from overlord

* Goal 3: Have some kind of canvas test for the draw functions

### Stretch Goals

* Health foods collide with tray and affect score, which is visible on the screen

### Feedback?
