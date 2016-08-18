# Ideabox 2.0 Submission Form - Charlie Kaminer
[Project Spec](https://github.com/turingschool/curriculum/blob/master/source/projects/revenge_of_idea_box.markdown)

------

# Basics

### Link to the Github Repository for the Project
[Your Repo](https://github.com/ckaminer/idea_box)

### Link to the Deployed Application
[Your Application](http://guarded-brook-71177.herokuapp.com/)

### Link to Your Commits in the Github Repository for the Project
[Your Commits](https://github.com/ckaminer/idea_box/commits/master)

### Provide a Screenshot of your Application
![ideabox](images/charlie_idea_box.jpg)

## Completion

### Were you able to complete the base functionality?
* Aside from the truncation feature (in production), yes.

### Which extensions, if any, did you complete?
* I completed the quality sort extension.

### Attach a .gif, or images of any extensions work being used on the site.
![extension](http://g.recordit.co/dX3fRTAsTe.gif)

# Code Quality

### Link to a specific block of your code on Github that you are proud of
* Why were you proud of this piece of code?

 [Create Idea Event](https://github.com/ckaminer/idea_box/blob/d7d065b1c6fc2f55126025d0ce3e2b0a0758abef/app/assets/javascripts/create_and_load.js#L32-L50)

 I'm proud of this piece of code because it not only deals with idea creation in a relatively clean way but also touches on UX.  I was having problems with blank boxes getting added to the table despite not making it through a successful ajax request.  I like the fact that a user will receive an explicit alert message without leaving the page.

### Link to a specific block of your code on Github that you feel not great about
* Why do you feel not awesome about the code? What challenges did you face trying to write/refactor it?

 [Upvote Downvote](https://github.com/ckaminer/idea_box/blob/d7d065b1c6fc2f55126025d0ce3e2b0a0758abef/app/assets/javascripts/quality_vote.js#L17-L37)

 I don't feel awesome about this code for a few reasons.  For one, it would have been more beneficial to not use an enum here (here meaning this entire project).  This code is an example of its downsides as I am forced to make multiple references to the quality array which is not ideal.  Additionally, this can very clearly be re-factored as almost the entire method is the same for up and down votes.  Ideally, I'd like to implement some kind of "direction" logic similar to how I did in the quality sort methods.


### Attach a screenshot or paste the output from your terminal of the result of your test-suite running.
![ideabox](images/charlie_tests.jpg)

![ideaboxjs](images/charlie_js_tests.jpg)

### Provide a link to an example, if you have one, of a test that covers an 'edge case' or 'unhappy path'
*
 [Search Filter Feature Spec](https://github.com/ckaminer/idea_box/blob/d7d065b1c6fc2f55126025d0ce3e2b0a0758abef/spec/features/search_filter_spec.rb#L17-L38)
-----

### Please feel free to ask any other questions or make any other statements below!

# Instructor Feedback

133/150

** If you want to finish truncation, we can re-eval that and amend ***

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

0 points

*** can be amended if pushed and fixed ***

* When a user clicks the title or body of an idea in the list, that text should become an editable text field, pre-populated with the existing idea title or body. (8 points)
* Clicking this link should _not_ take the user to a separate "edit" page for the given
  idea. (4 points, mandatory for specification adherence)
*  The user should be able to "commit" their changes by pressing "Enter/Return" or by clicking outside of the text field. (4 points)
* If the user reloads the page, their edits will be reflected. (4 points, mandatory for specification adherence)

#### Idea Filtering and Searching

(15 points total.)

### Extensions

#### Sorting

(10 additional points.)

## Instructor Evaluation Points

### Specification Adherence

* **10 points**

### User Interface

* **5 points** - The application is pleasant, logical, and easy to use. There no holes in functionality and the application stands on it own to be used by the instructor _without_ guidance from the developer.

### Testing

* **10 points** - Project has a running test suite that exercises the application at multiple levels including JavaScript tests.

### Ruby and Rails Quality

* **10 points** - Developer is able to craft Rails features that make smart use of Ruby, follow the principles of MVC, and push business logic down where it belongs. There _zero_ instances where an instructor would recommend taking a different approach. Developer writes code that is exceptionally clear and well-factored. Application is expertly divided into logical components each with a clear, single responsibility.

### JavaScript Style

* **8 points** - Application is thoughtfully put together with some duplication and no major bugs. Developer can speak to choices made in the code and knows what every line of code is doing.

### Workflow

* **10 points** - The developer effectively uses Git branches and many small, atomic commits that document the evolution of their application.
