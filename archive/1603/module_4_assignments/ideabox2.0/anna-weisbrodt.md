# Ideabox 2.0 Submission Form - Anna Weisbrodt

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
[GitHub Repo](https://github.com/AnnaCW/ideabox)

### Link to the Deployed Application
[Deployed Application](https://pure-inlet-70337.herokuapp.com/)

### Link to Your Commits in the Github Repository for the Project
[Commits](https://github.com/AnnaCW/ideabox/commits/master)

### Provide a Screenshot of your Application
![screenshot](https://cloud.githubusercontent.com/assets/17806544/17761550/3793b36a-64c5-11e6-9d70-aaaea8383c9a.png)

## Completion

### Were you able to complete the base functionality?
* Yes

### Which extensions, if any, did you complete?
* None

### Attach a .gif, or images of any extensions work being used on the site.
* N/A

# Code Quality

### Link to a specific block of your code on Github that you are proud of
* Why were you proud of this piece of code?

[Link to Code](https://github.com/AnnaCW/ideabox/blob/d4bd9aa93ac951c9d06a85dffc4a425a242d07c8/app/assets/javascripts/ideas_helpers.js#L1-L34)

* This is a link to my JS helper functions file. While my JS code could certainly use more refactoring, this was really my first effort to refactor JS. During refactoring, I also went from having everything in one long ideas.js file, to breaking my functions into different files (roughly corresponding to CRUD, plus the helpers file). Breaking the code into separate files really helped me start to see what could be split apart and refactored.


### Link to a specific block of your code on Github that you feel not great about
* Why do you feel not awesome about the code? What challenges did you face trying to write/refactor it?

[Link To Code](https://github.com/AnnaCW/ideabox/blob/d4bd9aa93ac951c9d06a85dffc4a425a242d07c8/app/assets/javascripts/edit_ideas.js#L1-L47)

* This is a link to part of my code for the edit ideas (title and body) functionality. I had a lot of challenges in trying to get this to work, so I'm proud of it in the sense that I got it working. I don't feel great about it in that I'm sure this is not the best way to do it, and the code just looks messy. I was not able to test it so I am hesitant to refactor.

### Attach a screenshot or paste the output from your terminal of the result of your test-suite running.

#### RSPEC

Annas-MacBook:ideabox ACW$ rspec
WARNING: The next major version of capybara-webkit will require at least version 5.0 of Qt. You're using version 4.8.7.
........

Finished in 2.6 seconds (files took 2.46 seconds to load)
8 examples, 0 failures

#### TEASPOON

Annas-MacBook:ideabox ACW$ rake teaspoon
Starting the Teaspoon server...
Puma starting in single mode...
* Version 3.6.0 (ruby 2.3.0-p0), codename: Sleepy Sunday Serenity
* Min threads: 5, max threads: 5
* Environment: test
* Listening on tcp://127.0.0.1:62767
Use Ctrl-C to stop
Teaspoon running default suite at http://127.0.0.1:62767/teaspoon/default
.

Finished in 0.01500 seconds
1 example, 0 failures

Annas-MacBook:ideabox ACW$


### Provide a link to an example, if you have one, of a test that covers an 'edge case' or 'unhappy path'

[Unhappy Path Example](https://github.com/AnnaCW/ideabox/blob/e09dade90526f885312bca435285e43f9f538dd4/spec/features/user_edits_quality_spec.rb#L19-L49)

* This test ensures that nothing happens when a user tries to upvote a 'genius' idea, or downvote a 'swill' idea.

-----

### Please feel free to ask any other questions or make any other statements below!

141/150

----

# Instructor Feedback

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

* **10 points**

### User Interface

- Add New Idea at bottom of the page
- Can only edit one field per page reload (due to all event listeners for edit being removed)
- Some movement of the table when larger words are introduced to quality

* **3 points** - The application has many strong pages/interactions, but a few holes in lesser-used functionality.

### Testing

* *** points** - Project has sporadic use of tests and multiple levels. Not all controller actions are tested. There are little or no attempts at integration testing.

### Ruby and Rails Quality

* **10 points** - Developer is able to craft Rails features that make smart use of Ruby, follow the principles of MVC, and push business logic down where it belongs. There _zero_ instances where an instructor would recommend taking a different approach. Developer writes code that is exceptionally clear and well-factored. Application is expertly divided into logical components each with a clear, single responsibility.

### JavaScript Style

* **5 points** - Your application has some duplication and minor bugs. Developer can speak to most choices made in the code and knows what every line is doing.

### Workflow

* **10 points** - The developer effectively uses Git branches and many small, atomic commits that document the evolution of their application.
