# GameTime Submission Form

## Basics

[Spec]()

### Implemented with Websockets
[Repo](https://github.com/drew-t/node-gametime/)  
[Deployed](warlords1602.herokuapp.com)

### Implemented with Local Multiplayer
[Repo](https://github.com/drew-t/gametime/)  
[Deployed](jaredroth.github.io/warlords.html)

### Commits to Websockets
-[Drew](https://github.com/drew-t/node-gametime/commits?author=drew-t)  

### Commits to Local
-[Drew](https://github.com/drew-t/gametime/commits?author=drew-t)  
-[Josh](https://github.com/drew-t/gametime/commits?author=jwashke)  
-[Jared](https://github.com/drew-t/gametime/commits?author=JaredRoth)

### Provide a Screenshot of your Game
![Warlords](http://jaredroth.github.io/warlords/images/Gameplay.jpg)

---

## Completion

### Do You Consider the Application to be Fully Playable?
 - The local version is complete and in my (Jared's) opinion, more fun because of the social aspect.
 - The websockets version is missing a few features (like beginning and end of game flow) and has some synching problems.

### What Extensions, as Requested By an Instructor, Did You Complete?
- Multiplayer:
  - Using multiple keyboard inputs, we have 4 player single-screen multiplyer
  - Using websockets, we were also able to have four players connect to the game and control their respective paddles. Everything "works", but there is some lag which can cause the games to de-sync

### What Features, if Any, Do You Feel Exceed Instructor Expectations?
- We feel that because we intended to implement websockets from the very beginning, we began with high expectations for the project. (See below)

----

## Risk Taking
- Two biggest risks:
 - websockets out of the gate (I'm getting tired of typing that word)
 - Working almost completely remotely which led to some jagged merges and integrations
- Both risks directly caused growth as developers and as a team. 10/10 would do again.

----

## Code Quality

### [Ball.js in general... but this method particularly](https://github.com/drew-t/gametime/blob/b8164f6fc9472ae28f0138930b4e74b8ae7d5db8/lib/ball.js#L87-L104)
- Detecting which side of a block the ball hit was very difficult. We tried multiple methods with varying success but eventually come up with this. I am most proud of it because I didn't just lift it from SO... I adjusted something I found there and made it work better for us. (...Still not perfectly)

### [Grid Creation](https://github.com/drew-t/gametime/blob/b8164f6fc9472ae28f0138930b4e74b8ae7d5db8/lib/game.js#L68-L102)
- This could definitely have used some refactoring, but got left behind as we needed to complete features. Initially, it became this long because all of the 'things' it's doing were using the same derived variables and it felt weird to pass these repeatedly. Also, it's duplicating the same operations 4 times, but I couldn't dry these out because the conditions and final operation were performed with very unique combinations of the variables.

### Test Results

##### Paddle  
 - constructor  
  - with default attributes  
     - assigns a player that is passed in ‣
     - assigns the canvas that is passed in ‣
     - assigns a paddleWidth of 60 ‣
     - assigns a paddleHeight of 8 ‣
     - assigns left pressed to be false ‣
     - assigns right pressed to be false ‣
     - assigns vertical to be false ‣
     - assigns x as 10 ‣
     - assigns y as one third of the canvas height ‣
     - assigns oneThirdWidth as one third of the canvas width ‣
     - assigns oneThirdHeight as one third of the canvas height ‣
     - assigns rightKeyCode to be 39 ‣
     - assigns leftKeyCode to be 37 ‣

 - move
  - as player 1
    - with right key pressed
      - with the x too far to the right  
        - assigns true to vertical ‣
        - assigns x to equal one third of the canvas width ‣
        - assigns y to equal one third of the canvas minus the paddle width ‣  
      - with x not too far to the right and vertical equals true
        - subtracts 9 from the y ‣
      - with x not too far to the right and vertical equals false
        - adds 9 to the x ‣
    - with left key pressed
      - with the y too far down
        - assigns false to vertical ‣
        - assigns x to equal one third of the canvas width minus the paddle width ‣
        - assigns y to equal one third of the canvas height ‣
      - with y not too far down and vertical set to true
        - adds 9 to y ‣
      - with y not too far down and vertical set to false
        - subtracts 9 from x ‣
 - setPaddleX
    - as player 1 or 3
      - returns 10 ‣
    - as player 2 or 4
      - returns canvas width minus the paddle width minus 10 ‣
 - setPaddleY
    - as player 1 or 2
      - returns one third of the canvas height ‣
    - as player 3 or 4
      - returns one third of the canvas height times two ‣

##### Block
 - should take attributes
  - should recieve and assign an x coordinate ‣
  - should recieve and assign a y coordinate ‣
  - should recieve and assign a height ‣
  - should recieve and assign a width ‣
  - should recieve and assign a color ‣
  - should have a default render status of true ‣

##### Ball
 - should take attributes
  - should recieve and assign an x coordinate ‣
  - should recieve and assign a y coordinate ‣
  - should recieve and assign a radius ‣
  - should recieve and assign an x speed ‣
  - should recieve and assign a y speed ‣
  - should have a default collided status of false ‣
 - move
  - should change x by speed ‣
  - should change y by speed ‣
 - wallCollision
  - should not change speed or direction if not colliding ‣
  - should reverse y speed when the ball hits the top or bottom ‣
  - should reverse x speed when the ball hits the left or right ‣
 - checkQuadrant
  - should reset ball collided status ‣
 - blockCollision
  - does nothing if ball has already collided ‣
  - does nothing if block has been removed ‣
  - does nothing if ball and block do not collide ‣
  - sets ball collision to true and block render to false on collision ‣
  - should call whichSide function
 - intersects
  - should detect collision if overlapping ‣
  - should not detect collision if not overlapping ‣
 - whichSide
  - reverses ySpeed when colliding with top ‣
  - reverses ySpeed when colliding with bottom ‣
  - reverses xSpeed when colliding with left ‣
  - reverses xSpeed when colliding with right ‣
 - top
  - returns the center y coordinate minus the radius ‣
 - bottom
  - returns the center y coordinate plus the radius ‣
 - left
  - returns the center x coordinate minus the radius ‣
 - right
  - returns the center x coordinate plus the radius ‣

##### Game
 - should take and create attributes
  - should recieve and assign the ctx ‣
  - should recieve and assign the canvas ‣
  - should create empty ball array ‣
  - should create empty player array ‣
  - should establish block and player sizes ‣
 - beginRound
  - should create a ball inside the balls array
  - should call createGrid function
  - should begin the animation

### Test Breakdown
- 64 tests
- [These tests cover all behaviors happy/sad of the function in question](https://github.com/drew-t/gametime/blob/b8164f6fc9472ae28f0138930b4e74b8ae7d5db8/test/ball-test.js#L98-L141)

-----

## Instructor Feedback

- Points: (base 300)

## Evaluation Rubric

155/150

### Extra Credit

* **50 points**

Two different forms/repos for the multiplayer functionality 

### Functional Expectations

* **35 points** - Application is fully playable and exceeds the expecations set by instructors

### User Interface

* **10 points** - The application has many strong pages/interactions, but a few holes in lesser-used functionality.

### Testing

* **15 points** - Project has sporadic use of tests and multiple levels. The application contains numerous holes in testing and/or many features are untested.

Testing is A+ on clientside - Testing is F- on Node. 

### JavaScript Style

* **20 points** - Application is thoughtfully put together with some duplication and no major bugs. Developer can speak to choices made in the code and knows what every line of code is doing.

### Workflow

* **20 points** - The developer effectively uses Git branches and many small, atomic commits that document the evolution of their application.

### Code Sanitation

The output from JSHint shows…

* **5 points** - Six to ten complaints
