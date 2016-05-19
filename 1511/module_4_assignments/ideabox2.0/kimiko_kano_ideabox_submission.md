# Ideabox 2.0 Submission Form
[Project Spec](https://github.com/turingschool/curriculum/blob/master/source/projects/revenge_of_idea_box.markdown)

# Basics

### Link to the Github Repository for the Project
[My Repo](https://github.com/ksk5280/js_idea_box)

### Link to the Deployed Application
[My Application](http://js-idea-box.herokuapp.com/)

### Link to My Commits in the Github Repository for the Project
[My Commits](https://github.com/ksk5280/js_idea_box/commits/master)

### Provide a Screenshot of your Application
![screenshot](images/screenshot.jpg)

## Completion

### Were you able to complete the base functionality?
* Yes

### Which extensions, if any, did you complete?
* I completed the sorting extension

### Attach a .gif, or images of any extensions work being used on the site.
http://recordit.co/eNDiVxxkwb

# Code Quality

### Link to a specific block of your code on Github that you are proud of
* Why were you proud of this piece of code?

https://github.com/ksk5280/js_idea_box/blob/master/app/assets/javascripts/add_ideas.js#L1-14

I think this block of code is pretty clean. The serialize method is convenient because it gets the info from the form and you can easily pass that data to the ajax call.


### Link to a specific block of your code on Github that you feel not great about
* Why do you feel not awesome about the code? What challenges did you face trying to write/refactor it?

https://github.com/ksk5280/js_idea_box/blob/master/app/assets/javascripts/sort_ideas.js#L19-57

I was happy to be able to get the sorting to work, but I used the same code to sort ascending and descending. I'm sure I could refactor it relatively easily, but it's late and I'm so tired...

### Attach a screenshot or paste the output from your terminal of the result of your test-suite running.
```
 --> rspec
.......................

Finished in 17.45 seconds (files took 2.79 seconds to load)
23 examples, 0 failures

Coverage report generated for RSpec to /Users/kimiko/Documents/Turing/4module/projects/js_idea_box/coverage. 30 / 30 LOC (100.0%) covered.

--> rake teaspoon
Starting the Teaspoon server...
Teaspoon running default suite at http://127.0.0.1:55839/teaspoon/default
..

Finished in 0.00800 seconds
2 examples, 0 failures
```
### Provide a link to an example, if you have one, of a test that covers an 'edge case' or 'unhappy path'

https://github.com/ksk5280/js_idea_box/blob/master/spec/requests/api/v1/ideas_controller_spec.rb
-----


# Instructor Feedback

151 (141 + 10 for extension)/150

### Data Model

(5 points total.)

### User Flows

#### Viewing ideas

(7 points total.)

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

#### Extension: Sorting
(+ 10 points)

### Instructor Evaluation Points

#### Specification Adherence

10 points: The application consists of one page with all of the major functionality being provided by jQuery. There is no use of format.js in Rails. There is no use of unobstrusive JavaScript. There are no front-end frameworks used in the application. No approach was taken that is counter to the spirit of the project and its learning goals. There are no features missing from above that make the application feel incomplete or hard to use.

#### User Interface

5 points - The application is pleasant, logical, and easy to use. There no holes in functionality and the application stands on it own to be used by the instructor without guidance from the developer.

#### Testing

8 points - Project has a running test suite that tests and multiple levels but fails to cover some features. All controller actions are covered by tests. The application makes some use of integration testing.

#### Ruby and Rails Quality

8 points - Developer solves problems with a balance between conciseness and clarity and often extracts logical components. Developer can speak to choices made in the code and knows what every line of code is doing.

#### JavaScript Style

8 points - Application is thoughtfully put together with some duplication and no major bugs. Developer can speak to choices made in the code and knows what every line of code is doing.

#### Workflow

10 points - The developer effectively uses Git branches and many small, atomic commits that document the evolution of their application.
