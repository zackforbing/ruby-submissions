# Ideabox 2.0 Submission Form - Steven Olson

# Basics

### Link to the Github Repository for the Project
[My Repo](https://github.com/SteveOscar/idea_box)

### Link to the Deployed Application
[My Application](https://idea-box-of-dreams.herokuapp.com/)

### Link to Your Commits in the Github Repository for the Project
[My Commits](https://github.com/SteveOscar/idea_box/commits/master)

### Provide a Screenshot of your Application
![spacejam](http://i.imgur.com/vzbBwNH.png)

## Completion

### Were you able to complete the base functionality?

Yes

### Which extensions, if any, did you complete?

I completed the inline editing extension, allowing a user to click on a title or body field, edit it, and save changes by clicking outside of the field or hitting the 'enter' button. I also did some Selenium JS, testing which is not technically an extension, but is in my head.

### Attach a .gif, or images of any extensions work being used on the site.

Functionality with inline editing:

![](http://g.recordit.co/8KbeHPWaoW.gif)


# Code Quality

### Link to a specific block of your code on Github that you are proud of

[Link](https://github.com/SteveOscar/idea_box/blob/master/app/assets/javascripts/edit_inline.js)

I'm happy with this code because, although the methods aren't beautifully concise, I learned a lot in writing these methods for editing ideas inline. I had originally created this functionality with dedicated buttons and separate fields, so it was interesting to convert that to a much more compact UX. I was able to to extract the primary steps out into separate functions, and learned some new event listeners that will be useful in the future.

### Link to a specific block of your code on Github that you feel not great about

[Link](https://github.com/SteveOscar/idea_box/blob/master/app/assets/javascripts/ideas.js)

I don't like this giant block of html for rendering a new idea element on the page. I couldn't find a satisfying way to rearrange line breaks without breaking the code.

### Attach a screenshot or paste the output from your terminal of the result of your test-suite running.

```
.............................................

Finished in 10.184635s, 1.1782 runs/s, 2.5529 assertions/s.  


12 runs, 26 assertions, 0 failures, 0 errors, 0 skips
Coverage report generated for MiniTest to   
/Users/stevenolson/Turing/projects/idea_box/idea_box/coverage. 26 / 26 LOC (100.0%) covered.
```

### Provide a link to an example, if you have one, of a test that covers an 'edge case' or 'unhappy path'

[Create an idea with missing attributes ](https://github.com/SteveOscar/idea_box/blob/master/test/controllers/api/ideas_controller_test.rb)

# Instructor Feedback

155 (out of 150)

### Data Model

(5 points total.)

### User Flows

#### Viewing ideas

(5 points total.)

No truncation

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

Extensions are a great way to earn additional points beyond the 150 available in this project. That said, awarding points for delivering a given extension is up to the instructor, who may only award partial points depending on the quality of the implementation. The points listed below represent the maximum number of points. Extensions can _not_ be done after the fact without instructor permission in advance.

#### Inline idea editing

(10 additional points.)

When a user clicks the title or idea of an idea in the list, that text should become an editable text field, pre-populated with the existing idea title or body. The user should be able to "commit" their changes by pressing "Enter/Return" or by clicking outside of the text field.

## Instructor Evaluation Points

### Specification Adherence

* **10 points**: The application consists of one page with all of the major functionality being provided by jQuery. There is no use of `format.js` in Rails. There is no use of unobstrusive JavaScript. There are no front-end frameworks used in the application. No approach was taken that is counter to the spirit of the project and its learning goals. There are no features missing from above that make the application feel incomplete or hard to use.

### User Interface

* **5 points** - The application is pleasant, logical, and easy to use. There no holes in functionality and the application stands on it own to be used by the instructor _without_ guidance from the developer.

### Testing

* **10 points** - Project has a running test suite that exercises the application at multiple levels including JavaScript tests.

### Ruby and Rails Quality

* **10 points** - Developer is able to craft Rails features that make smart use of Ruby, follow the principles of MVC, and push business logic down where it belongs. There _zero_ instances where an instructor would recommend taking a different approach. Developer writes code that is exceptionally clear and well-factored. Application is expertly divided into logical components each with a clear, single responsibility.

### JavaScript Style

* **8 points** - Application is thoughtfully put together with some duplication and no major bugs. Developer can speak to choices made in the code and knows what every line of code is doing.

### Workflow

* **10 points** - The developer effectively uses Git branches and many small, atomic commits that document the evolution of their application.
