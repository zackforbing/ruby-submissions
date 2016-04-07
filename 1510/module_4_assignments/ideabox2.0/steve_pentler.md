# Idea Box

### Link to the Github Repository for the Project
[GitHub Repo](https://github.com/stevepentler/IdeaBox)

### Link to the Deployed Application
[Live Link](https://pentler-ideas.herokuapp.com/)

### Link to Your Commits in the Github Repository for the Project
[Commits](https://github.com/stevepentler/IdeaBox/commits/master)

### Provide a Screenshot of your Application
![](http://g.recordit.co/jflg8dNj6L.gif)

## Completion

### Were you able to complete the base functionality?
All base functionality is complete.

### Which extensions, if any, did you complete?
Inline Editing(10)

### Attach a .gif, or images of any extensions work being used on the site.
![](http://g.recordit.co/Ov33UONm3n.gif)

# Code Quality

### Link to a specific block of your code on Github that you are proud of
- [qualityIdea](https://github.com/stevepentler/IdeaBox/blob/master/app/assets/javascripts/quality_idea.js#L30)
DRY after refactoring from seperate promote and demote methods.
- [searchIdea](https://github.com/stevepentler/IdeaBox/blob/master/app/assets/javascripts/search_idea.js#L1) : Well named, human-readable, abstracted code.
- [Controller Testing](https://github.com/stevepentler/IdeaBox/blob/master/test/controllers/ideas_controller_test.rb#L25)
Specific, realiable controller testing for create, update, and delete. Decent testing for idea promotion/demotion.

### Link to a specific block of your code on Github that you feel not great about
- [editIdea](https://github.com/stevepentler/IdeaBox/blob/master/app/assets/javascripts/edit_idea.js#L7): I tried to refactor this code on 5 seperate occassions, but kept running into a problem with the contentEditable function. I finally got it, but it still looks "chunky." I'm not a a fan of how much space the ideaParams take up, but they require a fair amount of local varaiables.
- [Selenium Integration Test](https://github.com/stevepentler/IdeaBox/blob/master/test/integration/create_idea_test.rb): This isn't pretty, but I was excited to get Selenium working. I had trouble selecting specific elements.

### Attach a screenshot or paste the output from your terminal of the result of your test-suite running.

ideaBox ⚡ rake

Run options: --seed 50462

###### Running:

**************

Fabulous run in 14.942947s, 0.9369 runs/s, 4.3499 assertions/s.

14 runs, 65 assertions, 0 failures, 0 errors, 0 skips


### Provide a link to an example, if you have one, of a test that covers an 'edge case' or 'unhappy path'

- [Missing Validations](https://github.com/stevepentler/IdeaBox/blob/master/test/controllers/ideas_controller_test.rb#L53)

-----

# Instructor

156

### Data Model

(5 points total.)

### User Flows

#### Viewing ideas

(10 points total.)

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

### Extensions

#### Inline idea editing

(8 additional points.)

- 2 for clicking out not working

## Instructor Evaluation Points

### Specification Adherence

* **10 points**: The application consists of one page with all of the major functionality being provided by jQuery. There is no use of `format.js` in Rails. There is no use of unobstrusive JavaScript. There are no front-end frameworks used in the application. No approach was taken that is counter to the spirit of the project and its learning goals. There are no features missing from above that make the application feel incomplete or hard to use.

### User Interface

* **3 points** - The application has many strong pages/interactions, but a few holes in lesser-used functionality.

-2 for inline click out

### Testing

* **10 points** - Project has a running test suite that exercises the application at multiple levels including JavaScript tests.

### Ruby and Rails Quality

* **10 points** - Developer is able to craft Rails features that make smart use of Ruby, follow the principles of MVC, and push business logic down where it belongs. There _zero_ instances where an instructor would recommend taking a different approach. Developer writes code that is exceptionally clear and well-factored. Application is expertly divided into logical components each with a clear, single responsibility.

### JavaScript Style

* **10 points** - Application has exceptionally well-factored code with little or no duplication and all components separated out into logical components. There _zero_ instances where an instructor would recommend taking a different approach.

### Workflow

* **10 points** - The developer effectively uses Git branches and many small, atomic commits that document the evolution of their application.
