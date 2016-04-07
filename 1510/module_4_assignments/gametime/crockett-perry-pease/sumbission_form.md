Complete this Form before the final eval. Delete this line from your version.

# GameTime Submission Form

## Basics

### Link to the Github Repository for the Project
[Our Repo](https://github.com/jecrockett/gametime)

### Link to the Deployed Application
[Faux-Gar](https://faux-gar.herokuapp.com/#)

### Link to Your Commits in the Github Repository for the Project
[James Crockett Commits](https://github.com/jecrockett/gametime/commits?author=jecrockett)

[Joe Perry Commits](https://github.com/jecrockett/gametime/commits?author=jwperry)

[Justin Pease Commits](https://github.com/jecrockett/gametime/commits?author=Jpease1020)
### Provide a Screenshot of your Game
![Faux-Gar](http://g.recordit.co/rIWwfFOf8m.gif)

---

## Completion

### Do You Consider the Application to be Fully Playable?
 - Yes.  It is a fully playable continuous multiplayer game.  The goal is to be the biggest player.  

### What Extensions, as Requested By an Instructor, Did You Complete?
- Multiplayer - we have a game that allows as many players as the server can handle.
[Server.js lines 59 -83](https://github.com/jecrockett/gametime/blob/3a2ee23577ed2689b1598d64deb69cad46d7c795/server.js#L59-L83)

- WebSockets - we have WebSockets sending information back and forth between the server and the clients(players).
[Server](https://github.com/jecrockett/gametime/blob/master/server.js)
[Client](https://github.com/jecrockett/gametime/blob/master/public/client.js)

### What Features, if Any, Do You Feel Exceed Instructor Expectations?
 - [Websocket communication](https://github.com/jecrockett/gametime/blob/3a2ee23577ed2689b1598d64deb69cad46d7c795/server.js#L59-L83)
 - [Canvas Scaling](https://github.com/jecrockett/gametime/blob/3a2ee23577ed2689b1598d64deb69cad46d7c795/public/client.js#L231-L243)

----

## Risk Taking
We were told during our initial game proposal that our instructors "might suggest picking another game," so we feel the whole project was ambitious and something of a risk. Namely, we tackled a real-time updating multi-player game in 10-days using a language we formally started learning 20-days ago. We're incredibly proud of what we produced.

----

## Code Quality

### Link to a specific block of your code on Github that you are proud of
- [Speed Boost Logic](https://github.com/jecrockett/gametime/blob/b676f3a2376f3655a6793b631a28b5b4418b6833/public/online-player.js#L96-L100)
- [Partial Application](https://github.com/jecrockett/gametime/blob/3a2ee23577ed2689b1598d64deb69cad46d7c795/public/online-player.js#L14-L28)


### Link to a specific block of your code on Github that you feel not great about
- [Eat Functions](https://github.com/jecrockett/gametime/blob/b676f3a2376f3655a6793b631a28b5b4418b6833/public/online-player.js#L38-L72)
- These need to be refactored. We have a feeling this might be a good spot to use currying. We have a ton of repetition in our eat functions when we calculate the distance between objects for collision detection, but then we perform different actions depending on what set of objects have collided and weren't positive how to handle that.
- [Seed Functions](https://github.com/jecrockett/gametime/blob/87221f66b81fe4515a2b232150d4dbd3a354dad6/lib/food-generator.js#L13-L37)
- Similar to above.  All seed functions are very identical and could be refactored.

### Attach a screenshot or paste the output from your terminal of the result of your test-suite running.
![](http://g.recordit.co/BO485XzQrX.gif)

### Test Breakdown
- 35 Unit Tests
- 16 Feature Tests

### Provide a link to an example, if you have one, of a unit test that covers an 'edge case' or 'unhappy path'
[Conditions when player cannot move](https://github.com/jecrockett/gametime/blob/3a2ee23577ed2689b1598d64deb69cad46d7c795/test/player-movements-test.js#L57-L101)

### Provide a link to an example, if you have one, of a feature test that covers an 'edge case' or 'unhappy path'
[Conditions when player cannot eat virus](https://github.com/jecrockett/gametime/blob/3a2ee23577ed2689b1598d64deb69cad46d7c795/test/player-eats-virus-test.js#L38-L64)

[Conditions when player cannot eat player](https://github.com/jecrockett/gametime/blob/3a2ee23577ed2689b1598d64deb69cad46d7c795/test/players-eats-player-test.js#L38-L74)

-----

### Please feel free to ask any other questions or make any other statements below!

-----

## Instructor Feedback

- Points: (base 300)
