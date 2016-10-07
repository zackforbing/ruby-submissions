### Basics
Link to the Github Repository for the Project:

[My Repo](https://github.com/chompasina/ideabox)

Link to the Deployed Application

[My Application](https://infinite-wildwood-24384.herokuapp.com/)

Link to Your Commits in the Github Repository for the Project

[My Commits](https://github.com/chompasina/ideabox/commits/master)

Provide a Screenshot of your Application

spacejam

Completion

Were you able to complete the base functionality?

* Yes, base functionality is complete.

If not, list what functionality is missing.
Which extensions, if any, did you complete?

Attach a .gif, or images of any extensions work being used on the site.

Code Quality
Link to a specific block of your code on Github that you are proud of:

https://github.com/chompasina/ideabox/blob/master/app/assets/javascripts/ideas.js#L70-L88

Why were you proud of this piece of code?

* I'm proud of this code because it encompasses a few ideas that I hadn't felt familiar with before this project -- event listeners, especially identifying a particular key that is pressed; blur on clicking away; and clearing the selection afterwards.

Link to a specific block of your code on Github that you feel not great about

* https://github.com/chompasina/ideabox/blob/master/app/assets/javascripts/ideas.js#L33-L52

Why do you feel not awesome about the code? What challenges did you face trying to write/refactor it?

* This code felt hacky to me, rendering HTML into the JS function. In trying to refactor it, I wasn't sure how I could possibly add it into my HTML file instead.

Attach a screenshot or paste the output from your terminal of the result of your test-suite running.
🐈  @ideabox: rspec
..

Finished in 10.72 seconds (files took 6.1 seconds to load)
2 examples, 0 failures

Coverage report generated for RSpec to /Users/tommasinamiller/turinghw/projects/module4/ideabox/coverage. 28 / 31 LOC (90.32%) covered.

Provide a link to an example, if you have one, of a test that covers an 'edge case' or 'unhappy path'

Please feel free to ask any other questions or make any other statements below!



* Idea bodies longer than 100 characters should be truncated to the nearest word. (5 points)

## Instructor Evaluation Points

### Specification Adherence

* **10 points**: The application consists of one page with all of the major functionality being provided by jQuery. There is no use of `format.js` in Rails. There is no use of unobstrusive JavaScript. There are no front-end frameworks used in the application. No approach was taken that is counter to the spirit of the project and its learning goals. There are no features missing from above that make the application feel incomplete or hard to use.

### User Interface
* __4__ Had one small piece of the feature I needed to be explained - overall composition and layout is intuitive and usable

* **5 points** - The application is pleasant, logical, and easy to use. There no holes in functionality and the application stands on it own to be used by the instructor _without_ guidance from the developer.
* **3 points** - The application has many strong pages/interactions, but a few holes in lesser-used functionality.

### Testing
  * 3 - Few integration tests - no controller tests

* **0 points** - There is little or no evidence of testing in this application.

### Ruby and Rails Quality

* **10 points** - Developer is able to craft Rails features that make smart use of Ruby, follow the principles of MVC, and push business logic down where it belongs. There _zero_ instances where an instructor would recommend taking a different approach. Developer writes code that is exceptionally clear and well-factored. Application is expertly divided into logical components each with a clear, single responsibility.

### JavaScript Style

* **5 points** - Your application has some duplication and minor bugs. Developer can speak to most choices made in the code and knows what every line is doing.

### Workflow

* **10 points** - The developer effectively uses Git branches and many small, atomic commits that document the evolution of their application.
