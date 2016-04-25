# RealTime Submission Form
[Project Spec](https://github.com/turingschool/curriculum/blob/master/source/projects/real_time.markdown)

# Basics

### Link to the Github Repository for the Project
[My Repo](https://github.com/ShannonPaige/real-time)

### Link to the Deployed Application
[My Application](https://obscure-castle-51089.herokuapp.com/)

### Link to Your Commits in the Github Repository for the Project
[My Commits](https://github.com/ShannonPaige/real-time/commits/master)

### Provide a Screenshot of your Application
![construction](http://g.recordit.co/8z86QS8OPd.gif)

## Completion

### Were you able to complete functionality that fits both case studies?
Almost....

### List any functionality from the case studies that is missing
I didn't provide a way for the admin to close the poll by a certain time. It has
to be done manually.

### Did you do anything outside the scope of the case studies?
* I used different ids for the dashboard and the voting page, and kept the dashboardId secret from voters,
so they can't access it.

* It wasn't outside the scope, but I noticed that if there were multiple polls, the results being rendered
were for the one that had been most recently voted on. I added the id of the poll
to the voting container and then check it against the current polls id.

# Code Quality

### Link to a specific block of your code on Github that you are proud of
[Link](https://github.com/ShannonPaige/real-time/blob/master/lib/find-current-poll.js)
[Link](https://github.com/ShannonPaige/real-time/blob/master/server.js#L55)
* Adding the id and checking if the poll we're emitting to is the correct poll was pretty cool.

### Link to a specific block of your code on Github that you feel not great about
[Link](https://github.com/ShannonPaige/real-time/blob/master/public/client.js#L42-L52)
* These are so similar I smell that I could do something with them, but I couldn't make it work.

### Attach a screenshot or paste the output from your terminal of the result of your test-suite running.
I couldn't get tests to work, and wasn't able to figure out a way to console log results for troubleshooting.
![](http://g.recordit.co/jaEpnTs4w1.gif)

### Provide a link to an example, if you have one, of a test that covers an 'edge case' or 'unhappy path'
No

-----

### Please feel free to ask any other questions or make any other statements below!
* I have a branch where I did it all with jQuery instead of js, but I had to give it up because of issues with
.text() and .replaceWith() not updating until refresh. It would be cool to go over why that was happening.``


-----

## Instructor Feedback

119/200

### Concept and Features

Does it have the expected features?

* 50 points - Some features were sacrificed to meet the deadline. At best, this is a prototype. Major features covered by the learning goals listed above were not written by the developer.

### Code Quality (JavaScript and/or Ruby)

* 25 points - Developer solves problems with a balance between conciseness and clarity and often extracts logical components. Developer can speak to choices made in the code and knows what every line of code is doing.

### Client-Side Application

* 25 points - Your application is thoughtfully put together with some duplication and no major bugs.

### Test-Driven Development

* 10 points - Many areas of the code are not covered by tests.

### Interface

* 4 points - The application has many strong pages/interactions, but a few holes in lesser-used functionality.

### Workflow

* 5 points - The developer effectively uses Git branches and many small, atomic commits that document the evolution of their application.
