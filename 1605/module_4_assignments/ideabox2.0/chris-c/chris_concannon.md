# Ideabox 2.0 Submission Form
[Project Spec](https://github.com/turingschool/curriculum/blob/master/source/projects/revenge_of_idea_box.markdown)

------

# Basics

### Link to the Github Repository for the Project
[Github Repo](https://www.github.com/concach/idea_box)

### Link to the Deployed Application
[Heroku Deployment](https://concach-idea-box.herokuapp.com/)

### Link to Your Commits in the Github Repository for the Project
[Your Commits](https://github.com/concach/idea_box/commits/master)

### Provide a Screenshot of your Application
[Idea Box Homepage](./chris_concannon_idea_box.png)

## Completion

### Were you able to complete the base functionality?
* I was able to complete functionality for adding ideas, deleting ideas, and modifying the quality for ideas. I was not able to fully complete the search filters and the editing function for title and body of an idea, but each of these features is partially complete.

### Which extensions, if any, did you complete?
* I did not complete extensions

### Attach a .gif, or images of any extensions work being used on the site.

# Code Quality

### Link to a specific block of your code on Github that you are proud of
[Code Link](https://github.com/concach/idea_box/blob/master/app/assets/javascripts/ideas.js#L48-L60)
* I am proud of this particular piece of code because I think it wisely uses function arguments to update a function, and it is designed to be re-usable across updates to multiple attributes of an idea.

### Link to a specific block of your code on Github that you feel not great about
[Code Link](https://github.com/concach/idea_box/blob/master/app/assets/javascripts/ideas.js#L131-L156)
* I do not feel particularly great about this piece of code because I know that my event listeners are flawed, and my search bar code (commented out) does not function properly.

### Attach a screenshot or paste the output from your terminal of the result of your test-suite running.
[Idea Box Tests](./chris_concannon_idea_box_spec.png)

### Provide a link to an example, if you have one, of a test that covers an 'edge case' or 'unhappy path'
[Idea Box Edge Case Testing](https://github.com/concach/idea_box/blob/master/spec/models/idea_spec.rb#L12-L32)

-----

### Please feel free to ask any other questions or make any other statements below!






*  The user should be able to "commit" their changes by pressing "Enter/Return" or by clicking outside of the text field. (4 points)
* If the user reloads the page, their edits will be reflected. (4 points, mandatory for specification adherence)
* As a user types in the search box, the list of ideas should filter in real time to only display ideas whose title or body include the user's text. The page _should not_ reload. (6 points)
* Clearing the search box should restore all the ideas to the list. (6 points)

95 - 20 = 75

75 + 38 = 113

### Specification Adherence
38 / 55

* **8 points**: The application consists of one page with all of the major functionality being provided by jQuery. There is no use of `format.js` in Rails. There is no use of unobstrusive JavaScript. There are no front-end frameworks used in the application. No approach was taken that is counter to the spirit of the project and its learning goals. There are no features missing from above that make the application feel incomplete or hard to use.

### User Interface

* **2 points** - The application shows effort in the interface, but the result is not effective. The evaluator has some difficulty using the application when reviewing the features in the user stories.

### Testing

* **5 points** - Project has sporadic use of tests and multiple levels. Not all controller actions are tested. There are little or no attempts at integration testing.

### Ruby and Rails Quality

* 7 - some larger methods - a little too much logic in the controller - could push it to the model. Binding.pry in controller.

* **8 points** - Developer solves problems with a balance between conciseness and clarity and often extracts logical components. Developer can speak to choices made in the code and knows what every line of code is doing.
* **5 points** - Developer writes effective code, but does not breakout logical components. Application shows some effort to break logic into components, but the divisions are inconsistent or unclear. There are many large methods or functions and it is not clear to the evaluator what a given section of code does. Developer cannot speak to every line of code on the server side.

### JavaScript Style

Some bugs - some base functionality missing - opportunities to refactor - Good attempts and can speak to code

* **6 points** - Your application has some duplication and minor bugs. Developer can speak to most choices made in the code and knows what every line is doing.

### Workflow

* **10 points** - The developer effectively uses Git branches and many small, atomic commits that document the evolution of their application.
