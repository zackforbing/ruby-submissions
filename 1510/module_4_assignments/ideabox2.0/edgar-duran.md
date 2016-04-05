# Basics

### Link to the Github Repository for the Project
[My Repo](https://github.com/edgarduran/ideabox-2.0)

### Link to the Deployed Application
[My Application](http://edgars-ideabox.herokuapp.com/)

### Link to My Commits in the Github Repository for the Project
[My Commits](https://github.com/edgarduran/ideabox-2.0/commits/master)

### Provide a Screenshot of your Application
![Idea Box](http://i.imgur.com/U0XYMMv.png)![](http://i.imgur.com/nog1jKi.png)

## Completion

### Were you able to complete the base functionality?
* Yas!!

### Which extensions, if any, did you complete?
None

### Attach a .gif, or images of any extensions work being used on the site.
N/A

# Code Quality

### Link to a specific block of your code on Github that you are proud of
[Proud of](https://github.com/edgarduran/ideabox-2.0/blob/master/app/assets/javascripts/ideaEdit.js#L37-L40)

* Why were you proud of this piece of code?
I figured out an efficient way to hide the current idea while showing the editing form over it.

### Link to a specific block of your code on Github that you feel not great about
[Not proud](https://github.com/edgarduran/ideabox-2.0/blob/master/app/assets/javascripts/ideas.js#L6-L48)
* Why do you feel not awesome about the code? What challenges did you face trying to write/refactor it?
I feel like these two methods do the same thing with the exception of where they interpolate the html. I bet I could have refactored into one method with a conditional at least. Plus interploating a huge dive in the method also is excesive. I should have pulled that variable out. The biggest challenge was time.

### Attach a screenshot or paste the output from your terminal of the result of your test-suite running.
![Test Suite](http://i.imgur.com/qAw6SUU.png)

### Provide a link to an example, if you have one, of a test that covers an 'edge case' or 'unhappy path'

-----

# Instructor Feedback

### Data Model

(5 points total.)

### User Flows

#### Viewing ideas

(10 points total.)

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

* **3 points** - The application has many strong pages/interactions, but a few holes in lesser-used functionality.

### Testing

* **5 points** - Project has sporadic use of tests and multiple levels. Not all controller actions are tested. There are little or no attempts at integration testing.

### Ruby and Rails Quality

* **10 points** - Developer is able to craft Rails features that make smart use of Ruby, follow the principles of MVC, and push business logic down where it belongs. There _zero_ instances where an instructor would recommend taking a different approach. Developer writes code that is exceptionally clear and well-factored. Application is expertly divided into logical components each with a clear, single responsibility.

### JavaScript Style

* **8 points** - Application is thoughtfully put together with some duplication and no major bugs. Developer can speak to choices made in the code and knows what every line of code is doing.

### Workflow

* **10 points** - The developer effectively uses Git branches and many small, atomic commits that document the evolution of their application.
