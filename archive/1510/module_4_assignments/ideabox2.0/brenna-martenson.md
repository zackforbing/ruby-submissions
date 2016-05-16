# Ideabox 2.0 Submission Form
[Project Spec](https://github.com/turingschool/curriculum/blob/master/source/projects/revenge_of_idea_box.markdown)

------

### [Github Repository](https://github.com/martensonbj/ideabox)

### [Deployed Application](http://idea-bucket.herokuapp.com/)

### [Github Commits](https://github.com/martensonbj/ideabox/commits/master)

### Provide a Screenshot of your Application
![Imgur](http://i.imgur.com/ZHTW0c2.png?1)

## Completion

### Completion of base functionality
Base functionality is complete.

### Which extensions, if any, did you complete?
Sorting works but only when you reload the page and only in one direction.

### Attach a .gif, or images of any extensions work being used on the site.
![RecordIt](http://g.recordit.co/e45OLJPcq9.gif)
# Code Quality

### Link to a specific block of your code on Github that you are proud of
[Filter Functionality](https://github.com/martensonbj/ideabox/blob/master/app/assets/javascripts/search.js#L1-L19)  
This was a really satisfying piece of functionality to complete. It helped me get a better understanding of how to manipulate jQuery objects and I was able to apply what I learned to other parts of the app.

![RecordIt](http://g.recordit.co/9r4PxjaTeN.gif)

### Link to a specific block of your code on Github that you feel not great about
[Quality Change](https://github.com/martensonbj/ideabox/blob/master/app/assets/javascripts/increase_quality.js#L1-L7)  
  I'm trying to make an effort to avoid if-else statements. This was a particularly challenging piece of the project and I would benefit from spending more time refactoring how this is implemented.

### Attach a screenshot or paste the output from your terminal of the result of your test-suite running.

`$ rspec
............
Finished in 14.19 seconds (files took 3.27 seconds to load)
12 examples, 0 failures`

### Provide a link to an example, if you have one, of a test that covers an 'edge case' or 'unhappy path'
[Model Validations](https://github.com/martensonbj/ideabox/blob/master/spec/models/idea_spec.rb#L15-L25)  
An idea isn't very useful without a title and a description. This test makes sure ideas aren't created without those attributes.

-----

# Instructor Feedback

146

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

* **8 points** - The developer makes a series of small, atomic commits that document the evolution of their application. There are no formatting issues in the code base.
