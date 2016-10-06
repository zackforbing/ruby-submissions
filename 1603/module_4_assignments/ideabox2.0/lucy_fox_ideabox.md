## Lucy Fox, Idea Box

### Important Links:

[Github Repo](https://github.com/lucyfox4131/idea_box.git)

[Production Link](https://all-the-ideas.herokuapp.com/)

[Github Commits](https://github.com/lucyfox4131/idea_box/commits/master)

### Screenshot:
[Screenshot](http://i.imgur.com/N0awFGq.png)

### Completion:
##### Were you able to complete the base functionality?
I was able to complete the bas functionality

##### Which extensions, if any, did you complete?
I did not complete any extensions

### Code Quality:
##### Link to a specific block of code on Github that you are proud of
 [Helper Methods for Upvote/Downvote Quality](https://github.com/lucyfox4131/idea_box/blob/master/app/assets/javascripts/quality_helpers.js)

##### Why were you proud of this piece of code?
I found that the upvote and downvote functions had quite a few similarities. I'm proud of the code I was able to refactor to pull out some of the common code between these two features. It feels like a good step towards learning how to refactor code.

##### Link to a specific block of your code on Github that you feel not great about
[Delete A Row](https://github.com/lucyfox4131/idea_box/blob/master/app/assets/javascripts/delete.js)

##### Why do you feel not awesome about the code? What challenges did you face trying to write/refactor it?
I struggled with the Delete function. I don't feel extremely good about deleting the row right without having some reliance on the ajax call. However, I struggled with "This" quite a bit and still feel I don't understand it quite as well as I should. Especially in terms of scope within different functions.

##### Attach a screenshot or past the output from your terminal of the result of your test-suite running.
[RSpec and Rake Teaspoon Tests Running](http://i.imgur.com/jtUtk8g.png)

##### Provide a link to an example, if you have one, of a test that covers an 'edge case' or 'unhappy path'
[Github Link - Sad Path Test - Idea won't be created without a title](https://github.com/lucyfox4131/idea_box/blob/master/spec/requests/api/v1/ideas_controller_spec.rb)

## Instructor Feedback

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

* **4 points** - The application has many strong pages/interactions, but a few holes in lesser-used functionality.

### Testing

* **10 points** - Project has a running test suite that exercises the application at multiple levels including JavaScript tests.

### Ruby and Rails Quality

* **9 points** - Developer is able to craft Rails features that make smart use of Ruby, follow the principles of MVC, and push business logic down where it belongs. There _zero_ instances where an instructor would recommend taking a different approach. Developer writes code that is exceptionally clear and well-factored. Application is expertly divided into logical components each with a clear, single responsibility.

### JavaScript Style

* **8 points** - Application is thoughtfully put together with some duplication and no major bugs. Developer can speak to choices made in the code and knows what every line of code is doing.

### Workflow

* **10 points** - The developer effectively uses Git branches and many small, atomic commits that document the evolution of their application.
