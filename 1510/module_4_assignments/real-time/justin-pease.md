# RealTime Submission Form
[Project Spec](https://github.com/turingschool/curriculum/blob/master/source/projects/real_time.markdown)

* Fork this repo, if you haven't already and check out a branch
* Use this README as a template to create a file in this folder with your name as the title.
* Submit a pull request

------

# Basics

### Link to the Github Repository for the Project
[Justin Pease Crowd Source](https://github.com/Jpease1020/crowdsource)

### Link to the Deployed Application
[Live App](https://crowd-poll.herokuapp.com/)

### Link to Your Commits in the Github Repository for the Project
[My Commits](https://github.com/Jpease1020/crowdsource/commits/master)

### Provide a Screenshot of your Application
![screen shot](http://g.recordit.co/W2MdcpMtm2.gif)

## Completion

### Were you able to complete functionality that fits both case studies?
Yes
### List any functionality from the case studies that is missing
N/A
### Did you do anything outside the scope of the case studies?
No
# Code Quality

### Link to a specific block of your code on Github that you are proud of
[socket emits to specific polls](https://github.com/Jpease1020/crowdsource/blob/e036f3504e5bca5304998ab59c04ae69e0c0329c/server.js#L92-L102)

* Why were you proud of this piece of code?
I don't think there is anything ground breaking going on but I was happy to figure out a way to have the sockets listen for individual polls so each poll goes from the server only to pages that have the links to that specific poll.

### Link to a specific block of your code on Github that you feel not great about
[if statements](https://github.com/Jpease1020/crowdsource/blob/e036f3504e5bca5304998ab59c04ae69e0c0329c/server.js#L92-L102)
* Why do you feel not awesome about the code? What challenges did you face trying to write/refactor it?
I had trouble converting things over to ES6.  I struggled to implement the use of local storage in a way that cover all scenarios of data being lost or shown to the wrong polls.  I'm also not crazy about having each function in the socket listener in the server needing an if statement to check against.  I wanted to create an object that would store the socket channels as keys each returning the correct function but haven't figured out how to create the object and pass the needed values to the functions.

### Attach a screenshot or paste the output from your terminal of the result of your test-suite running.
[igmur-image](http://imgur.com/rDYQNGK)
### Provide a link to an example, if you have one, of a test that covers an 'edge case' or 'unhappy path'

-----

### Please feel free to ask any other questions or make any other statements below!


-----

## Instructor Feedback

### Concept and Features

Does it have the expected features?

* 100 points - Exceeded expectations. There are more features than we planned.
* 75 points - Met expectations as outlined by the user personas, the application is a solid first version. All planned features were delivered.
* 50 points - Some features were sacrificed to meet the deadline. At best, this is a prototype. Major features covered by the learning goals listed above were not written by the developer.
* 25 points - Major features are missing, there are major bugs that make it impossible to use, and/or the application is not deployed to production.
* 0 - There is no application.

### Code Quality (JavaScript and/or Ruby)

* 30 points - Developer writes code that is exceptionally clear and well-factored. Application is expertly divided into logical components each with a clear, single responsibility.
* 25 points - Developer solves problems with a balance between conciseness and clarity and often extracts logical components. Developer can speak to choices made in the code and knows what every line of code is doing.
* 20 points - Developer writes effective code, but does not breakout logical components. Application shows some effort to break logic into components, but the divisions are inconsistent or unclear. There are many large methods or functions and it is not clear to the evaluator what a given section of code does.
* 10 points - Developer writes code with unnecessary variables, operations, or steps which do not increase clarity.
* 0 points - Developer writes code that is difficult to understand. Application logic shows poor decomposition with too much logic mashed together.

### Client-Side Application

* 30 points - Your application has exceptionally well-factored code with little or now duplication and all components separated out into logical components.
* 25 points - Your application is thoughtfully put together with some duplication and no major bugs.
* 20 points - Your application has a significant amount of duplication and one or major bugs.
* 10 points - Your client-side application does not function or the application does not make use of WebSockets for updating information on the client.
* 0 points - There is little or no client-side code.

### Test-Driven Development

* 30 points - The code demonstrates high test coverage. It is tested at the feature, controller and unit levels. It tests the WebSocket as well as the controller endpoints.
* 25 points - The code demonstrates high test coverage. It is tests at controller and unit levels. All controller/routes are tested. There are no failing tests.
* 20 points - The code demonstrates high test coverage. One or more enpoints are not tested or the internal business logic is not fully tested.
* 10 points - Many areas of the code are not covered by tests.
* 0 points - No tests were written or the testing framework does not work.

### Interface

* 5 points - The application is pleasant, logical, and easy to use
* 4 points - The application has many strong pages/interactions, but a few holes in lesser-used functionality.
* 2 points - The application shows effort in the interface, but the result is not effective. The evaluator has some difficulty using the application when reviewing the features in the user stories.
* 0 points - The application is confusing or difficult to use.

### Workflow

* 5 points - The developer effectively uses Git branches and many small, atomic commits that document the evolution of their application.
* 4 points - The developer makes a series of small, atomic commits that document the evolution of their application. There are no formatting issues in the code base.
* 2 points - The developer makes large commits covering multiple features that make it difficult for the evaluator to determine the evolution of the application.
* 0 points - The developer commited the code to version control in only a few commits. The evaluator cannot determine the evolution of the application.
* 0 points - The application was not checked into version control.
