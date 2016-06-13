# Ideabox 2.0 Submission Form
[Project Spec](https://github.com/turingschool/curriculum/blob/master/source/projects/revenge_of_idea_box.markdown)

# Basics

[Repository](https://github.com/amaxwellblair/idea_box)

[Deployed Application](https://glacial-river-31267.herokuapp.com/)

[Commit History](https://github.com/amaxwellblair/idea_box/commits/master)


![idea-box](images/amb-idea-box.png)

## Completion

### Were you able to complete the base functionality?
* All but body truncation

### Which extensions, if any, did you complete?
* None

# Code Quality

### Link to a specific block of your code on Github that you are proud of
* Not particularly proud of code quality. I used a majority of pure javascript versus jQuery which made me happy.
* Also tried to have restful-ish requests of ideas
  * [See create and update idea](https://github.com/amaxwellblair/idea_box/blob/master/app/assets/javascripts/dashboardIndex.js#L45)

### Link to a specific block of your code on Github that you feel not great about
* Most of the code isn't fantastic. Felt poorly about it due to the lack of organization and DRY fundamentals
* I would have liked to refactor this project by pulling out html generators, ajax calls, and other items to specific directories
  * [Not DRY](https://github.com/amaxwellblair/idea_box/blob/master/app/assets/javascripts/dashboardIndex.js#L77)
  * [Could be moved to separate file](https://github.com/amaxwellblair/idea_box/blob/master/app/assets/javascripts/dashboardIndex.js#L181)

# Instructor Feedback

110/150

### Data Model

(5 points total.)

### User Flows

#### Viewing ideas

(2 points total.)

missing truncation & descending order

#### Adding a new idea

(15 points total.)

#### Deleting an existing idea

(15 points total.)

#### Changing the quality of an idea

(15 points total.)

#### Editing an existing idea

(0 points total.)

Not working in production

Issue relates to splitting on a 'dash' which is present earlier in the url in heroku and not locally: https://github.com/amaxwellblair/idea_box/blob/master/app/assets/javascripts/dashboardIndex.js#L62

Could be fixed with a data attribute or a regex matcher (or grabbing the last dash, etc).

#### Idea Filtering and Searching

(15 points total.)

## Instructor Evaluation Points

### Specification Adherence

* **10 points**

### User Interface

* **3 points** - The application has many strong pages/interactions, but a few holes in lesser-used functionality.

### Testing

* **5 points** - Project has sporadic use of tests and multiple levels. Not all controller actions are tested. There are little or no attempts at integration testing.

### Ruby and Rails Quality

* **10 points** - Developer is able to craft Rails features that make smart use of Ruby, follow the principles of MVC, and push business logic down where it belongs. There _zero_ instances where an instructor would recommend taking a different approach. Developer writes code that is exceptionally clear and well-factored. Application is expertly divided into logical components each with a clear, single responsibility.

### JavaScript Style

* **5 points** - Your application has some duplication and minor bugs. Developer can speak to most choices made in the code and knows what every line is doing.

### Workflow

* **10 points** - The developer effectively uses Git branches and many small, atomic commits that document the evolution of their application.
