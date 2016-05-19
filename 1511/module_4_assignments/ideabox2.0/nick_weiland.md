# Ideabox 2.0 Submission Form
[Project Spec](https://github.com/turingschool/curriculum/blob/master/source/projects/revenge_of_idea_box.markdown)

* Fork this repo, if you haven't already and check out a branch
* Use this README as a template to create a file in this folder with your name as the title.
* Submit a pull request
* Pro Tip: You can use [recordit.co](http://recordit.co/) to record interaction gifs.
* Secondary Pro Tip: [Here's how to link to specific line number(s) in Github](http://stackoverflow.com/questions/23821235/how-to-link-to-specific-line-number-on-github)
* Tertiary Pro Tip: You can re-use some of these things in your portfolio/resume

------

# Basics

### Link to the Github Repository for the Project
[Repo](https://github.com/weilandia/idea_box.git)

### Link to the Deployed Application
[Prod](https://ideaboxsinatra.herokuapp.com/)

### Link to Your Commits in the Github Repository for the Project
[Commits](https://github.com/weilandia/idea_box/commits)

### Provide a Screenshot of your Application
![ideabox](images/weiland_ideabox.png)

## Completion

### Were you able to complete the base functionality?
* Searching isn't great.
* Testing :(

### Which extensions, if any, did you complete?
* Built with Sinatra
* Used MongoDB

### Attach a .gif, or images of any extensions work being used on the site.

# Code Quality

### Link to a specific block of your code on Github that you are proud of
[application.rb](https://github.com/weilandia/idea_box/blob/master/application.rb)
* Why were you proud of this piece of code?
  * Piecing together every component of the app was super fun. I learned a lot about how Rails works and Rack.

[routes.rake](https://github.com/weilandia/idea_box/blob/master/lib/tasks/routes.rake)
* This was cool.

### Link to a specific block of your code on Github that you feel not great about
[global.js](https://github.com/weilandia/idea_box/blob/master/app/assets/javascripts/global.js)
* Why do you feel not awesome about the code? What challenges did you face trying to write/refactor it?
  * I tried to inject the html with $.load(), but that didn't work.  I'd like to use some sort of template so I don't have to change this in two places.

### Attach a screenshot or paste the output from your terminal of the result of your test-suite running.
```
idea_box ✈︎ rspec
..........

Finished in 40.43 seconds (files took 2.5 seconds to load)
10 examples, 0 failures
```
Boom.

### Provide a link to an example, if you have one, of a test that covers an 'edge case' or 'unhappy path'

-----

### Please feel free to ask any other questions or make any other statements below!

# Instructor

171/150

### Data Model

(5 points total.)

### User Flows

#### Viewing ideas

(5 points total.)

Missing trucation.

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

#### Sorting

(10 additional points.)

#### Student Directed Extension

(10 * 2 additional points.)

MongoDB on backend
Sinatra on backend

## Instructor Evaluation Points

### Specification Adherence

* **10 points**:

### User Interface

* **5 points** - The application is pleasant, logical, and easy to use. There no holes in functionality and the application stands on it own to be used by the instructor _without_ guidance from the developer.

### Testing

* **10 points** - Project has a running test suite that exercises the application at multiple levels including JavaScript tests.

### SINATRA Quality

* **10 points** - Developer is able to craft Rails features that make smart use of Ruby, follow the principles of MVC, and push business logic down where it belongs. There _zero_ instances where an instructor would recommend taking a different approach. Developer writes code that is exceptionally clear and well-factored. Application is expertly divided into logical components each with a clear, single responsibility.

### JavaScript Style

* **8 points** - Application is thoughtfully put together with some duplication and no major bugs. Developer can speak to choices made in the code and knows what every line of code is doing.

### Workflow

* **8 points** - The developer makes a series of small, atomic commits that document the evolution of their application. There are no formatting issues in the code base.
