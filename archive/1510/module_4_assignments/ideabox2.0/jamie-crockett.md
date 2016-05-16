# Ideabox 2.0 Submission Form
[Project Spec](https://github.com/turingschool/curriculum/blob/master/source/projects/revenge_of_idea_box.markdown)

# Basics

### Link to the Github Repository for the Project
[My Repo](https://github.com/jecrockett/idea_box)

### Link to the Deployed Application
[Deployed App](https://jec-idea-box.herokuapp.com/)

### Link to Your Commits in the Github Repository for the Project
[My Commits](https://github.com/jecrockett/idea_box/commits/master)

### Provide a Screenshot of your Application
![ideabox](images/jamie_crockett_ideabox.png)

## Completion

### Were you able to complete the base functionality?
* Yes

### Which extensions, if any, did you complete?
* I completed quality sorting and inline editing.

### Attach a .gif, or images of any extensions work being used on the site.
Inline Editing
![](http://g.recordit.co/kd62FrmCww.gif)

Sorting
![](http://g.recordit.co/he0CiLOGKz.gif)

# Code Quality

### Link to a specific block of your code on Github that you are proud of
[Code](https://github.com/jecrockett/idea_box/blob/14ff893de16818cd193154ae67ffc1e1c1138b84/app/assets/javascripts/sort_quality.js#L14-L30)

I thought it was clever to have an if else that determines whether the set of ideas actually needs to be sorted or if it simply can be reversed. If it's already been sorted and no new ideas have been added, the logic simply flips the ideas rather than performing any analysis.

### Link to a specific block of your code on Github that you feel not great about
[Code](https://github.com/jecrockett/idea_box/blob/14ff893de16818cd193154ae67ffc1e1c1138b84/app/assets/javascripts/update_idea_quality.js#L1-L12)

I was proud that I was able to refactor this from two separate increase/decrease functions into one, but it still feels like I'm assigning too many variables and in general too much is going on. I'm still struggling to think of JS in an OO way and give small responsibilities to objects. I'm just throwing a bunch of variables into a magic machine that gives me what I want.

### Attach a screenshot or paste the output from your terminal of the result of your test-suite running.
```
$ rspec
.................

Finished in 9.08 seconds (files took 2.12 seconds to load)
17 examples, 0 failures
```

### Provide a link to an example, if you have one, of a test that covers an 'edge case' or 'unhappy path'

-----

### Please feel free to ask any other questions or make any other statements below!
Really enjoyed this project. Made me feel capable at JS, but also open my eyes to how much I don't understand and how far I have to go in terms of 'thinking' in the language.

-------

#Instructor Feedback

162

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

(16 points total.)

Issue with: If the user reloads the page, their edits will be reflected. (4 points, mandatory for specification adherence)

#### Idea Filtering and Searching

(15 points total.)

### Extensions

#### Inline idea editing

(10 additional points.)

When a user clicks the title or idea of an idea in the list, that text should become an editable text field, pre-populated with the existing idea title or body. The user should be able to "commit" their changes by pressing "Enter/Return" or by clicking outside of the text field.

#### Sorting

(10 additional points.)

When viewing the ideas list, the user should have the option to sort ideas by Quality. The default sort should be descending ("genius" → "plausible" → "swill"), and clicking the sort a second time should reverse it. The Idea list should be sorted client-side without reloading the page.

## Instructor Evaluation Points

### Specification Adherence

* **10 points**: The application consists of one page with all of the major functionality being provided by jQuery. There is no use of `format.js` in Rails. There is no use of unobstrusive JavaScript. There are no front-end frameworks used in the application. No approach was taken that is counter to the spirit of the project and its learning goals. There are no features missing from above that make the application feel incomplete or hard to use.

### User Interface

* **3 points** - The application has many strong pages/interactions, but a few holes in lesser-used functionality.

### Testing

* **10 points** - Project has a running test suite that exercises the application at multiple levels including JavaScript tests.

### Ruby and Rails Quality

* **8 points** - Developer solves problems with a balance between conciseness and clarity and often extracts logical components. Developer can speak to choices made in the code and knows what every line of code is doing.

### JavaScript Style

* **8 points** - Application is thoughtfully put together with some duplication and no major bugs. Developer can speak to choices made in the code and knows what every line of code is doing.

### Workflow

* **10 points** - The developer effectively uses Git branches and many small, atomic commits that document the evolution of their application.
