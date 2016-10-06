# Ideabox 2.0 Submission Form
[Project Spec](https://github.com/turingschool/curriculum/blob/master/source/projects/revenge_of_idea_box.markdown)

# Basics

### Link to the Github Repository for the Project
[GitHub](https://github.com/ryanflach/idea_box)

### Link to the Deployed Application
[Heroku](http://idea-box-rf.herokuapp.com/)

### Link to Your Commits in the Github Repository for the Project
[Commits](https://github.com/ryanflach/idea_box/commits/master)

### Provide a Screenshot of your Application
![Screenshot](http://i.imgur.com/1WOQchS.png)

## Completion

### Were you able to complete the base functionality?
* Yes.

### Which extensions, if any, did you complete?
* N/A

# Code Quality

### Link to a specific block 'good' code on Github
* [$(document).ready block in ideas.js](https://github.com/ryanflach/idea_box/blob/master/app/assets/javascripts/ideas.js#L1-L7)
  * Refactoring in JavaScript has been challenging, due to inexperience with the language. It was important to me to have a readable `$(document).ready` section that included only calls to functions that were defined outside of the block, and that identified clearly what was happening when the page loads. I feel that I accomplished that goal with this code.

### Link to a specific block of 'bad' code on Github
* [Redundancy in functions to update idea title/body](https://github.com/ryanflach/idea_box/blob/master/app/assets/javascripts/ideas.js#L220-L261)
  * There is a lot of redundancy in this code that I lacked the confidence to refactor, due to a lack of full comfort and familiarity with `this` and `event.target` when it goes more than one level. I know this code could be better, but I didn't spend the time to get it where I wanted, and so it is currently a deficiency in my code.

### Test Suite Status
```
Ryans-MacBook-Air:idea_box Ryan$ rspec
.......................

Finished in 15.99 seconds (files took 2.47 seconds to load)
23 examples, 0 failures

Coverage report generated for RSpec to /Users/Ryan/turing/4module/projects/idea_box/coverage. 424 / 424 LOC (100.0%) covered.
```

### Link to an example of a test that covers an 'edge case' or 'unhappy path'
* [Ensure new ideas are searchable](https://github.com/ryanflach/idea_box/blob/master/spec/features/search_for_an_idea_spec.rb#L54-L81)
