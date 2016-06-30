# Basics

### Link to the Github Repository for the Project
[JP - Idea Box - Github](https://github.com/jwperry/ruby-submissions)

### Link to the Deployed Application
[JP - Idea Box - Heroku](https://jp-turing-idea-box.herokuapp.com/)

### Link to Your Commits in the Github Repository for the Project
[Commits](https://github.com/jwperry/revenge_of_idea_box/commits/master)

### Provide a Screenshot of your Application
![Screenshot](http://i.imgur.com/qkWPPQu.png)

# Completion

### Were you able to complete the base functionality?
* Yes, base functionality is all complete.

### Which extensions, if any, did you complete?
* I completed the 20 point tagging extension.
* I inadvertently completed most of of the in-line editing extension. I set up in-line edits triggered by clicking on the edit button just because it was a fun challenge, but you have to click 'save' to keep the changes.

### Attach a .gif, or images of any extensions work being used on the site.
![Screenshot of Tagging](http://i.imgur.com/ESh57cd.png)
![Screenshot of In-Line Edits](http://i.imgur.com/vGJAptz.png)

# Code Quality

### Link to a specific block of your code on Github that you are proud of
* Why were you proud of this piece of code?

[Using .call to control state](https://github.com/jwperry/revenge_of_idea_box/blob/062285ab59f915e3006e264efb6023197136b6ac/app/assets/javascripts/tag-filter.js#L16-L31)
  * This particular piece of code taught me more about JavaScript than any other. I got stuck for a really long time trying to reference what I wanted through various functions, and this is really what made me understand the use of methods like .call(), .apply(), and .bind().

### Link to a specific block of your code on Github that you feel not great about
* Why do you feel not awesome about the code? What challenges did you face trying to write/refactor it?

[Constructing HTML manually](https://github.com/jwperry/revenge_of_idea_box/blob/062285ab59f915e3006e264efb6023197136b6ac/app/assets/javascripts/list-ideas.js.erb#L48-L72)
  * I spent a lot of time trying to figure out the best way to construct/insert some HTML, and I'm sure this is NOT it. I have no idea how to refactor it in the context of my program. This version already IS refactored as it was originally one huge, hideous block until I broke it out into several methods.

### Attach a screenshot or paste the output from your terminal of the result of your test-suite running.

$ rspec
................

Finished in 2.4 seconds (files took 2.59 seconds to load)
16 examples, 0 failures

Coverage report generated for RSpec to /Users/Jet/turing/4module/revenge_of_idea_box/coverage. 56 / 56 LOC (100.0%) covered.

### Provide a link to an example, if you have one, of a test that covers an 'edge case' or 'unhappy path'
[Sad path test](https://github.com/jwperry/revenge_of_idea_box/blob/062285ab59f915e3006e264efb6023197136b6ac/spec/models/idea_spec.rb#L13-L31)
  * Here is an example of some model edge-case testing, making sure new ideas are created with all the required attributes.

----
#Instructor Feedback

176

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

(10 additional points.)

When a user clicks the title or idea of an idea in the list, that text should become an editable text field, pre-populated with the existing idea title or body. The user should be able to "commit" their changes by pressing "Enter/Return" or by clicking outside of the text field.

#### Tagging

(20 additional points.)

Add an optional third text field upon idea creation for "Tags". Tags should be a comma-separated list of short text tags, and should be processed on the server such that any existing tags are re-used, and any new ones are created. Once there are tags to display, a list of existing tags should appear at the top of the idea list. Clicking one of these tags should show only ideas that include it. When viewing ideas filtered by tag, be sure to include a link to take the user back to "All Ideas". This filtering could be implemented either as a separate page or via javascript within the same interface.

## Instructor Evaluation Points

### Specification Adherence

* **10 points**: The application consists of one page with all of the major functionality being provided by jQuery. There is no use of `format.js` in Rails. There is no use of unobstrusive JavaScript. There are no front-end frameworks used in the application. No approach was taken that is counter to the spirit of the project and its learning goals. There are no features missing from above that make the application feel incomplete or hard to use.

### User Interface

* **5 points** - The application is pleasant, logical, and easy to use. There no holes in functionality and the application stands on it own to be used by the instructor _without_ guidance from the developer.

### Testing

* **10 points** - Project has a running test suite that exercises the application at multiple levels including JavaScript tests.

### Ruby and Rails Quality

* **8 points** - Developer solves problems with a balance between conciseness and clarity and often extracts logical components. Developer can speak to choices made in the code and knows what every line of code is doing.

### JavaScript Style

* **8 points** - Application is thoughtfully put together with some duplication and no major bugs. Developer can speak to choices made in the code and knows what every line of code is doing.

### Workflow

* **10 points** - The developer effectively uses Git branches and many small, atomic commits that document the evolution of their application.
