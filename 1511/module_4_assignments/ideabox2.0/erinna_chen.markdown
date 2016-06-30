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
![covered](images/erinna_test.png)

### Provide a link to an example, if you have one, of a test that covers an 'edge case' or 'unhappy path'
[Genius is superlative](https://github.com/erinnachen/genius-box/blob/master/spec/features/user_can_upvote_an_idea_spec.rb#L35)
* This test checks the case where you have reached the upper echilon of ideaness and want to continue to thumbs up your idea.

-----

### Please feel free to ask any other questions or make any other statements below!
My biggest question was the use of `$(document).ready(function(){})` for multiple JS files. I had to extract functions into the global namespace if I wanted to share them across files. Is that kosher? Is there a way to avoid all of this?

Also, why does Chrome not implement `Object.values()`? 😕

--------

# Instructor Feedback

Nice work! I left some notes inline in the sections below!

143/150

### Data Model

(5 points total.)

### User Flows

#### Viewing ideas

(5 points total.)

- Missing truncation

#### Adding a new idea

(15 points total.)

#### Deleting an existing idea

(15 points total.)

#### Changing the quality of an idea

(15 points total.)

#### Editing an existing idea

(20 points total.)

#### Idea Filtering and Searching

(15 points total.)

## Instructor Evaluation Points

### Specification Adherence

* **10 points**: The application consists of one page with all of the major functionality being provided by jQuery. There is no use of `format.js` in Rails. There is no use of unobstrusive JavaScript. There are no front-end frameworks used in the application. No approach was taken that is counter to the spirit of the project and its learning goals. There are no features missing from above that make the application feel incomplete or hard to use.

### User Interface

* **5 points** - The application is pleasant, logical, and easy to use. There no holes in functionality and the application stands on it own to be used by the instructor _without_ guidance from the developer.

### Testing

* **10 points** - Project has a running test suite that exercises the application at multiple levels including JavaScript tests.

### Ruby and Rails Quality

* **10 points** - Developer is able to craft Rails features that make smart use of Ruby, follow the principles of MVC, and push business logic down where it belongs. There _zero_ instances where an instructor would recommend taking a different approach. Developer writes code that is exceptionally clear and well-factored. Application is expertly divided into logical components each with a clear, single responsibility.

### JavaScript Style

Notes:
  - Good use of delegation.
  - [Spacing is off in a few places](https://github.com/erinnachen/genius-box/blob/master/app/assets/javascripts/update_idea_quality.js#L23-L30)
  - An easier way to do document.ready would be to have larger functions that do set up for you and calling them all in the document.ready block - You don't need to wrap all of your JS code in it.

* **8 points** - Application is thoughtfully put together with some duplication and no major bugs. Developer can speak to choices made in the code and knows what every line of code is doing.

### Workflow

Notes: You already have the information that you need in the submission forms - don't skip the READMEs!

* **10 points** - The developer effectively uses Git branches and many small, atomic commits that document the evolution of their application.
