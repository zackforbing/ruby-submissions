# Ideabox 2.0 Submission Form
[Project Spec](https://github.com/turingschool/curriculum/blob/master/source/projects/revenge_of_idea_box.markdown)
------

# Basics

### Link to the Github Repository for the Project
[Repo](https://github.com/cheljoh/ideabox)

### Link to the Deployed Application
[Application Link](https://cheljohideas.herokuapp.com/)

### Link to Your Commits in the Github Repository for the Project
[Commits](https://github.com/cheljoh/ideabox/commits/master?page=1)

### Provide a Screenshot of your Application
![application](http://g.recordit.co/FMwnbSPB4q.gif)

## Completion

### Were you able to complete the base functionality?
* Yes, I was able to complete all requirements.

### Which extensions, if any, did you complete?
* None(yet)

### Attach a .gif, or images of any extensions work being used on the site.

# Code Quality

### Link to a specific block of your code on Github that you are proud of
 [Code](https://github.com/cheljoh/ideabox/blob/master/app/assets/javascripts/load_ideas.js#L1-L9)
* I like this bit of code because it is clean.

### Link to a specific block of your code on Github that you feel not great about
  [Code](https://github.com/cheljoh/ideabox/blob/master/app/assets/javascripts/events.js#L99-L108)
* This code allows me to reuse my update ajax call function, but I don't like the conditionals. I have similar code elsewhere.

### Attach a screenshot or paste the output from your terminal of the result of your test-suite running.

--> rspec
...................

Finished in 42.8 seconds (files took 2.87 seconds to load)
19 examples, 0 failures

Coverage report generated for RSpec to /Users/chelseajohnson/Documents/turing/4module/ideabox/coverage. 38 / 38 LOC (100.0%) covered.

--> rake teaspoon
Starting the Teaspoon server...
Teaspoon running default suite at http://127.0.0.1:51497/teaspoon/default
.....

Finished in 0.00900 seconds
5 examples, 0 failures

### Provide a link to an example, if you have one, of a test that covers an 'edge case' or 'unhappy path'
[Sad Path](https://github.com/cheljoh/ideabox/blob/master/spec/features/user_adds_a_new_idea_spec.rb#L31-L49)

-----

### Please feel free to ask any other questions or make any other statements below!

# Instructor Feedback

147/150

### Data Model

(5 points total.)

### User Flows

#### Viewing ideas

(9 points total.)

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

### Instructor Evaluation Points

#### Specification Adherence

10 points: The application consists of one page with all of the major functionality being provided by jQuery. There is no use of format.js in Rails. There is no use of unobstrusive JavaScript. There are no front-end frameworks used in the application. No approach was taken that is counter to the spirit of the project and its learning goals. There are no features missing from above that make the application feel incomplete or hard to use.

#### User Interface

5 points - The application is pleasant, logical, and easy to use. There no holes in functionality and the application stands on it own to be used by the instructor without guidance from the developer.

#### Testing

10 points - Project has a running test suite that exercises the application at multiple levels including JavaScript tests.

#### Ruby and Rails Quality

10 points - Developer is able to craft Rails features that make smart use of Ruby, follow the principles of MVC, and push business logic down where it belongs. There zero instances where an instructor would recommend taking a different approach. Developer writes code that is exceptionally clear and well-factored. Application is expertly divided into logical components each with a clear, single responsibility.

#### JavaScript Style

8 points - Application is thoughtfully put together with some duplication and no major bugs. Developer can speak to choices made in the code and knows what every line of code is doing.

#### Workflow

10 points - The developer effectively uses Git branches and many small, atomic commits that document the evolution of their application.
