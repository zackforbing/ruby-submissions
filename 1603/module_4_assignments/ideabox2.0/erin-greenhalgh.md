#Ideabox 2.0 Submission Form

* [Project Spec](https://github.com/turingschool/curriculum/blob/master/source/projects/revenge_of_idea_box.markdown)
* [GitHub Repo](https://github.com/ErinGreenhalgh/ideabox)
* [Deployed Application](http://ideasfordays.herokuapp.com/)
* [My Commits](https://github.com/ErinGreenhalgh/ideabox/commits/master)

###My Application

![IdeaBox](http://i.imgur.com/Ibb8VEh.png)

###Completion

Base functionality is complete, with the exception of truncating the idea to the closest 100 words.
I did not complete any extensions.

###Code Quality

[Code I am proud of](https://github.com/ErinGreenhalgh/ideabox/blob/cce5a6fc8b173740c6b04e3d9cc307b8a6262349/app/assets/javascripts/update_quality.js#L3-L35)
####Why were you proud of this piece of code?
I was happy with figuring out how to send the parameters of the quality to the ajax call. It was conceptually challenging for me to figure out how this should work, since the quality has to be sent to the ajax call but it can't be grabbed from the page. It was new to me to store the logic of which quality to send to the ajax call in the javascript instead of in the model, as was my first instinct. This is not super DRY but I was happy to figure this part out.

[Code I don't feel great about](https://github.com/ErinGreenhalgh/ideabox/blob/cce5a6fc8b173740c6b04e3d9cc307b8a6262349/app/assets/javascripts/ideas.js#L51-L91)

####Why do you feel not awesome about the code? What challenges did you face trying to write/refactor it?
This code is not DRY at all and I know it could be refactored. I would like to have one helper function that toggles the 'contenteditable' class on whatever attribute you pass to it, instead of having essentially the same function with on different parameter. In the same way, the code for updating the title and body is nearly identical, so it would be nice to just have one function that I could pass 'title' or
'body' to. I did not refactor this code because I ran out of time, and wanted to make sure that I got all the base functionality completed first.

###Test Suite
![Test Suite](http://i.imgur.com/cH2bcKh.png)

###Edge Case/Sad Path Test
Yikes I don't really have any sad path tests :/

# Instructor Feedback

113/150

*** Update grade on fixes if amended - see notes below ***

### Data Model

(5 points total.)

### User Flows

#### Viewing ideas

5 points

***No truncation***

#### Adding a new idea

(15 points total.)

#### Deleting an existing idea

(15 points total.)

#### Changing the quality of an idea

(15 points total.)

#### Editing an existing idea

0 points

*** If you want to get this fixed before Wednesday of next week - DM it to me with a test added for it and we'll amend ***

* When a user clicks the title or body of an idea in the list, that text should become an editable text field, pre-populated with the existing idea title or body. (8 points)
* Clicking this link should _not_ take the user to a separate "edit" page for the given
  idea. (4 points, mandatory for specification adherence)
*  The user should be able to "commit" their changes by pressing "Enter/Return" or by clicking outside of the text field. (4 points)
* If the user reloads the page, their edits will be reflected. (4 points, mandatory for specification adherence)

#### Idea Filtering and Searching

(15 points total.)

## Instructor Evaluation Points

### Specification Adherence

* **10 points**

### User Interface

* **5 points** - The application is pleasant, logical, and easy to use. There no holes in functionality and the application stands on it own to be used by the instructor _without_ guidance from the developer.

### Testing

*** Amend testing score based on testing done for fix ***

* **5 points** - Project has sporadic use of tests and multiple levels. Not all controller actions are tested. There are little or no attempts at integration testing.

### Ruby and Rails Quality

* **10 points** - Developer is able to craft Rails features that make smart use of Ruby, follow the principles of MVC, and push business logic down where it belongs. There _zero_ instances where an instructor would recommend taking a different approach. Developer writes code that is exceptionally clear and well-factored. Application is expertly divided into logical components each with a clear, single responsibility.

### JavaScript Style

* **8 points** - Application is thoughtfully put together with some duplication and no major bugs. Developer can speak to choices made in the code and knows what every line of code is doing.

### Workflow

* **10 points** - The developer effectively uses Git branches and many small, atomic commits that document the evolution of their application.
