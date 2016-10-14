# Ideabox 2.0 Submission Form
[Project Spec](https://github.com/turingschool/curriculum/blob/master/source/projects/revenge_of_idea_box.markdown)

* Fork this repo, if you haven't already and check out a branch
* Use this README as a template to create a file in this folder with your name as the title.
* Submit a pull request
* Pro Tip: You can use [recordit.co](http://recordit.co/) to record interaction gifs.
* Secondary Pro Tip: [Here's how to link to specific line number(s) in Github](http://stackoverflow.com/questions/23821235/how-to-link-to-specific-line-number-on-github)
* Tertiary Pro Tip: You can re-use some of these things in your portfolio/resume

------

# Basics

### Link to the Github Repository for the Project
[Your Repo](https://github.com/karinamzalez/idea_box)

### Link to the Deployed Application
[Idea Circle](https://idea-circle.herokuapp.com/)

### Link to Your Commits in the Github Repository for the Project
[My Commits](https://github.com/karinamzalez/idea_box/commits/master)

### Provide a Screenshot of your Application
![idea-circle](/images/circle.png)

## Completion

### Were you able to complete the base functionality?
* Idea Filtering and Searching

### Which extensions, if any, did you complete?

### Attach a .gif, or images of any extensions work being used on the site.

# Code Quality

### Link to a specific block of your code on Github that you are proud of
* https://github.com/karinamzalez/idea_box/blob/master/app/assets/javascripts/delete_lesson.js.es6
* Why were you proud of this piece of code?
* because it was my simplest ajax call

### Link to a specific block of your code on Github that you feel not great about
* https://github.com/karinamzalez/idea_box/blob/master/app/assets/javascripts/edit_lesson.js.es6
* Why do you feel not awesome about the code? What challenges did you face trying to write/refactor it?
* because it's repetative-- not fully functional

### Attach a screenshot or paste the output from your terminal of the result of your test-suite running.
![idea-circle](/images/test.png)

### Provide a link to an example, if you have one, of a test that covers an 'edge case' or 'unhappy path'

-----

### Please feel free to ask any other questions or make any other statements below!


### Data Model

(5 points total.)

### User Flows

#### Viewing ideas

(8/10 points total.)

On the application's root, the user should:

* Idea bodies longer than 100 characters should be truncated to the nearest word. (3/5 points)

#### Adding a new idea

(15 points total.)

#### Deleting an existing idea

(15 points total.)

#### Changing the quality of an idea

(15 points total.)

#### Editing an existing idea

(18/20 points total.)

* If the user reloads the page, their edits will be reflected. (2/4 points, mandatory for specification adherence)

#### Idea Filtering and Searching

(15 points total.)

We'd like our users to be able to easily find specific ideas they already created, so
let's provide them with a filtering interface on the idea list.

* At the top of the idea list, include a text field labeled "Search". (3 points)
* As a user types in the search box, the list of ideas should filter in real time to only display ideas whose title or body include the user's text. The page _should not_ reload. (6 points)
* Clearing the search box should restore all the ideas to the list. (6 points)

## Instructor Evaluation Points

### Specification Adherence

* **0/10 points**: The application consists of one page with all of the major functionality being provided by jQuery. There is no use of `format.js` in Rails. There is no use of unobtrusive JavaScript. There are no front-end frameworks used in the application. No approach was taken that is counter to the spirit of the project and its learning goals. There are no features missing from above that make the application feel incomplete or hard to use.

### User Interface

* **3 points** - The application has many strong pages/interactions, but a few holes in lesser-used functionality.

### Testing

* **6 points** - Project has sporadic use of tests and multiple levels. Not all controller actions are tested. There are little or no attempts at integration testing.

### Ruby and Rails Quality

* **8 points** - Developer solves problems with a balance between conciseness and clarity and often extracts logical components. Developer can speak to choices made in the code and knows what every line of code is doing.

### JavaScript Style

* **8 points** - Application is thoughtfully put together with some duplication and no major bugs. Developer can speak to choices made in the code and knows what every line of code is doing.

### Workflow

* **10 points** - The developer effectively uses Git branches and many small, atomic commits that document the evolution of their application.
