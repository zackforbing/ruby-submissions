# Game Time Check In # 1

## Basics

### Team
- [Chelsea Johnson](https://github.com/cheljoh)
- [July Tran](https://github.com/julyytran)

### Game Name
GO GO NYAN CAT

### Give a Basic Description of the Game

Nyan cat avoids veggies and eats candy. More candy = more points. Loses points and lives when it eats veggies.

### Include a Link to or Screen Shot of the Game

[Nyan Cat Fly](http://www.addictinggames.com/funny-games/nyan-cat-fly-game.jsp)

### Link to the Github repository for the project
[Repo](https://github.com/cheljoh/game-time)

## The Plan

### Describe Your goals for the finished product

- Nyan cat moves up and down on the left side of the screen
- Background is 8-bit outer space
- It moves up or down to eat candy and avoid veggies.
- You gain points for every piece of candy you eat
- You start with three lives
- If you eat a veggie, you lose a life. Once all three lives are gone, game over
- Every time you eat a veggie, a message appears (ex: "cabbage, yuck! -10 points")
- If you eat 10 pieces of candy, you get a life back (can have a max of 3)
- If you gain 200 points, you progress to a new level. Items appear more quickly and there are more veggies to avoid.
- Pressing P pauses the game
- Will have the Nyan cat music in the background

Optional:
- Turing mode- you avoid Allans and try to eat Julians
- Jorge mode- you eat burritos and don't avoid anything
- Konami code- surprise!
- Fancy mode- piano music and Nyan cat has a top hat

### What is your MVP, or 'this was harder than I thought' plan?

- Nyan cat moves up and down
- Nyan cat eats candies
- Nyan cat avoids veggies
- If Nyan cat hits a veggie, they lose a life
- If they lose 3 lives, game over

### What have you accomplished so far?
Rendering background and Nyan cat image. Nyan cat moves up and down in fixed positions on the left side of the screen.

### Questions, Comments, Concerns?
How can we render the cat in each quadrant? Right now, looping through all y values when it goes up. Do we need a game loop? Also, we need to npm run build each time we make a change. Is this unusual?


## Instructor Section

### Points for first check in (base 50)

50/50

### Instructor's goals for next check in

- Get testing set up, and test collision detection (a few other non-drawing methods)
- Clean up collision detection
- Begin implementing toasters

### Extension

- Test and render game reactions to toasters
- Visual indication of score that resets

### Feedback?
