# RealTime Submission Form
[Project Spec](https://github.com/turingschool/curriculum/blob/master/source/projects/real_time.markdown)

------

# Basics

### Link to the Github Repository for the Project
[Your Repo](https://github.com/PenneyGadget/crowdsource)

### Link to the Deployed Application
[Your Application](https://realtime-crowdsource.herokuapp.com/)

### Link to Your Commits in the Github Repository for the Project
[Your Commits](https://github.com/PenneyGadget/crowdsource/commits/master)

### Provide a Screenshot of your Application
![Crowdsource](http://i.imgur.com/593RIhX.jpg)

## Completion

### Were you able to complete functionality that fits both case studies?

Yes.

### List any functionality from the case studies that is missing

None.

### Did you do anything outside the scope of the case studies?

I took the time to actually do CSS and style the app so it's fun to use.

# Code Quality

### Link to a specific block of your code on Github that you are proud of
[disablePoll function](https://github.com/PenneyGadget/crowdsource/blob/master/public/client.js#L47-L59)

It's not that I'm particularly proud of this function, as I'm sure it can be refactored, I just learned
several new things in implementing this function. Because I ended up not using jQuery, I learned to do
some simple DOM manipulation within basic JS which gave me a better understanding of JS in general.

### Link to a specific block of your code on Github that you feel not great about
[app.post route](https://github.com/PenneyGadget/crowdsource/blob/master/server.js#L21-L35)

I wanted to refactor this and pull out setting the poll attributes to their own class, but I got so
busy with fixing little websocket errors that crept up that I ran out of time and was afraid to try
to do an extraction at the last minute.

### Attach a screenshot or paste the output from your terminal of the result of your test-suite running.

![Test suite](http://i.imgur.com/Z66xRXe.png)

### Provide a link to an example, if you have one, of a test that covers an 'edge case' or 'unhappy path'

[These two tests](https://github.com/PenneyGadget/crowdsource/blob/master/test/server-test.js#L91-L110)
check that a poll is not created and the user is not redirected if either a title is missing or there
are not at least two voting options submitted.

### Please feel free to ask any other questions or make any other statements below!


-----

## Instructor Feedback

175/200

### Concept and Features

Does it have the expected features?

* 100 points - Exceeded expectations. There are more features than we planned.

### Code Quality (JavaScript and/or Ruby)

* 20 points - Developer writes effective code, but does not breakout logical components. Application shows some effort to break logic into components, but the divisions are inconsistent or unclear. There are many large methods or functions and it is not clear to the evaluator what a given section of code does.

### Client-Side Application

* 25 points - Your application is thoughtfully put together with some duplication and no major bugs.

### Test-Driven Development

* 20 points - The code demonstrates high test coverage. One or more enpoints are not tested or the internal business logic is not fully tested.

### Interface

* 5 points - The application is pleasant, logical, and easy to use

### Workflow

* 5 points - The developer effectively uses Git branches and many small, atomic commits that document the evolution of their application.
