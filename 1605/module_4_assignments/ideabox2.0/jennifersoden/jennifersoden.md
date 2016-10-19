# Ideabox 2.0 Submission Form
[Project Spec](https://github.com/turingschool/curriculum/blob/master/source/projects/revenge_of_idea_box.markdown)


------

# Basics

### Link to the Github Repository for the Project
[Your Repo](https://github.com/MsJennyGiraffe/idea_box)

### Link to the Deployed Application
[Your Application](http://buckets-of-ideas.herokuapp.com/)

### Link to Your Commits in the Github Repository for the Project
[Your Commits](https://github.com/MsJennyGiraffe/idea_box/commits/master)

### Provide a Screenshot of your Application
![spacejam](http://i67.tinypic.com/m125g.png)

## Completion

### Were you able to complete the base functionality?
No

* If not, list what functionality is missing.
Missing
* Body truncation for ideas
* Thumbs
* Search


### Which extensions, if any, did you complete?
None

### Attach a .gif, or images of any extensions work being used on the site.
N/A

# Code Quality

### Link to a specific block of your code on Github that you are proud of

https://github.com/MsJennyGiraffe/idea_box/blob/master/app/assets/javascripts/idea_index.js#L10

* Why were you proud of this piece of code?
  * I'm proud of this code because it is the result of the first time I tried to refactor code, and I think it turned out fairly clean. I was really afraid to break out a long method that wasn't named and was doing far too much, because it also included the ajax call, but I am happy with the way it turned out.

### Link to a specific block of your code on Github that you feel not great about

https://github.com/MsJennyGiraffe/idea_box/blob/master/app/assets/javascripts/idea_service.js#L40-64

* Why do you feel not awesome about the code? What challenges did you face trying to write/refactor it?

  * I don't like how repetitive it is, but I couldn't think of a way to change the idea title/body dynamically, and I send only one at a time. This is probably an issue with how I chose to the structure of the editable content, I'm sure there is a better way, and I'd love to look into it.

### Attach a screenshot or paste the output from your terminal of the result of your test-suite running.

Finished in 0.49334 seconds (files took 1.41 seconds to load)

7 examples, 0 failures

### Provide a link to an example, if you have one, of a test that covers an 'edge case' or 'unhappy path'

https://github.com/MsJennyGiraffe/idea_box/blob/master/spec/requests/api/v1/ideas_controller_spec.rb#L68-84

-----

### Please feel free to ask any other questions or make any other statements below!

### Data Model

(5 points total.)

### User Flows

#### Viewing ideas

(2/10 points total.)

On the application's root, the user should:


* Idea bodies longer than 100 characters should be truncated to the nearest word. (5 points)
* Ideas should appear in descending chronological order (with the most recently created
  idea at the top). (3 points)

#### Adding a new idea

(13/15 points total.)

* The text fields should be cleared and ready to accept a new idea. (2 points)

#### Deleting an existing idea

(15 points total.)

#### Changing the quality of an idea

(3/15 points total.)

As we said above, ideas should start out as "swill." In order to change the recorded quality of an idea, the user will interact with it from the idea list.


* Clicking thumbs up on the idea should increase its quality one notch ("swill" → "plausible",
  "plausible" → "genius"). (4 points)
* Clicking thumbs down on the idea should decrease its quality one notch ("genius" → "plausible",
  "plausible" → "swill"). (4 points)
* Incrementing a "genius" idea or decrementing a "swill" idea should have no effect. (4 points)

#### Editing an existing idea

(20 points total.)

#### Idea Filtering and Searching

(0/15 points total.)

We'd like our users to be able to easily find specific ideas they already created, so
let's provide them with a filtering interface on the idea list.

* At the top of the idea list, include a text field labeled "Search". (3 points)
* As a user types in the search box, the list of ideas should filter in real time to only display ideas whose title or body include the user's text. The page _should not_ reload. (6 points)
* Clearing the search box should restore all the ideas to the list. (6 points)

## Instructor Evaluation Points

### Specification Adherence

* **10 points**: The application consists of one page with all of the major functionality being provided by jQuery. There is no use of `format.js` in Rails. There is no use of unobstrusive JavaScript. There are no front-end frameworks used in the application. No approach was taken that is counter to the spirit of the project and its learning goals. There are no features missing from above that make the application feel incomplete or hard to use.

### User Interface

* **5 points** - The application is pleasant, logical, and easy to use. There no holes in functionality and the application stands on it own to be used by the instructor _without_ guidance from the developer.

### Testing

* **7 points** - Project has sporadic use of tests and multiple levels. Not all controller actions are tested. There are little or no attempts at integration testing.

### Ruby and Rails Quality

* **10 points** - Developer is able to craft Rails features that make smart use of Ruby, follow the principles of MVC, and push business logic down where it belongs. There _zero_ instances where an instructor would recommend taking a different approach. Developer writes code that is exceptionally clear and well-factored. Application is expertly divided into logical components each with a clear, single responsibility.

### JavaScript Style

* **8 points** - Application is thoughtfully put together with some duplication and no major bugs. Developer can speak to choices made in the code and knows what every line of code is doing.

### Workflow

* **10 points** - The developer effectively uses Git branches and many small, atomic commits that document the evolution of their application.
