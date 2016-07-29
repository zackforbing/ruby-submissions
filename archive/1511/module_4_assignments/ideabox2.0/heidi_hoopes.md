# Basics

### Link to the Github Repository for the Project
[My Repo](https://github.com/hhoopes/idea_box)

### Link to the Deployed Application
[Boxed-Ideas](http://boxed-ideas.herokuapp.com/)

### Link to Your Commits in the Github Repository for the Project
[My Commits](https://github.com/hhoopes/idea_box/commits/master)

### Provide a Screenshot of your Application
![Filtered](https://github.com/hhoopes/idea_box/blob/master/images/screenshot1.png)
![All Ideas](https://github.com/hhoopes/idea_box/blob/master/images/screenshot2.png)

## Completion

### Were you able to complete the base functionality?
* I literally got all of the functionality, except that I didn't label the search box "Search" (but put that text inside the box).

### Which extensions, if any, did you complete?
* I didn't complete any extensions

### Attach a .gif, or images of any extensions work being used on the site.
N/A

# Code Quality

### Link to a specific block of your code on Github that you are proud of
[Filtering ideas](https://github.com/hhoopes/idea_box/blob/master/app/assets/javascripts/idea_filter.js#L1)

* Why were you proud of this piece of code?
I started off a little scared of the feature, but learned a lot about various events(keypress, keyup, change) and different ways you could match text in JS(match, indexOf). Because I gradually refactored it, I'm very happy with how well my search works. It's both case-insensitive and looks in the middle of the words or at partial words. And now I know the subtleties of using various keyboard events!

### Link to a specific block of your code on Github that you feel not great about
[Editing idea](https://github.com/hhoopes/idea_box/blob/master/app/assets/javascripts/idea_editor.js#L23)

* Why do you feel not awesome about the code? What challenges did you face trying to write/refactor it?
I had to duplicate a lot of code at first because I implemented enums in the database. It meant when I called an idea's quality on the front end, I was returned the string value. I realized later that there is a method for accessing the integer, but it's not as obvious. So I could refactor it now so I can do math with the qualities a little more easily and not have to use multiple if loops to handle different contexts.

### Attach a screenshot or paste the output from your terminal of the result of your test-suite running.
![Test Suite](https://github.com/hhoopes/idea_box/blob/master/images/tests.png)

### Provide a link to an example, if you have one, of a test that covers an 'edge case' or 'unhappy path'
* I didn't do great at this, so this is probably one of my best in this sense.

[link](https://github.com/hhoopes/idea_box/blob/master/spec/features/visitor_sees_all_ideas_spec.rb)
-----

### Please feel free to ask any other questions or make any other statements below!

# Instructor Feedback

142/150

### Data Model

(5 points total.)

### User Flows

#### Viewing ideas

(8 points total.)

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

8 points - Project has a running test suite that tests and multiple levels but fails to cover some features. All controller actions are covered by tests. The application makes some use of integration testing.

#### Ruby and Rails Quality

8 points - Developer solves problems with a balance between conciseness and clarity and often extracts logical components. Developer can speak to choices made in the code and knows what every line of code is doing.

####mJavaScript Style

8 points - Application is thoughtfully put together with some duplication and no major bugs. Developer can speak to choices made in the code and knows what every line of code is doing.

#### Workflow

10 points - The developer effectively uses Git branches and many small, atomic commits that document the evolution of their application.
