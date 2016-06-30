


#Jeneve Parrish ---  Ideabox 2.0 _Submission Form_
[Project Spec](https://github.com/turingschool/curriculum/blob/master/source/projects/revenge_of_idea_box.markdown)
------

# Basics

### Link to the Github Repository for the Project
[Jeneve's Idea Box Repo](https://github.com/jeneve/idea-box)

### Link to the Deployed Application
[jeneve-has-ideas.herokuapp.com](https://jeneve-has-ideas.herokuapp.com/)

### Link to Commits in the Github Repository for the Project
[Jeneve's Commits](https://github.com/jeneve/idea-box/commits/master)

### Provide a Screenshot of your Application
![idea-box](http://g.recordit.co/XzyNuujtMP.gif)

## Completion

### Were you able to complete the base functionality?
 **If not, list what functionality is missing?**

- ##### (spec)Ideas should appear in descending chronological order (with the most recently created idea at the top). (3 points)

	_mine shows the most recently updated on top upon page reload._

- ##### (spec)Incrementing a "genius" idea or decrementing a "swill" idea should have no effect. (4 points)

	_mine shows a retro alert letting you know why nothing happened_

### Which extensions, if any, did you complete?
####(_none_)
 
### Attach a .gif, or images of any extensions work being used on the site.
####(_N/A_)
# Code Quality

### Link to a specific block of your code on Github that you are proud of

 **Why were you proud of this piece of code?**

#####I wrote a request without ajax after many hours of debugging an ajax request, [here.](https://github.com/jeneve/idea-box/blob/master/app/assets/javascripts/functions.js#L7) Not proud that I could never debug the problem with the ajax request, but proud that I was able to get past it.

### Link to a specific block of your code on Github that you feel not great about
**Why do you feel not awesome about the code? What challenges did you face trying to write/refactor it?**

#####in the time I had, it was the best I could do to separate listeners from functions into two files. There is still SO much repetition and so many oppurtunities for refactoring the javascript. The two very similar methods beginning on the linked line number below is an example of the problem.[ here.](https://github.com/jeneve/idea-box/blob/master/app/assets/javascripts/functions.js#L65)

### Attach a screenshot or paste the output from your terminal of the result of your test-suite running.

![rspec-sceenshot](https://github.com/jeneve/idea-box/blob/master/app/assets/images/rspec-screenshot.png?raw=true)

### Provide a link to an example, if you have one, of a test that covers an 'edge case' or 'unhappy path'
####(_N/A_)
-----

### Please feel free to ask any other questions or make any other statements below!


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
* **5 points** - The application is pleasant, logical, and easy to use. There no holes in functionality and the application stands on it own to be used by the instructor _without_ guidance from the developer.
​
### Testing
​
* **10 points** - Project has a running test suite that exercises the application at multiple levels including JavaScript tests.

### Ruby and Rails Quality
​
* **9 points** 
​
### JavaScript Style
​
* **8 points** - Application is thoughtfully put together with some duplication and no major bugs. Developer can speak to choices made in the code and knows what every line of code is doing.
​

### Workflow

* **10 points** - The developer effectively uses Git branches and many small, atomic commits that document the evolution of their application.
* 
### Total Points: 147/150
