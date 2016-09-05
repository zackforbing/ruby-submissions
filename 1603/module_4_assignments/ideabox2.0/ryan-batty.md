# Ideabox 2.0 Submission Form
[Project Spec](https://github.com/turingschool/curriculum/blob/master/source/projects/revenge_of_idea_box.markdown)

------

# Basics

[Idea Box - Repo](https://github.com/Riizu/idea_box)

[Idea Box - Heroku](https://boiling-dawn-58829.herokuapp.com/)

[Idea Box - Commits](https://github.com/Riizu/idea_box/commits/master)

### Screenshot
![idea_box](http://i.imgur.com/cMG3dp8.png)

## Completion

### Were you able to complete the base functionality?
* The only missing requirement was truncation of idea bodies.

### Extensions
* N/A - No extensions were completed

# Code Quality

### Proud Moment: [Idea Quality Change](https://github.com/Riizu/idea_box/blob/master/app/models/idea.rb)
* I like this piece of code because I felt it was a very robust solution to handling upvoting/downvoting with enums. It allows for easy extendability and additional requirements.

### Weak Moment: [generateIdeaHtml function](https://github.com/Riizu/idea_box/blob/master/app/assets/javascripts/idea.js)
* While simple, I feel like this method is needlessly long. It seems like it could be shortened in some manner with dynamic generation of tags, but adding that seemed to go against the KISS principle.

### Test Suite: [Rails/Teaspoon Album](http://imgur.com/a/XsmDU)

### Sad Path Test: [Search Spec Failure](https://github.com/Riizu/idea_box/blob/master/spec/features/visitor_can_search_ideas_spec.rb)

-----

### Thoughts:
> Overall, I feel this was a successful project. While I wish I had been able to get extensions, as I definitely feel capable of completing them, the First Week slowness was definitely in effect, and motivation ended up being a challenge. I also think that the idea (hah puns) of the project itself was hard to get excited about, but thats okay - thats a common thing in real life.

## Rubric

### Data Model

(5 points total.)

### User Flows

#### Viewing ideas

(10 points total.)

* Idea bodies longer than 100 characters should be truncated to the nearest word. (5 points)

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

* **4 points** - The application has many strong pages/interactions, but a few holes in lesser-used functionality.

### Testing

* **10 points** - Project has a running test suite that exercises the application at multiple levels including JavaScript tests.

### Ruby and Rails Quality

* **8 points** - Developer solves problems with a balance between conciseness and clarity and often extracts logical components. Developer can speak to choices made in the code and knows what every line of code is doing.

### JavaScript Style

* **8 points** - Application is thoughtfully put together with some duplication and no major bugs. Developer can speak to choices made in the code and knows what every line of code is doing.

### Workflow

* **10 points** - The developer effectively uses Git branches and many small, atomic commits that document the evolution of their application.
