# Ideabox 2.0 Submission Form

### Link to the Github Repository for the Project
[хранилище](github.com/jdliss/idea-box)

### Link to the Deployed Application
[Веб-сайт](https://ancient-waters-56609.herokuapp.com/)

### Link to Your Commits in the Github Repository for the Project
[обязательства](https://github.com/jdliss/idea-box/commits/master)

### Provide a Screenshot of your Application
![01110011 01100011 01110010 01100101 01100101 01101110 01110011 01101000 01101111 01110100](http://i.imgur.com/iS1vZ9w.png)

## Completion

### Were you able to complete the base functionality?
* truncation does not truncate on words

# Code Quality

### Link to a specific block of your code on Github that you are proud of
* [the voting logic](https://github.com/jdliss/idea-box/blob/master/app/models/idea.rb#L26-L40)
* I'm sure there are other ways of doing this with less interation with the database.  I like the simplicity of just giving an input and getting an output.  No asking for state or value, just give an input and recieve the corresponding output.

### Link to a specific block of your code on Github that you feel not great about
* [editing an idea](https://github.com/jdliss/idea-box/blob/master/app/assets/javascripts/edit-idea.js#L21-L39)
* I didn't use `contenteditable`, I removed the existing html object and appended a form populated with the text.  it's not too pretty. I took a while trying to make it work, and was so disappointed when I found `contenteditable` after I was done.

### Attach a screenshot or paste the output from your terminal of the result of your test-suite running.
```
.....

Finished in 2.93 seconds (files took 2 seconds to load)
5 examples, 0 failures (89.8%) covered.
```

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
(5 points total.) - doesnt truncate to nearest word
​
#### Adding a new idea
​
(15 points total.)

​
#### Deleting an existing idea
​
(15 points total.)

​
#### Changing the quality of an idea
​
(15 points total.)
​
#### Editing an existing idea
​
(20 points total.)
​
#### Idea Filtering and Searching
​
(15 points total.)

## Instructor Evaluation Points
​
### Specification Adherence
​
* **10 points**: The application consists of one page with all of the major functionality being provided by jQuery. There is no use of `format.js` in Rails. There is no use of unobstrusive JavaScript. There are no front-end frameworks used in the application. No approach was taken that is counter to the spirit of the project and its learning goals. There are no features missing from above that make the application feel incomplete or hard to use.
​
### User Interface
​
* **4 points** - The application is pleasant, logical, and easy to use. There no holes in functionality and the application stands on it own to be used by the instructor _without_ guidance from the developer.
​
### Testing
​
* **10 points** - Project has a running test suite that exercises the application at multiple levels including JavaScript tests.
​
### Ruby and Rails Quality
​
* **8 points** - Developer solves problems with a balance between conciseness and clarity and often extracts logical components. Developer can speak to choices made in the code and knows what every line of code is doing.

​
### JavaScript Style
​
* **8 points** - Application is thoughtfully put together with some duplication and no major bugs. Developer can speak to choices made in the code and knows what every line of code is doing.
​
### Workflow
​
* **10 points** - The developer effectively uses Git branches and many small, atomic commits that document the evolution of their application.

### Total Score: 140/150
