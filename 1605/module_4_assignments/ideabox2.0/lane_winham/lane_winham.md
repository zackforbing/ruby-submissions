
# Basics

### Link to the Github Repository for the Project
[Your Repo](https://github.com/Laner12/revenge_of_idea_box)

### Link to the Deployed Application
[Your Application](https://revenge-of-idea-box.herokuapp.com/)

### Link to Your Commits in the Github Repository for the Project
[Your Commits](https://github.com/Laner12/revenge_of_idea_box/commits/master)

### Provide a Screenshot of your Application
![Idea Box Homepage](http://i.imgur.com/6FrjDn3.png)

## Completion

### Were you able to complete the base functionality?

* I was unable to finish the filtering with the navbar search
* I was unable to finish sanitizing the body length

# Code Quality

### Link to a specific block of your code on Github that you are proud of
[Code link](https://github.com/Laner12/revenge_of_idea_box/blob/master/app/assets/javascripts/idea.js#L89-L98)
* Why were you proud of this piece of code?

* It is probably not anywhere near good javascript but this was how I figured out how to pass the information to the controller.

### Link to a specific block of your code on Github that you feel not great about
[Code link](https://github.com/Laner12/revenge_of_idea_box/blob/master/app/controllers/api/v1/ideas_controller.rb#L11-L19)
* Why do you feel not awesome about the code? What challenges did you face trying to write/refactor it?

* I was having issues with how to update the voting params so I sent params to the controller to handle it, but I think there was certainly a better way.

### Attach a screenshot or paste the output from your terminal of the result of your test-suite running.
![Test suite](http://i.imgur.com/r5VWir3.png)

-----

### Please feel free to ask any other questions or make any other statements below!

* I was having issues grabing all of the ideas in order to filter them. I was trying ``` $idea = $(".idea") ``` assuming that it would return an array of all ideas on the DOM. How could I have got all ideas?

* Idea bodies longer than 100 characters should be truncated to the nearest word. (5 points)
*  The user should be able to "commit" their changes by pressing "Enter/Return" or by clicking outside of the text field. (2 points)

(15 points total.)

73 +



## Instructor Evaluation Points

### Specification Adherence

* **10 points**: The application consists of one page with all of the major functionality being provided by jQuery. There is no use of `format.js` in Rails. There is no use of unobstrusive JavaScript. There are no front-end frameworks used in the application. No approach was taken that is counter to the spirit of the project and its learning goals. There are no features missing from above that make the application feel incomplete or hard to use.

### User Interface
* 4 One small thing needed to be explained - overall a good composition and experience

* **5 points** - The application is pleasant, logical, and easy to use. There no holes in functionality and the application stands on it own to be used by the instructor _without_ guidance from the developer.
* **3 points** - The application has many strong pages/interactions, but a few holes in lesser-used functionality.

### Testing
* __7__ - Only one integration test.

* **8 points** - Project has a running test suite that tests and multiple levels but fails to cover some features. All controller actions are covered by tests. The application makes some use of integration testing.

### Ruby and Rails Quality

* **8 points** - Developer solves problems with a balance between conciseness and clarity and often extracts logical components. Developer can speak to choices made in the code and knows what every line of code is doing.

### JavaScript Style

* **8 points** - Application is thoughtfully put together with some duplication and no major bugs. Developer can speak to choices made in the code and knows what every line of code is doing.

### Workflow
** 9 - Would like to see more commits and management of the code through the process.

* **10 points** - The developer effectively uses Git branches and many small, atomic commits that document the evolution of their application.
