# idea_box

[Github Repo](https://github.com/afg419/idea_box/new/master?readme=1)  
[Production Site](https://ag-idea-box.herokuapp.com/)  
[List of commits on Github](https://github.com/afg419/idea_box/commits/master)    

![this wouldve been a screen shot of the app if you had internet.](http://i.imgur.com/T0ZkHq9.png)  


###Completion  
Completes all basic functionality expectations.  
![Sorting by quality extension](http://recordit.co/Zqq8HHoAse.gif)  

###Code Quality  
Some sweet code: [This allows for dynamic filtering and sorting of ideas based on document state](https://github.com/afg419/idea_box/blob/0d723b8aad80a707d154d5ce2c2df273e6caba47/app/assets/javascripts/ideas.js.es6#L53-L59)  
Some ugly code: [Couldn't get all JS classes to see the ideas object without holding it as an attribute on the `document`](https://github.com/afg419/idea_box/blob/0d723b8aad80a707d154d5ce2c2df273e6caba47/app/assets/javascripts/ideas.js.es6#L1-L7)  
Test Suite:    
![this wouldve been a screen shot of the running tests if you had internet.](http://i.imgur.com/htfAyyw.png)    
[Unhappy Path Testing](https://github.com/afg419/idea_box/blob/0d723b8aad80a707d154d5ce2c2df273e6caba47/spec/controllers/idea_voting_ideas_controller_spec.rb#L1-L55)

---
#Instructor Feedback

168

For storage of ideas - look at things like localStorage or other techniques of keeping a global ideas repository.

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

* **10 points** - Developer is able to craft Rails features that make smart use of Ruby, follow the principles of MVC, and push business logic down where it belongs. There _zero_ instances where an instructor would recommend taking a different approach. Developer writes code that is exceptionally clear and well-factored. Application is expertly divided into logical components each with a clear, single responsibility.

### JavaScript Style

* **8 points** - Application is thoughtfully put together with some duplication and no major bugs. Developer can speak to choices made in the code and knows what every line of code is doing.

### Workflow

* **10 points** - The developer effectively uses Git branches and many small, atomic commits that document the evolution of their application.
