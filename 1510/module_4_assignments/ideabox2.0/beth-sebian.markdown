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
[Revenge of Idea Box](https://github.com/bethsebian/revenge_of_idea_box)

### Link to the Deployed Application
[Revenge of Idea Box](https://stark-lake-86720.herokuapp.com/)

### Link to Your Commits in the Github Repository for the Project
[My Commits](https://github.com/bethsebian/revenge_of_idea_box/commits/master)

### Provide a Screenshot of your Application
![ideabox](images/beth_sebian_screenshot.png)


## Completion

### Were you able to complete the base functionality?
Nope.  
* Filter and Search is missing
* testing completely absent

### Which extensions, if any, did you complete?
None  

### Attach a .gif, or images of any extensions work being used on the site.

# Code Quality

### Link to a specific block of your code on Github that you are proud of
[Model methods](https://github.com/bethsebian/revenge_of_idea_box/blob/master/app/models/idea.rb)
I was pleased to have a chance to move some of these methods to the model.

### Link to a specific block of your code on Github that you feel not great about
[ideas.js file](https://github.com/bethsebian/revenge_of_idea_box/blob/master/app/assets/javascripts/ideas.js)
* This seems like a mess.
* Different approaches to do the same thing (add new element waits for trigger in a different way than other functions)

### Attach a screenshot or paste the output from your terminal of the result of your test-suite running.
n/a. face-palm.  

### Provide a link to an example, if you have one, of a test that covers an 'edge case' or 'unhappy path'

-----

### Please feel free to ask any other questions or make any other statements below!
Some weird page reloads going on. My Ajax updates content without the page reload, but a reload is triggered somehow after that (see add new and update).

----
# Instructor Feedback

128/150

### Data Model

(5 points total.)

### User Flows

#### Viewing ideas

(5 points total.)

No truncation

#### Adding a new idea

(15 points total.)s

#### Deleting an existing idea

(15 points total.)

#### Changing the quality of an idea

(15 points total.)

#### Editing an existing idea

(20 points total.)

#### Idea Filtering and Searching

(0/15)

## Instructor Evaluation Points

### Specification Adherence

* **10 points**: The application consists of one page with all of the major functionality being provided by jQuery. There is no use of `format.js` in Rails. There is no use of unobstrusive JavaScript. There are no front-end frameworks used in the application. No approach was taken that is counter to the spirit of the project and its learning goals. There are no features missing from above that make the application feel incomplete or hard to use.

### User Interface

* **5 points** - The application is pleasant, logical, and easy to use. There no holes in functionality and the application stands on it own to be used by the instructor _without_ guidance from the developer.

### Testing

* **0 points** - There is little or no evidence of testing in this application.

### Ruby and Rails Quality

* **10 points** - Developer is able to craft Rails features that make smart use of Ruby, follow the principles of MVC, and push business logic down where it belongs. There _zero_ instances where an instructor would recommend taking a different approach. Developer writes code that is exceptionally clear and well-factored. Application is expertly divided into logical components each with a clear, single responsibility.

### JavaScript Style

* **8 points** - Application is thoughtfully put together with some duplication and no major bugs. Developer can speak to choices made in the code and knows what every line of code is doing.


### Workflow

* **10 points** - The developer effectively uses Git branches and many small, atomic commits that document the evolution of their application.
