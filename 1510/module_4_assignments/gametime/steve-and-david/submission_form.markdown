#Shrimpin' Ain't Easy || Submission Form

## Basics

### Link to the Github Repository for the Project
[GameTime](https://github.com/stevepentler/GameTime)

### Link to the Deployed Application
[Shrimpin' Ain't Easy](http://stevepentler.github.io/GameTime/)

### Link to Your Commits in the Github Repository for the Project
- [Steve](https://github.com/stevepentler/GameTime/commits?author=stevepentler)
- [David](https://github.com/stevepentler/GameTime/commits?author=dastinnette)

### Provide a Screenshot of your Game
[Shrimpin' Ain't Easy](http://i.imgur.com/kDdYfDo.png?1)

---

## Completion

### Do You Consider the Application to be Fully Playable?
 - Yes

### What Extensions, as Requested By an Instructor, Did You Complete?
Implemented p5.js library:
- Our initial goal was to play a song from the Forrest Gump soundtrack, then base the motion of the shrimp on the amplitude of the song.
- [Our implementation](https://gist.github.com/stevepentler/99d89ad4ef79b9fae0dd628961e7bbd7)

----

## Risk Taking
- What risks did you feel you took on this project?
  1. p5 implementation required a lot of persistence. Running these two tools side by side presented a great deal of challenges, and p5 features intricacies that aren't clear in the documentation. We feel this was a creative solution - passing information from p5 to an invisible element on the DOM and then ripping the information using jQuery. Though it's recognizably a workaround solution, this strategy tied in a number of client-side concepts.
  2. Strong attempts to refactor code.
- How do you feel about those risks?
  1. Ultimately, we achieved our goal. Though the success of this app wasn't dependent on p5, we think it adds a unique flavor to our game. In addition, we are excited to have a better understanding of the possibilities of p5.
  2. We spent an immense amount of time both successfully and unsuccessfully refactoring code. It's definitely frustrating to spend a couple hour trying to refactor, then git stashing all of your changes. On the bright side, we were able to isolate our drawObjects and moveObjects functions.

----

## Code Quality

### Link to a specific block of your code on Github that you are proud of
[Extracting functions from Game file](https://github.com/stevepentler/GameTime/blob/3aa670cb349737941a84ceaedb8ba5ffcd2b2875/lib/game.js#L42-L52)
- We extracted object move and draw functions into separate files reducing clutter in the main Game file.

### Link to a specific block of your code on Github that you feel not great about
[Bullet functions within Game file](https://github.com/stevepentler/GameTime/blob/3aa670cb349737941a84ceaedb8ba5ffcd2b2875/lib/game.js#L54-L73)
- We made multiple attempts to extract bullet functions out of the game file but it was too difficult to track the state (active vs inactive) of the bullet in another file.

### Attach a screenshot or paste the output from your terminal of the result of your test-suite running.
[Tests on tests](http://i.imgur.com/sKnhN64.png?1)

### Test Breakdown
- How Many Unit Tests?
  - 22
- How Many Feature/Integration Tests?
  - 21

### Provide a link to an example, if you have one, of a unit test that covers an 'edge case' or 'unhappy path'
[Collision edge case](https://github.com/stevepentler/GameTime/blob/4d4a6a4a7c332b71ceddd49d506a9aefdc998e88/test/collision-test.js#L45-L53)
- Tested an edge case where a collision is verified even with variable fish dimensions.

### Provide a link to an example, if you have one, of a feature test that covers an 'edge case' or 'unhappy path'
[Recognizes false collision](https://github.com/stevepentler/GameTime/blob/fd00c98af2c1b8caa89218856a58bc0323345fc7/test/collision-test.js#L95-L104)
- We tested direct hit collisions and edge case partial collisions in the code above this segment. We also successfully verified misses.

-----

### Please feel free to ask any other questions or make any other statements below!

-----

## Instructor Feedback

- Points: 135
- 
## Evaluation Rubric

There are 300 total available points for this project.

150 are available at each of three check-ins and are at instructor descretion.

Teams must complete the [submission form prior to each check-in](https://github.com/turingschool/ruby-submissions/tree/master/1510/module_4_assignments/gametime/template).

150 out of a total of 300 points are included in the rubric below. The additional 150 feature points will be determined during iteration planning with instructors during check-ins.

### Functional Expectations

* **35 points** - Application is fully playable and exceeds the expecations set by instructors

### User Interface

* **15 points** - The application is pleasant, logical, and easy to use. There no holes in functionality and the application stands on it own to be used by the instructor _without_ guidance from the developer.

### Testing

* **25 points** - Project has a running test suite that tests and multiple levels but fails to cover some features. All controller actions are covered by tests. The application makes some use of integration testing.

### JavaScript Style

* **20 points** - Application is thoughtfully put together with some duplication and no major bugs. Developer can speak to choices made in the code and knows what every line of code is doing.

### Workflow

* **25 points** - The developer effectively uses Git branches and many small, atomic commits that document the evolution of their application.

### Code Sanitation

The output from JSHint shows…

* **15 points** - Zero complaints
