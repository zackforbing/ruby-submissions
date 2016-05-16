Complete this Form and the README.md before the first check in. Delete this line from your version.

# Game Time Check In # 1

## Basics

### Team
- [Penney Garrett](https://github.com/penneygadget)
- [Beth Sebian](https://github.com/bethsebian)

### Game Name
Infinite Loop

### Give a Basic Description of the Game
Users are presented with images of lines and corners that they have to rotate to connect to each other to make a the original, beautiful pattern with no end fragments.

### Include a Link to or Screen Shot of the Game

[Infinite Loop](http://drewcogbill.com/mobilemedia/wp-content/uploads/2015/05/Screen-Shot-2015-05-13-at-4.06.34-PM.png)

### Link to the Github repository for the project
[Penney Garrett Game Time Repo](https://github.com/PenneyGadget/game-time)

## The Plan

### Describe Your goals for the finished product

- Start screen invites player to start game.
- User clicks on shapes to rotate the shape.
- When no unconnected endpoints remain, user has solved problem and the screen pulses with light briefly.
- As the player advances through different patterns, the size of the pattern canvas grows.
- After completing a level, screen announces how many challenges the player has completed.
- Game contains 15 patterns minimum.
- Each shape unit is one of five arrangements: partial circle, circle with spoke, straight line, double curve, quadruple curve.
- Game remembers user and starts them at the level they last completed.
- TBD: autogenerate patterns or autogenerate pattern scramble

### What is your MVP, or 'this was harder than I thought' plan?

- Start screen invites player to start game.
- User clicks on shapes to rotate the shape.
- When no unconnected endpoints remain, user has solved problem ~~and the screen pulses with light briefly.~~
- ~~As the player advances through different patterns, the size of the pattern canvas grows.~~
- After completing a level, screen announces how many challenges the player has completed.
- Game contains 3 ~~15~~ patterns minimum.
- Each shape unit is one of two ~~five~~ arrangements: partial circle and circle with spoke ~~straight line, double curve, quadruple curve.~~
- ~~Game remembers user and starts them at the level they last completed.~~

### What have you accomplished so far?
- Determined how to draw arcs and other shapes
- Developed strategy for actions that will follow user clicks (rotations)
- Narrowed down color scheme
- Developed game scope
- Determined origin pattern (circle)

### Questions, Comments, Concerns?
- Does it make sense as beginners to build levels independently?
- Should we aim for patterns to have ability to autogenerate?

-----

## Instructor Section

### Points for first check in (base 50)

50
Great use of codepen!

### Instructor's goals for next check in

- Create a Shape constructor which can handle creating at least one shape
- Have two to four shape blocks rendering and with testing (not 100% exactly but some testing hooked up).

### Feedback?

Try to balance showing things on the screen and styling them against doing the backend.
