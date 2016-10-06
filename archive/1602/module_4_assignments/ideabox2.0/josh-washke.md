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
[Your Repo](https://github.com/jwashke/idea-box)

### Link to the Deployed Application
[Your Application](http://ideas-box.herokuapp.com/)

### Link to Your Commits in the Github Repository for the Project
[Your Commits](https://github.com/jwashke/idea-box/commits/master)

### Provide a Screenshot of your Application
![spacejam](https://s3-us-west-2.amazonaws.com/rails-misc-pictures/Screen+Shot+2016-06-30+at+10.47.45+AM.png)

## Completion

### Were you able to complete the base functionality?

* Yes

### Which extensions, if any, did you complete?

* Tagging, and sorting by quality

### Attach a .gif, or images of any extensions work being used on the site.

![GIF](http://g.recordit.co/8HuLPvgaZe.gif)

# Code Quality

### Link to a specific block of your code on Github that you are proud of
* Why were you proud of this piece of code?
```
app/assets/javascripts/handlers.js
```
```ruby
delegateClick: function(event) {
  var target = event.target;
  var id = target.id
  if (target.className.includes('deleteButton')) {
    this.deleteIdea(id);
  } else if (target.className.includes('thumbsUpButton')) {
    this.thumbsUpIdea(id);
  } else if (target.className.includes('thumbsDownButton')) {
    this.thumbsDownIdea(id);
  } else if (target.className.includes('ideaTitle')) {
    $(target).attr('contenteditable', 'true');
  } else if (target.className.includes('ideaBody')) {
    $(target).attr('contenteditable', 'true');
  }
},
```

Proud of this because originally I was attaching multiple event listeners to every idea on the page. When I was able to rewrite it to a single event listener for the entire block of ideas that depends on the event target to delegate the click event i was pretty excited.
### Link to a specific block of your code on Github that you feel not great about
* Why do you feel not awesome about the code? What challenges did you face trying to write/refactor it?

```
app/assets/javascripts/idea_service.js
```
```ruby
getIdeas: function() {
  $.getJSON("/api/v1/ideas").then(function(response) {
    var ideas = response.ideas
    ideas.forEach(function(idea) {
      if (idea.body.length > 100)
        idea.body = idea.body.substring(0, 100).split(" ").slice(0, -1).join(" ") + "...";
      var tags = idea.tags.map(function(tag) {
        var containsTag = tagList.tags.filter(function(oldTag) {
          return tag.name === oldTag.name;
        }).length > 0
        var newTag = new Tag(tag.name)
        if (!containsTag) {
          tagList.tags.push(newTag)
        }
        return newTag;
      })
      var newIdea = new Idea(idea.id, idea.title, idea.body, idea.quality, tags)
      ideaList.ideas.push(newIdea)
    });
    view.drawIdeas();
  });
},
```
its ugly and has too much going on. I tried to refactor but kept just breaking everything.

### Attach a screenshot or paste the output from your terminal of the result of your test-suite running.
```
Finished in 0.48944 seconds (files took 1.59 seconds to load)
27 examples, 0 failures, 1 pending
```
### Provide a link to an example, if you have one, of a test that covers an 'edge case' or 'unhappy path'
```
spec/models/idea_spec.rb
```
```ruby
context "with quality genius" do
  it "does not change the quality" do
    idea = create(:genius_idea)
    idea.cycle_quality_up
    expect(idea.quality).to eq("genius")
  end
end
```
-----


​
### Data Model
​
(5 points total.)
​
We'll be primarily working with _Idea_ objects.
​
* An Idea has a _title_, a _body_, and a _quality_. (1 point)
  * _title_ and _body_ are free-form strings.
* _quality_ can be represented however you feel best in the database,
  but in the user interface it should manifest as the options "genius", "plausible", and "swill" (2 points)
* By default, the idea's "quality" should default to the lowest setting (i.e. "swill"). (2 points)
​
### User Flows
​
#### Viewing ideas
​
(10 points total.)
​
On the application's root, the user should:
​
* See a list of all existing ideas, including the title, body, and quality for each idea. (2 points, mandatory for specification adherence)
* Idea bodies longer than 100 characters should be truncated to the nearest word. (5 points)
* Ideas should appear in descending chronological order (with the most recently created
  idea at the top). (3 points)
​
#### Adding a new idea
​
(15 points total.)
​
On the application's main page, a user should:
​
* See two text boxes for entering the "Title" and "Body" for a new idea,
  and a "Save" button for committing that idea. (3 points, mandatory for specification adherence)
​
When a user clicks "Save":
​
* A new idea with the provided title and body should appear in the idea list. (5 points, mandatory for specification adherence)
* The text fields should be cleared and ready to accept a new idea. (2 points)
* The page _should not_ reload. (3 points, mandatory for specification adherence)
* The idea should be committed to the database. It should still be present upon reloading the page. (2 points, mandatory for specification adherence)
​
#### Deleting an existing idea
​
(15 points total.)
​
When viewing the idea list:
​
* Each idea in the list should have a link or button to "Delete" (or 𝗫, etc). (2 points)
* Upon clicking "Delete", the appropriate idea should be removed from the list (5 points, mandatory for specification adherence).
* The page _should not_ reload when an idea is deleted. (5 points, mandatory for specification adherence)
* The idea should be removed from the database. It should not re-appear on next page load. (3 points, mandatory for specification adherence)
​
#### Changing the quality of an idea
​
(15 points total.)
​
As we said above, ideas should start out as "swill." In order to change the recorded quality of an idea, the user will interact with it from the idea list.
​
* Each idea in the list should include a "thumbs up" and "thumbs down" button. (3 points)
* Clicking thumbs up on the idea should increase its quality one notch ("swill" → "plausible",
  "plausible" → "genius"). (4 points)
* Clicking thumbs down on the idea should decrease its quality one notch ("genius" → "plausible",
  "plausible" → "swill"). (4 points)
* Incrementing a "genius" idea or decrementing a "swill" idea should have no effect. (4 points)
​
#### Editing an existing idea
​
(20 points total.)
​
* When a user clicks the title or body of an idea in the list, that text should become an editable text field, pre-populated with the existing idea title or body. (8 points)
* Clicking this link should _not_ take the user to a separate "edit" page for the given
  idea. (4 points, mandatory for specification adherence)
*  The user should be able to "commit" their changes by pressing "Enter/Return" or by clicking outside of the text field. (4 points)
* If the user reloads the page, their edits will be reflected. (4 points, mandatory for specification adherence)
​
#### Idea Filtering and Searching
​
(15 points total.)
​
We'd like our users to be able to easily find specific ideas they already created, so
let's provide them with a filtering interface on the idea list.
​
* At the top of the idea list, include a text field labeled "Search". (3 points)
* As a user types in the search box, the list of ideas should filter in real time to only display ideas whose title or body include the user's text. The page _should not_ reload. (6 points)
* Clearing the search box should restore all the ideas to the list. (6 points)
​
### Extensions
​
Extensions are a great way to earn additional points beyond the 150 available in this project. That said, awarding points for delivering a given extension is up to the instructor, who may only award partial points depending on the quality of the implementation. The points listed below represent the maximum number of points. Extensions can _not_ be done after the fact without instructor permission in advance.
​
#### Tagging
​
(20 additional points.)
​
Add an optional third text field upon idea creation for "Tags". Tags should be a comma-separated list of short text tags, and should be processed on the server such that any existing tags are re-used, and any new ones are created. Once there are tags to display, a list of existing tags should appear at the top of the idea list. Clicking one of these tags should show only ideas that include it. When viewing ideas filtered by tag, be sure to include a link to take the user back to "All Ideas". This filtering could be implemented either as a separate page or via javascript within the same interface.
​
#### Sorting
​
(10 additional points.)
​
When viewing the ideas list, the user should have the option to sort ideas by Quality. The default sort should be descending ("genius" → "plausible" → "swill"), and clicking the sort a second time should reverse it. The Idea list should be sorted client-side without reloading the page.
​

## Instructor Evaluation Points
​
### Specification Adherence
​
* **10 points**: The application consists of one page with all of the major functionality being provided by jQuery. There is no use of `format.js` in Rails. There is no use of unobstrusive JavaScript. There are no front-end frameworks used in the application. No approach was taken that is counter to the spirit of the project and its learning goals. There are no features missing from above that make the application feel incomplete or hard to use.
​
### User Interface
​
* **5 points** - The application is pleasant, logical, and easy to use. There no holes in functionality and the application stands on it 
​
### Testing
​
* **9 points** - Project has a running test suite that tests and multiple levels but fails to cover some features. All controller actions are covered by tests. The application makes some use of integration testing.

​
### Ruby and Rails Quality
​
* **10 points** - Developer is able to craft Rails features that make smart use of Ruby, follow the principles of MVC, and push business logic down where it belongs. There _zero_ instances where an instructor would recommend taking a different approach. Developer writes code that is exceptionally clear and well-factored. Application is expertly divided into logical components each with a clear, single responsibility.

​
### JavaScript Style
​
* **9 points** - Application has exceptionally well-factored code with little or no duplication and all components separated out into logical components. There _zero_ instances where an instructor would recommend taking a different approach.

​
### Workflow
​
* **10 points** - The developer effectively uses Git branches and many small, atomic commits that document the evolution of their application.

### total score: 178
