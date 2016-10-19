# Ideabox 2.0 Submission Form- Nick Pisciotta

[Project Spec](https://github.com/turingschool/curriculum/blob/master/source/projects/revenge_of_idea_box.markdown)

------
# Basics

### Link to the Github Repository for the Project
[GitHub Repo](https://github.com/nickpisciotta/idea_box)

### Link to the Deployed Application
[App Website](http://thebigidea.herokuapp.com/)

### Link to Your Commits in the Github Repository for the Project
[Your Commits](https://github.com/nickpisciotta/idea_box/commits/master)

### Provide a Screenshot of your Application
![The Big Idea](http://www.openscreenshot.com/img/57b60e961a46c6-70492952)

## Completion

### Were you able to complete the base functionality?
* Yes

### Which extensions, if any, did you complete?
* No

### Attach a .gif, or images of any extensions work being used on the site.

# Code Quality

### Link to a specific block of your code on Github that you are proud of
[Code Link](https://github.com/nickpisciotta/idea_box/blob/master/app/assets/javascripts/filter.js)


Why were you proud of this piece of code?
* The search feature was a feature that I found particularly difficult since I was using a table and had to search by two table cell elements. While this function could use some refactoring, I felt proud to accomplish searching on this element type.

### Link to a specific block of your code on Github that you feel not great about

[Code Link](https://github.com/nickpisciotta/idea_box/blob/master/app/assets/javascripts/services.js#L1-L25)

Why do you feel not awesome about the code? What challenges did you face trying to write/refactor it?
* I would have preferred to use a different technique to append new information.  Storing this data to a JavaScript object and iterating over these objects while building them to the DOM would have been a technique worth trying.  Therefore I wouldn't have to just rely on the DOM for the "true" information.

### Attach a screenshot or paste the output from your terminal of the result of your test-suite running.
![Test Suite](http://imgur.com/a/0Arcw)
### Provide a link to an example, if you have one, of a test that covers an 'edge case' or 'unhappy path'

-----

## Rubric

### Data Model

(5 points total.)

### User Flows

#### Viewing ideas

(10 points total.)

* Idea bodies longer than 100 characters should be truncated to the nearest word. (2.5 points)
* Ideas should appear in descending chronological order (with the most recently created
  idea at the top). (3 points)


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

* **9 points** - Project has a running test suite that tests and multiple levels but fails to cover some features. All controller actions are covered by tests. The application makes some use of integration testing.

### Ruby and Rails Quality

* **10 points** - Developer is able to craft Rails features that make smart use of Ruby, follow the principles of MVC, and push business logic down where it belongs. There _zero_ instances where an instructor would recommend taking a different approach. Developer writes code that is exceptionally clear and well-factored. Application is expertly divided into logical components each with a clear, single responsibility.

### JavaScript Style

* **8 points** - Application is thoughtfully put together with some duplication and no major bugs. Developer can speak to choices made in the code and knows what every line of code is doing.

### Workflow

* **10 points** - The developer effectively uses Git branches and many small, atomic commits that document the evolution of their application.
