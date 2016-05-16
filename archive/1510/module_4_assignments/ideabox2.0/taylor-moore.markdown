# Basics

### Link to the Github Repository for the Project
[My Repo](https://github.com/Tman22/idea_box)

### Link to the Deployed Application
[My Application](http://still-meadow-55967.herokuapp.com/)

### Link to My Commits in the Github Repository for the Project
[My Commits](https://github.com/Tman22/idea_box/commits/master)

### Provide a Screenshot of your Application
![Not Space Jam](http://g.recordit.co/PeULDeyBjG.gif)

## Completion

### Were you able to complete the base functionality?
Yes except for truncating. I have a method that's very close, didn't the edit
to show the entire body.

### Which extensions, if any, did you complete?
Partial in-line editing and sort.

# Code Quality

### Link to a specific block of your code on Github that you are proud of
[Proud of?](https://github.com/Tman22/idea_box/blob/master/app/assets/javascripts/sort.js#L1-L14)
From what little I know of javascript


### Link to a specific block of your code on Github that you feel not great about
[Not so great](https://github.com/Tman22/idea_box/blob/master/app/assets/javascripts/edit.js#L12-L34)

### Attach a screenshot or paste the output from your terminal of the result of your test-suite running.
![](http://i.imgur.com/3Xl5nxK.png)
### Provide a link to an example, if you have one, of a test that covers an 'edge case' or 'unhappy path'

# Instructor Feedback

118 / 150

### Data Model

(5 points total.)

### User Flows

#### Viewing ideas

(7 points total.)

* MISSING: Ideas should appear in descending chronological order (with the most recently created
  idea at the top). (3 points)

#### Adding a new idea

(15 points total.)

#### Deleting an existing idea

(15 points total.)

#### Changing the quality of an idea

(15 points total.)

#### Editing an existing idea

(16 points total.)

* MISSING: After clicking on the edit link, the user should see form fields to modify the idea's title and body. (4 points)

#### Idea Filtering and Searching

(3 points total.)

We'd like our users to be able to easily find specific ideas they already created, so
let's provide them with a filtering interface on the idea list.

* MISSING: As a user types in the search box, the list of ideas should filter in real time to only display ideas whose title or body include the user's text. The page _should not_ reload. (6 points)
* MISSING: Clearing the search box should restore all the ideas to the list. (6 points)

## Instructor Evaluation Points

### Specification Adherence

* **10 points**: The application consists of one page with all of the major functionality being provided by jQuery. There is no use of `format.js` in Rails. There is no use of unobstrusive JavaScript. There are no front-end frameworks used in the application. No approach was taken that is counter to the spirit of the project and its learning goals. There are no features missing from above that make the application feel incomplete or hard to use.

### User Interface

* **3 points** - The application has many strong pages/interactions, but a few holes in lesser-used functionality.

### Testing

* **8 points** - Project has a running test suite that tests and multiple levels but fails to cover some features. All controller actions are covered by tests. The application makes some use of integration testing.

### Ruby and Rails Quality

* **10 points** - Developer is able to craft Rails features that make smart use of Ruby, follow the principles of MVC, and push business logic down where it belongs. There _zero_ instances where an instructor would recommend taking a different approach. Developer writes code that is exceptionally clear and well-factored. Application is expertly divided into logical components each with a clear, single responsibility.

### JavaScript Style

* **8 points** - Application is thoughtfully put together with some duplication and no major bugs. Developer can speak to choices made in the code and knows what every line of code is doing.

### Workflow

* **3 points** - The developer makes large commits covering multiple features that make it difficult for the evaluator to determine the evolution of the application.
