# Gurusundesh Khalsa
# Ideabox 2.0 Submission Form
[Project Spec](https://github.com/turingschool/curriculum/blob/master/source/projects/revenge_of_idea_box.markdown)

------

# Basics

### Link to the Github Repository for the Project
[Idea Box Repo](https://github.com/GKhalsa/idea_box)

### Link to the Deployed Application
[Heroku](http://idea-boxer.herokuapp.com/)

### Link to Your Commits in the Github Repository for the Project
[Commits](https://github.com/GKhalsa/idea_box/commits/master)

### Provide a Screenshot of your Application
[Idea Box Screenshot](http://i.imgur.com/37ysQpn.png)

## Completion

### Were you able to complete the base functionality?
* Did not do truncating of body

### Which extensions, if any, did you complete?
* Tagging

### Attach a .gif, or images of any extensions work being used on the site.
![](http://g.recordit.co/uCZxF9RqCM.gif)
# Code Quality

### Link to a specific block of your code on Github that you are proud of
* Having lost the versatility of active record relationships within javascript. Using this bit of code in the controller which added relationships to the JSON object being returned helped out while doing the tagging extension.

[adding relationships](https://github.com/GKhalsa/idea_box/blob/77a1816e6e43e9c707d3bb856acff83514703193/app/controllers/api/v1/ideas_controller.rb#L4)

* We lose the method uniq in javascript, but I thought this bit of code that I did was to the point and very re-usable.

[javascript uniq](https://github.com/GKhalsa/idea_box/blob/77a1816e6e43e9c707d3bb856acff83514703193/app/assets/javascripts/ideaManipulation.js#L43-L48)

### Data Model
(5 points total.)
### User Flows
#### Viewing ideas
(5 Points - doesn't truncate)
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
#### Tagging
(20 additional points.)

## Instructor Evaluation Points
### Specification Adherence
* **10 points**: The application consists of one page with all of the major functionality being provided by jQuery. There is no use of `format.js` in Rails. There is no use of unobstrusive JavaScript. There are no front-end frameworks used in the application. No approach was taken that is counter to the spirit of the project and its learning goals. There are no features missing from above that make the application feel incomplete or hard to use.
### User Interface
* **5 points** - The application is pleasant, logical, and easy to use. There no holes in functionality and the application stands on it own to be used by the instructor _without_ guidance from the developer
### Testing
* **0 points** - There is little or no evidence of testing in this application.
### Ruby and Rails Quality
* **10 points** - Developer is able to craft Rails features that make smart use of Ruby, follow the principles of MVC, and push business logic down where it belongs. There _zero_ instances where an instructor would recommend taking a different approach. Developer writes code that is exceptionally clear and well-factored. Application is expertly divided into logical components each with a clear, single responsibility.

### JavaScript Style
* **8 points** - Application is thoughtfully put together with some duplication and no major bugs. Developer can speak to choices made in the code and knows what every line of code is doing.

### Workflow
* **10 points** - The developer effectively uses Git branches and many small, atomic commits that document the evolution of their application.

### Final Score: 153/150

