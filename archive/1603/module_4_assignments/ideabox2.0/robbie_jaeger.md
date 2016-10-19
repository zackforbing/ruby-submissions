## Robbie Jaeger - Idea Box 2.0

### Important Links:

[Github Repo](https://github.com/robbiejaeger/idea_box.git)

[Production Link](https://ideabox-rj.herokuapp.com/)

[Github Commits](https://github.com/robbiejaeger/idea_box/commits/master)

### Screenshot:
[Idea Box Home Page](http://www.openscreenshot.com/img/57b6080bdb43b5-19195265)

### Completion:
##### Were you able to complete the base functionality?
Yes, I was able to complete the base functionality required in each section (I did not finish truncation).

##### Which extensions, if any, did you complete?
I did not complete any extensions.

### Code Quality:
##### Link to a specific block of code on Github that you are proud of
 [Upvote and Downvote](https://github.com/robbiejaeger/idea_box/blob/master/app/assets/javascripts/vote_idea.js)

##### Why were you proud of this piece of code?
I tried to pay attention to future changes when writing this code. Originally, I had a quality enum in my Idea ActiveRecord model, and I changed it to use integers only. This way, I could change the quality strings in my JS - the number of qualities and strings could be changed without changing the logic.

##### Link to a specific block of your code on Github that you feel not great about
[Editing Title and Body](https://github.com/robbiejaeger/idea_box/blob/master/app/assets/javascripts/update_idea.js)

##### Why do you feel not awesome about the code? What challenges did you face trying to write/refactor it?
In the current state of this code, if you click on a title and do not make any changes, the ajax call will still be sent unnecessarily. I wanted to get the original state of the text to be able to compare it to the edited version, but I wasn't able to get it for ideas that were added after the document was loaded.

##### Attach a screenshot or past the output from your terminal of the result of your test-suite running.
```
Teaspoon running default suite at http://127.0.0.1:55051/teaspoon/default
*

Pending:
  can render an idea should be a div with title and body
    # Not yet implemented

Finished in 0.00500 seconds
1 example, 0 failures, 1 pending


robbie: idea_box (master) $ rspec
*....

Pending: (Failures listed here are expected and do not affect your suite's status)

  1) Home should not have JavaScript errors
     # Temporarily skipped with xit
     # ./spec/features/user_can_delete_idea_spec.rb:4


Finished in 0.45938 seconds (files took 1.8 seconds to load)
5 examples, 0 failures, 1 pending
```

##### Provide a link to an example, if you have one, of a test that covers an 'edge case' or 'unhappy path'
I couldn't get my feature testing to work with webkit...so no sad path - I'm not proud of it.

## Rubric
### Data Model

(5 points total.)


### User Flows

#### Viewing ideas

(10 points total.)
* Idea bodies longer than 100 characters should be truncated to the nearest word. (5 points)

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

* **5 points** - Project has sporadic use of tests and multiple levels. Not all controller actions are tested. There are little or no attempts at integration testing.

### Ruby and Rails Quality

* **10 points** - Developer is able to craft Rails features that make smart use of Ruby, follow the principles of MVC, and push business logic down where it belongs. There _zero_ instances where an instructor would recommend taking a different approach. Developer writes code that is exceptionally clear and well-factored. Application is expertly divided into logical components each with a clear, single responsibility.

### JavaScript Style

* **8 points** - Application is thoughtfully put together with some duplication and no major bugs. Developer can speak to choices made in the code and knows what every line of code is doing.

### Workflow

* **10 points** - The developer effectively uses Git branches and many small, atomic commits that document the evolution of their application.
