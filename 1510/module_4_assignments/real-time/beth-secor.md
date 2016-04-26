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

179/200

### Concept and Features

Does it have the expected features?

* 100 points - Exceeded expectations. There are more features than we planned.

### Code Quality (JavaScript and/or Ruby)

* 20 points - Developer writes effective code, but does not breakout logical components. Application shows some effort to break logic into components, but the divisions are inconsistent or unclear. There are many large methods or functions and it is not clear to the evaluator what a given section of code does.

### Client-Side Application

* 25 points - Your application is thoughtfully put together with some duplication and no major bugs.

### Test-Driven Development

* 25 points - The code demonstrates high test coverage. It is tests at controller and unit levels. All controller/routes are tested. There are no failing tests.

### Interface

* 5 points - The application is pleasant, logical, and easy to use

### Workflow

* 4 points - The developer makes a series of small, atomic commits that document the evolution of their application. There are no formatting issues in the code base.
