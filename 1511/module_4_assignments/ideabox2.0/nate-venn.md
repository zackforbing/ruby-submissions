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
[Your Repo](https://github.com/natevenn/ideabox)

### Link to the Deployed Application
[Your Application](http://idea-boxx.herokuapp.com/)

### Link to Your Commits in the Github Repository for the Project
[Your Commits](https://github.com/natevenn/ideabox/commits/master)

### Provide a Screenshot of your Application
![ideabox](<img width="552" alt="ideabox" src="https://cloud.githubusercontent.com/assets/8459012/15279070/d168a716-1add-11e6-8ff2-476f3c926279.png">)

## Completion

### Were you able to complete the base functionality?
Yes

### Which extensions, if any, did you complete?
None

### Attach a .gif, or images of any extensions work being used on the site.
no extensions

# Code Quality

### Link to a specific block of your code on Github that you are proud of
[proud code](https://github.com/natevenn/ideabox/blob/master/app/assets/javascripts/ideas.js#L40)
I am proud of this code because it was a simple solution for keeping the
database stored value of the quality separate from the string version of quality
on the client side. I can do all the math on the client side and just send the
new integer value to the database and quickly change the string value of quality
on the client side by using a JS object.

### Link to a specific block of your code on Github that you feel not great about
[not proud code](https://github.com/natevenn/ideabox/blob/master/app/assets/javascripts/ideas.js#L42-L58)
I dont feel great about this code because it feels complex and about half of it
is static. Some of it could probably live in html form in the view and it could
really clean up the code.

### Attach a screenshot or paste the output from your terminal of the result of your test-suite running.
[tests](<img width="704" alt="idea-box-testing" src="https://cloud.githubusercontent.com/assets/8459012/15279119/50622dda-1ade-11e6-97b7-68d83ff9869c.png">)

### Provide a link to an example, if you have one, of a test that covers an 'edge case' or 'unhappy path'
[edge case](https://github.com/natevenn/ideabox/blob/master/spec/javascripts/change_quality_spec.js#L25-L30)


### Please feel free to ask any other questions or make any other statements below!

# Instructor Feedback

140/150

### Data Model

(5 points total.)

### User Flows

#### Viewing ideas

(9 points total.)

#### Adding a new idea

(15 points total.)

#### Deleting an existing idea

(15 points total.)

#### Changing the quality of an idea

(15 points total.)

#### Editing an existing idea

(20 points total.)

#### Idea Filtering and Searching

(11 points total.)

### Instructor Evaluation Points

#### Specification Adherence

10 points: The application consists of one page with all of the major functionality being provided by jQuery. There is no use of format.js in Rails. There is no use of unobstrusive JavaScript. There are no front-end frameworks used in the application. No approach was taken that is counter to the spirit of the project and its learning goals. There are no features missing from above that make the application feel incomplete or hard to use.

#### User Interface

5 points - The application is pleasant, logical, and easy to use. There no holes in functionality and the application stands on it own to be used by the instructor without guidance from the developer.

#### Testing

9 points - Project has a running test suite that tests and multiple levels but fails to cover some features. All controller actions are covered by tests. The application makes some use of integration testing.

#### Ruby and Rails Quality

8 points - Developer solves problems with a balance between conciseness and clarity and often extracts logical components. Developer can speak to choices made in the code and knows what every line of code is doing.

#### JavaScript Style

8 points - Application is thoughtfully put together with some duplication and no major bugs. Developer can speak to choices made in the code and knows what every line of code is doing.

#### Workflow

10 points - The developer effectively uses Git branches and many small, atomic commits that document the evolution of their application.
