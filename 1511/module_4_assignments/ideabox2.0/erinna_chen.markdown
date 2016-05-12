# Ideabox 2.0 Submission Form- Erinna Chen

## Basics
### The Project Description
[Project Spec](https://github.com/turingschool/curriculum/blob/master/source/projects/revenge_of_idea_box.markdown)

### Link to the Github Repository for the Project
[My Repo](https://github.com/erinnachen/genius-box)

### Link to the Deployed Application
[My sweet sweet production application](http://damp-island-60810.herokuapp.com/)

### Link to Your Commits in the Github Repository for the Project
[The Commits](https://github.com/erinnachen/genius-box/commits/master)

### Demo of the app
![demo](http://g.recordit.co/303ZVNzNjd.gif)

## Completion

### Were you able to complete the base functionality?
* I believe I got to base functionality. The only thing that I sort of skipped over was truncation of the body to 100 chars.

## Code Quality

### Link to a specific block of your code on Github that you are proud of
[Way DRYer than before](https://github.com/erinnachen/genius-box/blob/master/app/assets/javascripts/update_idea_quality.js#L3)
* Proud may be a little subjective. I think this is far cleaner than I started with. I had routes on the backend that would take care of all this, and there was different functions for upvoting and downvoting, and now it's relatively condensed. This can probably get a bit slimmer, but I'm cool.

### Link to a specific block of your code on Github that you feel not great about
[oooh that's painful](https://github.com/erinnachen/genius-box/blob/master/app/assets/javascripts/idea_helpers.js#L2)
* The challenge of this was that this element was pretty large. Come to think of it, I probably could have created strings for each part of the element. ES6 string interpolation may be a way to clean it up a bit.

### Attach a screenshot or paste the output from your terminal of the result of your test-suite running.
![covered](images/testing.png)

### Provide a link to an example, if you have one, of a test that covers an 'edge case' or 'unhappy path'
[Genius is superlative](https://github.com/erinnachen/genius-box/blob/master/spec/features/user_can_upvote_an_idea_spec.rb#L35)
* This test checks the case where you have reached the upper echilon of ideaness and want to continue to thumbs up your idea.

-----

### Please feel free to ask any other questions or make any other statements below!
My biggest question was the use of `$(document).ready(function(){})` for multiple JS files. I had to extract functions into the global namespace if I wanted to share them across files. Is that kosher? Is there a way to avoid all of this?

Also, why does Chrome not implement `Object.values()`? 😕
