# GameTime Submission Form

## Basics

### Link to the Github Repository for the Project
[The Repo](https://github.com/adriennedomingus/bubble_bobble/)

### Link to the Deployed Application
[Bubble Bobble Redux](http://bubble-bobble-redux.herokuapp.com/)

### Link to Your Commits in the Github Repository for the Project
[All the commits](https://github.com/adriennedomingus/bubble_bobble/commits/master)
### Provide a Screenshot of your Game
![Single Player](http://g.recordit.co/u35EwWHzXw.gif)

![Battle Zone](http://recordit.co/CAgkMS6US1.gif)

## Completion

### Do You Consider the Application to be Fully Playable?

 - Yes, though it feels like we could work on the project for a year, and maybe be finished - there's always more features to add. There are some minor playability issues: mostly styling - it could be clearer to the user what is happening and to whom (level transitions, who which scores belong to in 2 player mode, etc.)

### What Extensions, as Requested By an Instructor, Did You Complete?

* Two player mode  
* Moving app to Express

### What Features, if Any, Do You Feel Exceed Instructor Expectations?

-I'm not totally clear on what extensions were "required" vs. not. Those mentioned above were beyond the scope of the project spec.

## Risk Taking

- What risks did you feel you took on this project?

The project concept in general was more complicated than it needed to be to meet base project requirements - with a lot of moving pieces. The two most challenging pieces were creating a jump that looked natural (there are a lot of "phases" to the jump with different behavior in each of them), and not allowing him to walk through the vertical walls in level three. (Most collision looked for general overlap, while that required specific left:right edge and right:left edge collision).

- How do you feel about those risks?

Good. I think we would have gotten bored if we hadn't taken them. However, our code quality did suffer in order to complete the features we did, and has more redundancy than we would like.

## Code Quality

### Link to a specific block of your code on Github that you are proud of

[A jumping dinosaur](https://github.com/adriennedomingus/bubble_bobble/blob/3d2ca8d69921d6b3f05d6f49bb7a9b577d69bf6e/lib/dinosaur.js#L119-L129)
- Why were you proud of this piece of code?

All of the logic has been pulled out into small, reusable pieces of code, that makes this specific block very human-readable. It is clear what is going on in each branch of the flow control

### Link to a specific block of your code on Github that you feel not great about

[The Game Play Class](https://github.com/adriennedomingus/bubble_bobble/blob/3d2ca8d69921d6b3f05d6f49bb7a9b577d69bf6e/lib/game.js)

I would argue that this is less than our best showing in general. It was in significantly better shape before we added two-player mode, which introduced a host of duplication. Since that happened so late, we didn't have the opportunity to refactor we might have liked.

### Attach a screenshot or paste the output from your terminal of the result of your test-suite running.

![Part One](https://docs.google.com/drawings/d/1QcVbXVdySJa_pd_7FY7YUkX9HWl8CvK2PVnEjx4BALI/pub?w=960&h=503)
![Part Two](https://docs.google.com/drawings/d/10OA3PvmZw7vaenePhieCJ3bFJnSktEhT_DcPQLXoQpc/pub?w=969&h=481)

### Test Breakdown
- How Many Unit Tests?

43

- How Many Feature/Integration Tests?

I'm going to go with zero.

### Provide a link to an example, if you have one, of a unit test that covers an 'edge case' or 'unhappy path'

[Bub and Bob unfortunately cannot walk through walls.](https://github.com/adriennedomingus/bubble_bobble/blob/3d2ca8d69921d6b3f05d6f49bb7a9b577d69bf6e/test/dinosaur-test.js#L55-L60) They only wish they could

-----

### Please feel free to ask any other questions or make any other statements below!

-----

## Instructor Feedback

- Points: (base 300)
