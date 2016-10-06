# Ideabox 2.0 Submission Form
[Project Spec](https://github.com/turingschool/curriculum/blob/master/source/projects/revenge_of_idea_box.markdown)
------

# Basics

### Link to the Github Repository for the Project
[Your Repo](https://github.com/patrickwhardy/idea_box)

### Link to the Deployed Application
[Your Application](https://warm-tor-16277.herokuapp.com/)

### Link to Your Commits in the Github Repository for the Project
[Your Commits](https://github.com/patrickwhardy/idea_box/commits/master)

### Provide a Screenshot of your Application
![Ideabox Gif](http://recordit.co/XYSMrOeAnU.gif)

## Completion

### Were you able to complete the base functionality?
* Yes

### Which extensions, if any, did you complete?
* None

### Attach a .gif, or images of any extensions work being used on the site.
* Attached above
# Code Quality

### Link to a specific block of your code on Github that you are proud of
[Internal Api](https://github.com/patrickwhardy/idea_box/blob/master/app/controllers/api/v1/ideas_controller.rb)

* Why were you proud of this piece of code?
* Line 16 - Despite doing so much rails I was suprised to realized that updates are not set up to return data and was proud to figure out the work-around of stating json: @idea to make the app work as planned.

### Link to a specific block of your code on Github that you feel not great about
[Search Feature](https://github.com/patrickwhardy/idea_box/blob/master/app/assets/javascripts/ideas.js)

* Why do you feel not awesome about the code? What challenges did you face trying to write/refactor it?
* (Line 69) - This felt really hacky. I tried writing this block with .match and just could not get it to return true. I'm using .search when it is really meant for finding the index of chars. I also know that the search will also return matching html tags which is definitely not ideal.

### Attach a screenshot or paste the output from your terminal of the result of your test-suite running.

Patricks-MacBook-Pro-2:idea_box patrickwhardy$ rake test
Run options: --seed 60669

# Running:

..............

Fabulous run in 5.262109s, 2.6605 runs/s, 5.1310 assertions/s.

14 runs, 27 assertions, 0 failures, 0 errors, 0 skips
Patricks-MacBook-Pro-2:idea_box patrickwhardy$

### Provide a link to an example, if you have one, of a test that covers an 'edge case' or 'unhappy path'

[Idea Test](https://github.com/patrickwhardy/idea_box/blob/master/test/models/idea_test.rb)

* This refutes saving an idea with invalid attributes.

-----

### Please feel free to ask any other questions or make any other statements below!

# Instructor feedback

144/150

### Data Model
​
(5 points total.)
​
### User Flows
​
#### Viewing ideas
​
(10 points total.)
​
#### Adding a new idea
​
(15 points total.)
​
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
## Instructor Evaluation Points
​
### Specification Adherence
​
* **10 points**: The application consists of one page with all of the major functionality being provided by jQuery. There is no use of `format.js` in Rails. There is no use of unobstrusive JavaScript. There are no front-end frameworks used in the application. No approach was taken that is counter to the spirit of the project and its learning goals. There are no features missing from above that make the application feel incomplete or hard to use.
​
### User Interface
​
* **3 points** - The application has many strong pages/interactions, but a few holes in lesser-used functionality.

### Testing
​
* **8 points** - Project has a running test suite that tests and multiple levels but fails to cover some features. All controller actions are covered by tests. The application makes some use of integration testing.
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
