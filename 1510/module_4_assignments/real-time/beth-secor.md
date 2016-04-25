# RealTime Submission Form
[Project Spec](https://github.com/turingschool/curriculum/blob/master/source/projects/real_time.markdown)

------

# Basics

### Link to the Github Repository for the Project
[Repo](https://github.com/bethsecor/realtime-crowdsource)

### Link to the Deployed Application
[Application](https://arcane-lake-19394.herokuapp.com/)

### Link to Your Commits in the Github Repository for the Project
[Commits](https://github.com/bethsecor/realtime-crowdsource/commits/master)

### Provide a Screenshot of your Application
![gif](http://g.recordit.co/HXyirVaI0Y.gif)

## Completion

### Were you able to complete functionality that fits both case studies?

Yes!

### List any functionality from the case studies that is missing

No functionality missing.

### Did you do anything outside the scope of the case studies?

I did not.

# Code Quality

### Link to a specific block of your code on Github that you are proud of

I am proud of [this sockets code on the server side](https://github.com/bethsecor/realtime-crowdsource/blob/master/server.js#L70) because it took me a while conceptually to grasp websockets and I feel now after this project that I understand them much better. I am also proud that I [broke out these helper functions](https://github.com/bethsecor/realtime-crowdsource/tree/master/lib) into separate files so I could test them.

### Link to a specific block of your code on Github that you feel not great about

I don't feel great about [this jQuery](https://github.com/bethsecor/realtime-crowdsource/blob/master/public/client.js#L51), it's messy and I should have put them in functions.

### Attach a screenshot or paste the output from your terminal of the result of your test-suite running.

![tests](http://i.imgur.com/5uuL4bE.png)

### Provide a link to an example, if you have one, of a test that covers an 'edge case' or 'unhappy path'

-----

### Please feel free to ask any other questions or make any other statements below!

- Why in the websockets tutorial did we export `module.exports = server` and not `module.exports = app`? (In pizza express we exported `app`).

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
