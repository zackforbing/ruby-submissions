# Basics

### [Boxes of Ideas Repo](http://github.com/JaredRoth/idea-box)

### [Boxes of Ideas App](http://boxes-of-ideas.herokuapp.com/)

### [Commits](https://github.com/JaredRoth/idea-box/commits/master)

![Boxes of Ideas](images/jared-roth-screenshot.png)

## Completion

### All base functionality is complete

### No extensions

# Code Quality

### [DRY'd up the thumb up/down into one method](https://github.com/JaredRoth/idea-box/blob/770257083d67ccdb0d053dc132b4e61e5e752c03/app/assets/javascripts/idea_box.js#L56-L68)
* Was able to specify the direction of the vote and then have the method handle it appropriately.

### [Feels too large](https://github.com/JaredRoth/idea-box/blob/770257083d67ccdb0d053dc132b4e61e5e752c03/app/assets/javascripts/idea_box.js#L70-L90)
* Besides the fact that everything just lives in one file, there's a lot going on in this method and I wasn't sure how to break it up better.

![Boxes of Ideas](images/jared-roth-test-output.png)

### [Tests what happens when an idea quality cannot be raised past Genius or lowerd past Swill](https://github.com/JaredRoth/idea-box/blob/master/spec/features/user_can_alter_idea_quality_spec.rb)

### Data Model

(5 points total.)

### User Flows

#### Viewing ideas

(5 points total.)

#### Adding a new idea

(15 points total.)

#### Deleting an existing idea

(15 points total.)

#### Changing the quality of an idea

(15 points total.)

#### Editing an existing idea

(20 points total.)

#### Idea Filtering and Searching

(15 points) -- Originally 7, developer fixed search functionality


## Instructor Evaluation Points

### Specification Adherence

* **10 points**: The application consists of one page with all of the major functionality being provided by jQuery. There is no use of `format.js` in Rails. There is no use of unobstrusive JavaScript. There are no front-end frameworks used in the application. No approach was taken that is counter to the spirit of the project and its learning goals. There are no features missing from above that make the application feel incomplete or hard to use.

### User Interface

* **5 points** - The application is pleasant, logical, and easy to use. There no holes in functionality and the application stands on it own to be used by the instructor _without_ guidance from the developer.

### Testing

* **8 points** - Project has a running test suite that tests and multiple levels but fails to cover some features. All controller actions are covered by tests. The application makes some use of integration testing.

### Ruby and Rails Quality

* **10 points** - Developer is able to craft Rails features that make smart use of Ruby, follow the principles of MVC, and push business logic down where it belongs. There _zero_ instances where an instructor would recommend taking a different approach. Developer writes code that is exceptionally clear and well-factored. Application is expertly divided into logical components each with a clear, single responsibility.

### JavaScript Style

* **8 points** - Application is thoughtfully put together with some duplication and no major bugs. Developer can speak to choices made in the code and knows what every line of code is doing.

### Workflow

* **10 points** - The developer effectively uses Git branches and many small, atomic commits that document the evolution of their application.


### Total Score: 141/150
