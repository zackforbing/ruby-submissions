

# GameTime Submission Form

## Basics

### Link to the Github Repository for the Project
[SquarePocalypse](https://github.com/jdliss/game-time)

### Link to the Deployed Application
[Follow instructions in ReadMe to run](https://github.com/jdliss/game-time)

### Link to Your Commits in the Github Repository for the Project
-[JonB](https://github.com/jdliss/game-time/commits?author=Jbern16)
 -[JonL](https://github.com/jdliss/game-time/commits?author=jdliss)

### Provide a Screenshot of your Game
-![Gameplay!](http://recordit.co/2mlKV4JWsB/gif/notify)

---

## Completion

### Do You Consider the Application to be Fully Playable?
 - Fully playable, more on the MVP side.  

### What Extensions, as Requested By an Instructor, Did You Complete?
  Varying Type of Zombies(Squares) with different behavior.

  * Follow Squares (Purple)
  
  * Flankers (Yellow)

  * Boomers (Big and Cyan)


### What Features, if Any, Do You Feel Exceed Instructor Expectations?
Overall gameplay. Although we pivoted to more of a geomatry wars style game, the game turned out quite fun.

Follow and sawrming AI is probably one of the harder features we implemented and we feel it works very very well.  


----

## Risk Taking
Java! We finished the project fully in Java with zero help from outside game or other libraries. We only used what we had access to via Java 8.

We learned much from this experience, especially the fundamentals of this language. We also had the benefit from having an outside user(Jake) reviewing the game and providing issues we had to fix. That was great real world experience. 
Through that, we learned a lot of best practices and how to structure our code better.  

----

## Code Quality

### Link to a specific block of your code on Github that you are proud of
[Proud Code](https://github.com/jdliss/game-time/blob/master/src/org/object/Zombie.java#L51-L86)

We like this code because the complexity but also the readability and how broken down the logic is.

This is how we calculate the path for the zombies.  

### Link to a specific block of your code on Github that you feel not great about
[Not Proud](https://github.com/jdliss/game-time/blob/master/src/org/object/Bullet.java#L38-L74)

We feel that this method is handling a bit too much. It figures out collision while figuring out where to go. Overall, I feel as if our collision detection is a bit repeated. 

As a first time it was hard to grasp a lot of decoupling techniques that is utilized in Java. My first thought is that the repeating of collision detection could be taken out in it own class instead of being figured out in each object. 



### Attach a screenshot or paste the output from your terminal of the result of your test-suite running.
[Test Suite](http://i.imgur.com/aNDfU56.png)

### Test Breakdown
Unit Test: 12


### Provide a link to an example, if you have one, of a unit test that covers an 'edge case' or 'unhappy path'
[Unhappy](https://github.com/jdliss/game-time/blob/master/src/org/object/ZombieTest.java#L41-L49)

We had trouble figuring out a way for squares to swarm properly if they dont start on a 45 degree angle, this tests a random angle to make sure the it moves approriately. 

-----



### Please feel free to ask any other questions or make any other statements below!

-----

## Instructor Feedback

- Points: 170/150

### Functional Expectations

* **35 points** - Application is fully playable and exceeds the expecations set by instructors

### User Interface

* **15 points** - The application is pleasant, logical, and easy to use. There no holes in functionality and the application stands on it own to be used by the instructor _without_ guidance from the developer.

### Testing

* **25 points** - Project has a running test suite that tests and multiple levels but fails to cover some features. All functionality is covered by tests. The application makes some use of integration testing.

### Java Style

* **30 points** - Application has exceptionally well-factored code with little or now duplication and all components separated out into logical components. There _zero_ instances where an instructor would recommend taking a different approach.

### Workflow

* **25 points** - The developer effectively uses Git branches and many small, atomic commits that document the evolution of their application.

### Code Review Feedback

Did issues created by code reviewer get addressed

* **15 points** - Yes

### Extra Credit

**25 points** Went above and beyond with working with mentors, code refactoring, best practices and understanding the language above just copying and pasting code that 'works' or bringing in 3rd party libraries in an unfamiliar language.
