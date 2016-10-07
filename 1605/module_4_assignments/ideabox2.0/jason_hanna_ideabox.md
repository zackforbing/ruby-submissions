# Basics

### Idea Box 2.0
[GitHub Repo](https://github.com/Automatic365/idea-box-2.0)

### Idea Box on Heroku
[Idea Box on Heroku](https://idea-box-2-the-reckoning.herokuapp.com/)

### Link to My Commits in the Github Repository for the Project
[My Commits](https://github.com/Automatic365/idea-box-2.0/commits/master)

### Provide a Screenshot of your Application
![Project Screenshot](http://oi68.tinypic.com/209lelx.jpg)

## Completion

### Were you able to complete the base functionality?
* No. I don't have filtered searching.

### Which extensions, if any, did you complete?
* None

# Code Quality

### Link to a specific block of your code on Github that you are proud of

[Code Pride](https://github.com/Automatic365/idea-box-2.0/blob/ced1056b96fcbef38cb59a8607b7509f6720ad43/app/assets/javascripts/create_idea.js)
* It took me forever to understand the basics of what I was trying to do. Once I got this to work, my fuzzy understanding was enough to move forward with.

### Link to a specific block of your code on Github that you feel not great about

[Code Shame](https://github.com/Automatic365/idea-box-2.0)
* I'm still a little intimidated by JS and working my way through thinking through it more succinctly. I know that is to be expected in the first week, but I still feel shaky about the relationship JavaScript and I are developing.

### Attach a screenshot or paste the output from your terminal of the result of your test-suite running.

Finished in 2.61 seconds (files took 17.16 seconds to load)
10 examples, 0 failures

### Provide a link to an example, if you have one, of a test that covers an 'edge case' or 'unhappy path'

### Data Model

(5 points total.)


### User Flows

#### Viewing ideas

(5/10 points total.)

* Idea bodies longer than 100 characters should be truncated to the nearest word. (5 points)


#### Adding a new idea

(12/15 points total.)

* The page _should not_ reload. (3 points, mandatory for specification adherence)


#### Deleting an existing idea

(15 points total.)

#### Changing the quality of an idea

(15 points total.)

#### Editing an existing idea

(20 points total.)

#### Idea Filtering and Searching

(0/15 points total.)

We'd like our users to be able to easily find specific ideas they already created, so
let's provide them with a filtering interface on the idea list.

* At the top of the idea list, include a text field labeled "Search". (3 points)
* As a user types in the search box, the list of ideas should filter in real time to only display ideas whose title or body include the user's text. The page _should not_ reload. (6 points)
* Clearing the search box should restore all the ideas to the list. (6 points)

## Instructor Evaluation Points

### Specification Adherence

* **8 points**: A bug in how things get submitted

### User Interface


* **3 points** - The application has many strong pages/interactions, but a few holes in lesser-used functionality.


### Testing

* **7 points** - Project has sporadic use of tests and multiple levels. Not all controller actions are tested. There are little or no attempts at integration testing.

### Ruby and Rails Quality

* **10 points** - Developer is able to craft Rails features that make smart use of Ruby, follow the principles of MVC, and push business logic down where it belongs. There _zero_ instances where an instructor would recommend taking a different approach. Developer writes code that is exceptionally clear and well-factored. Application is expertly divided into logical components each with a clear, single responsibility.

### JavaScript Style

* **8 points** - Application is thoughtfully put together with some duplication and no major bugs. Developer can speak to choices made in the code and knows what every line of code is doing.

### Workflow

* **10 points** - The developer effectively uses Git branches and many small, atomic commits that document the evolution of their application.
