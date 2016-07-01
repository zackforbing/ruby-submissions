# Sal Ideabox 2.0 Submission
[Project Spec](https://github.com/turingschool/curriculum/blob/master/source/projects/revenge_of_idea_box.markdown)

------

# Basics

### Link to the Github Repository for the Project
[Ideabox](https://github.com/s-espinosa/idea_box)

### Link to the Deployed Application
[s-espinosa-ideabox](http://s-espinosa-ideabox.herokuapp.com/)

### Link to Your Commits in the Github Repository for the Project
[Commits](https://github.com/s-espinosa/idea_box/commits/master)

### Provide a Screenshot of your Application
![ideabox](images/sal.png)

## Completion

### Were you able to complete the base functionality?
No.

* Ideas limited to 100 characters when displayed.

### Which extensions, if any, did you complete?
None.

### Attach a .gif, or images of any extensions work being used on the site.

# Code Quality

### Link to a specific block of your code on Github that you are proud of
[load.js](https://github.com/s-espinosa/idea_box/blob/master/app/assets/javascripts/load.js)
* To me this code nicely breaks out the high-level process that occurs on page load. I like the way it describes the things that need to happen when a user first visits the site without being cluttered with detail.

### Link to a specific block of your code on Github that you feel not great about
[upgrade_idea.js](https://github.com/s-espinosa/idea_box/blob/master/app/assets/javascripts/upgrade_idea.js)
[downgrade_idea.js](https://github.com/s-espinosa/idea_box/blob/master/app/assets/javascripts/downgrade_idea.js)
* There's a lot of duplication in these two files. They're performing very similar actions, but just moving in opposite directions. Ultimately I found it easier to track what was happening for each of these buttons by having completely separate processes, but I could have removed some duplication by adding the ability to pass a direction (e.g. up/down) at the beginning of the process. It felt like that might be adding some unnecessary complexity around the conditions for switching from swill to plausible to genius, so I didn't pursue that path, but still don't feel entirely happy about it.

### Attach a screenshot or paste the output from your terminal of the result of your test-suite running.
```
When a user adds an idea
  the new idea is displayed

When a user deletes an idea
  the idea is removed from the page and deleted

When a user adds an idea
  the new idea is displayed

When a user rates an idea
  the rating is increased with thumbs up
  the rating is decreased with thumbs down
  the rating is not impacted by invalid ratings

When a user deletes an idea
  the idea is removed from the page and deleted

When a user visits root
  they see a list of ideas

POST /api/v1/ideas
  creates and returns an idea

DELETE /api/v1/ideas/:id
  deletes an idea from the database

GET /api/v1/ideas
  returns a list of all ideas

PATCH /api/v1/ideas
  updates an idea

Finished in 3.31 seconds (files took 2.59 seconds to load)
12 examples, 0 failures

Coverage report generated for RSpec to /Users/sespinos/Documents/web/school/turing/4module/projects/idea_box/coverage. 29 / 29 LOC (100.0%) covered.
```

### Provide a link to an example, if you have one, of a test that covers an 'edge case' or 'unhappy path'

[Rating not impacted by invalid ratings](https://github.com/s-espinosa/idea_box/blob/b4518d4ef187590dde443766f262dc7d480ecb50/spec/features/user_can_rate_ideas_spec.rb#L34-L53)

-----

​
### Data Model
​
(5 points total.)
​
We'll be primarily working with _Idea_ objects.
​
* An Idea has a _title_, a _body_, and a _quality_. (1 point)
  * _title_ and _body_ are free-form strings.
* _quality_ can be represented however you feel best in the database,
  but in the user interface it should manifest as the options "genius", "plausible", and "swill" (2 points)
* By default, the idea's "quality" should default to the lowest setting (i.e. "swill"). (2 points)
​
### User Flows
​
#### Viewing ideas
​
(5 points total.)
​
On the application's root, the user should:
​
* See a list of all existing ideas, including the title, body, and quality for each idea. (2 points, mandatory for specification adherence)
* Ideas should appear in descending chronological order (with the most recently created
  idea at the top). (3 points)
​
#### Adding a new idea
​
(15 points total.)
​
On the application's main page, a user should:
​
* See two text boxes for entering the "Title" and "Body" for a new idea,
  and a "Save" button for committing that idea. (3 points, mandatory for specification adherence)
​
When a user clicks "Save":
​
* A new idea with the provided title and body should appear in the idea list. (5 points, mandatory for specification adherence)
* The text fields should be cleared and ready to accept a new idea. (2 points)
* The page _should not_ reload. (3 points, mandatory for specification adherence)
* The idea should be committed to the database. It should still be present upon reloading the page. (2 points, mandatory for specification adherence)
​
#### Deleting an existing idea
​
(15 points total.)
​
When viewing the idea list:
​
* Each idea in the list should have a link or button to "Delete" (or 𝗫, etc). (2 points)
* Upon clicking "Delete", the appropriate idea should be removed from the list (5 points, mandatory for specification adherence).
* The page _should not_ reload when an idea is deleted. (5 points, mandatory for specification adherence)
* The idea should be removed from the database. It should not re-appear on next page load. (3 points, mandatory for specification adherence)
​
#### Changing the quality of an idea
​
(15 points total.)
​
As we said above, ideas should start out as "swill." In order to change the recorded quality of an idea, the user will interact with it from the idea list.
​
* Each idea in the list should include a "thumbs up" and "thumbs down" button. (3 points)
* Clicking thumbs up on the idea should increase its quality one notch ("swill" → "plausible",
  "plausible" → "genius"). (4 points)
* Clicking thumbs down on the idea should decrease its quality one notch ("genius" → "plausible",
  "plausible" → "swill"). (4 points)
* Incrementing a "genius" idea or decrementing a "swill" idea should have no effect. (4 points)
​
#### Editing an existing idea
​
(20 points total.)
​
* When a user clicks the title or body of an idea in the list, that text should become an editable text field, pre-populated with the existing idea title or body. (8 points)
* Clicking this link should _not_ take the user to a separate "edit" page for the given
  idea. (4 points, mandatory for specification adherence)
*  The user should be able to "commit" their changes by pressing "Enter/Return" or by clicking outside of the text field. (4 points)
* If the user reloads the page, their edits will be reflected. (4 points, mandatory for specification adherence)
​
#### Idea Filtering and Searching
​
(15 points total.)
​
We'd like our users to be able to easily find specific ideas they already created, so
let's provide them with a filtering interface on the idea list.
​
* At the top of the idea list, include a text field labeled "Search". (3 points)
* As a user types in the search box, the list of ideas should filter in real time to only display ideas whose title or body include the user's text. The page _should not_ reload. (6 points)
* Clearing the search box should restore all the ideas to the list. (6 points)
​
### Extensions

## Instructor Evaluation Points
​
### Specification Adherence
​
* **10 points**: The application consists of one page with all of the major functionality being provided by jQuery. There is no use of `format.js` in Rails. There is no use of unobstrusive JavaScript. There are no front-end frameworks used in the application. No approach was taken that is counter to the spirit of the project and its learning goals. There are no features missing from above that make the application feel incomplete or hard to use.
​
### User Interface
​
* **5 points** - The application is pleasant, logical, and easy to use. There no holes in functionality and the application stands on it 
​
### Testing
​
* **10 points** - Project has a running test suite that exercises the application at multiple levels including JavaScript tests.

​
### Ruby and Rails Quality
​
* **10 points** - Developer is able to craft Rails features that make smart use of Ruby, follow the principles of MVC, and push business logic down where it belongs. There _zero_ instances where an instructor would recommend taking a different approach. Developer writes code that is exceptionally clear and well-factored. Application is expertly divided into logical components each with a clear, single responsibility.
​
### JavaScript Style
​
* **8 points** - Application is thoughtfully put together with some duplication and no major bugs. Developer can speak to choices made in the code and knows what every line of code is doing.

### Workflow
​
* **7 points** - The developer makes a series of small, atomic commits that document the evolution of their application. There are no formatting issues in the code base.
* 
### score: 140
