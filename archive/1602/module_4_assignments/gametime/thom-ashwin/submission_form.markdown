# GameTime Submission Form

## Basics

### Link to the Github Repository for the Project
[Your Repo](https://github.com/theonlyrao/1942)

### Link to the Deployed Application
[Your Application](https://theonlyrao.github.io/1942/)

### Link to Your Commits in the Github Repository for the Project
[Thom's commits](https://github.com/theonlyrao/1942/commits/master?author=thompickett)

[Ashwin's commits](https://github.com/theonlyrao/1942/commits/master?author=theonlyrao)

### Provide a Screenshot of your Game
![1942](./images/1942_screenshot.png)

---

## Completion

### Do You Consider the Application to be Fully Playable?
Yes, the application is fully functional.

### What Extensions, as Requested By an Instructor, Did You Complete?
We did not complete any extensions.

### What Features, if Any, Do You Feel Exceed Instructor Expectations?
We did exetensive refactoring of plane classes in order to dry up our code and also to take advantage of new ES6 syntacical sugar. It is difficult to link to particular code that shows this, but the plane directory is [here](https://github.com/theonlyrao/1942/tree/master/lib/javascripts/planes).

----

## Risk Taking
The risks we took in this project are mostly under the surface. There are a lot of moving pieces in this game, as well as a need to inject randomness in order to make the game exciting. Building these features while also following good OOP design patterns was difficult.

----

## Code Quality

### Link to a specific block of your code on Github that you are proud of
We are proud of our [collision detector](https://github.com/theonlyrao/1942/blob/master/lib/javascripts/collision_detector.js). First, we did it by hand in order to deal with the fact that our objects are not rectangles. Second, we did a lot of work to optimze the detection, such as limiting the cases in which detection was necessary.

We also saw the benefits of TDD in this class. Because we knew that we simply wanted to be able to give it two objects and have it tell us whether they were going to collide or not, we were able to separate this class out and keep our code that much simpler.

### Link to a specific block of your code on Github that you feel not great about
We are not thrilled about how we handle the creation of [levels](https://github.com/theonlyrao/1942/blob/master/lib/javascripts/level.js#L23-L37). There is too much happening in this particular function, because it is being asked to determine how many planes are created, what kinds of planes those are, and when they are "launched" into the game.

We would very much have liked to apply SRP in this class. However, we did not implement levels until after we had all other elements in place. Although we tried to prepare for the implementation of levels, there were some things we didn't anticipate that resulted in this mishmash of code.

This class is definitely an area we would have done very differently if we did this project again.

### Attach a screenshot or paste the output from your terminal of the result of your test-suite running.
Test Suite Output
![test suite output](./images/test_suite.png)

### Test Breakdown
- 26 unit tests

- 2 integration tests

### Provide a link to an example, if you have one, of a unit test that covers an 'edge case' or 'unhappy path'
[Testing that plane can't move past bottom edge of canvas](https://github.com/theonlyrao/1942/blob/master/test/plane_moves_test.js#L74-L78)

### Provide a link to an example, if you have one, of a feature test that covers an 'edge case' or 'unhappy path'
[Testing that collisions are detected even if touching at just one point](https://github.com/theonlyrao/1942/blob/master/test/destroy_planes_test.js#L6-L23)

-----

### Please feel free to ask any other questions or make any other statements below!
It was great to go from knowing no javascript to feeling like we have some ability to write good OOP javascript.

-----

## Instructor Feedback

- Points: (base 300)
Functional Expectations

25 points - Application is fully playable without crashes or bugs

User Interface

15 points - The application is pleasant, logical, and easy to use. There no holes in functionality and the application stands on it own to be used by the instructor without guidance from the developer.

Testing

27 points - Project has a running test suite that tests and multiple levels but fails to cover some features. All functionality is covered by tests. The application makes some use of integration testing.

Javscript Style 

24 points - Application is thoughtfully put together with some duplication and no major bugs. Developer can speak to choices made in the code and knows what every line of code is doing.

Workflow

25 points - The developer effectively uses Git branches and many small, atomic commits that document the evolution of their application.

The output from JSHint shows…

15 points - Zero complaints

total:286 (including check ins)
