###Ideabox 2.0 Submission Form

* [Project Spec](https://github.com/turingschool/curriculum/blob/master/source/projects/revenge_of_idea_box.markdown)

###Basics

* [Github Repo](https://github.com/chadellison/idea_box)

* [Heroku](https://idea-box-123.herokuapp.com/)

* [Commits](https://github.com/chadellison/idea_box/commits/master)

###Screenshot

###Were you able to complete the base functionality?
* Yes, All base functionality and two extensions were completed

###Which extensions, if any, did you complete?
* I did the sorting extension and a student led extension. Users can filter by quality

###Code Quality

###Link to a specific block of your code on Github that you are proud of
* [Proud of](https://github.com/chadellison/idea_box/blob/master/app/assets/javascripts/filter.js)
  This was a fun challenge to tackle and it was when JS started to click for me.

* [Not proud of](https://github.com/chadellison/idea_box/blob/master/app/assets/javascripts/sort.js)
  This makes me feel dirty. I'm sure there are several ways this could be better; I kept hitting strange ambiguities that I did not expect.

###Attach a screenshot or paste the output from your terminal of the result of your test-suite running.
  idea_box :: (refactor-methods) » rspec                                                                  ~/turing/4module/projects/idea_box
  .......****..........

  Pending: (Failures listed here are expected and do not affect your suite's status)

  1) User can add an idea User sees new idea
     # No reason given
     # ./spec/features/user_can_add_an_idea_spec.rb:4

  2) user can remove ideas users no longer sees the ideas
     # No reason given
     # ./spec/features/user_can_delete_ideas_spec.rb:4

  3) User can see ideas User sees ideas
     # No reason given
     # ./spec/features/user_can_see_ideas_spec.rb:4

  4) user can thumbs up an idea user sees adjusted idea quality
     # No reason given
     # ./spec/features/user_can_thumbs_up_and_thumbs_down_ideas_spec.rb:4


  Finished in 0.20245 seconds (files took 2.58 seconds to load)
  21 examples, 0 failures, 4 pending


# Instructor Notes

160/150

### Data Model
​
(5 points total.)
​
### User Flows
​
#### Viewing ideas
​
(5 points total.)
​
* missing truncation
​
#### Adding a new idea
​
(15 points total.)
​
#### Deleting an existing idea
​
(15 points total.)
​
#### Changing the quality of an idea
​
(15 points total.)
​
#### Editing an existing idea
​
(20 points total.)
​
#### Idea Filtering and Searching
​
(15 points total.)
​
### Extensions
​
Extensions are a great way to earn additional points beyond the 150 available in this project. That said, awarding points for delivering a given extension is up to the instructor, who may only award partial points depending on the quality of the implementation. The points listed below represent the maximum number of points. Extensions can _not_ be done after the fact without instructor permission in advance.
​
#### Sorting
​
(10 additional points.)
​
When viewing the ideas list, the user should have the option to sort ideas by Quality. The default sort should be descending ("genius" → "plausible" → "swill"), and clicking the sort a second time should reverse it. The Idea list should be sorted client-side without reloading the page.
​
#### Student Directed Extension
​
(10 additional points.)
​
Student chooses an additional feature or performance optimization to add to the project. The extension must be intuitive and should not detract from the user's experience in any major way (i.e. not buggy or incomplete).
​
## Instructor Evaluation Points
​
### Specification Adherence
​
* **10 points**: The application consists of one page with all of the major functionality being provided by jQuery. There is no use of `format.js` in Rails. There is no use of unobstrusive JavaScript. There are no front-end frameworks used in the application. No approach was taken that is counter to the spirit of the project and its learning goals. There are no features missing from above that make the application feel incomplete or hard to use.
​
### User Interface
​
* **5 points** - The application is pleasant, logical, and easy to use. There no holes in functionality and the application stands on it own to be used by the instructor _without_ guidance from the developer.
​
### Testing
​
* **7 points** - Project has a running test suite that tests and multiple levels but fails to cover some features. All controller actions are covered by tests. The application makes some use of integration testing.

​
### Ruby and Rails Quality
​
* **10 points** - Developer is able to craft Rails features that make smart use of Ruby, follow the principles of MVC, and push business logic down where it belongs. There _zero_ instances where an instructor would recommend taking a different approach. Developer writes code that is exceptionally clear and well-factored. Application is expertly divided into logical components each with a clear, single responsibility.
​
### JavaScript Style
​
* **8 points** - Application is thoughtfully put together with some duplication and no major bugs. Developer can speak to choices made in the code and knows what every line of code is doing.
​
### Workflow
​
* **10 points** - The developer effectively uses Git branches and many small, atomic commits that document the evolution of their application.
