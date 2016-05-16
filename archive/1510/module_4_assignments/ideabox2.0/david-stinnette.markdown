# Ideabox 2.0 Submission Form - David Stinnette

# Basics

### Link to the Github Repository for the Project
[My Repo](https://github.com/dastinnette/idea-box2.0)

### Link to the Deployed Application
[My Application](https://ideabox2-0.herokuapp.com/)

### Link to Your Commits in the Github Repository for the Project
[My Commits](https://github.com/dastinnette/idea-box2.0/commits/master)

### Provide a Screenshot of your Application
![App Screenshot](images/david_stinnette_app_screenshot.png)

## Completion

### Were you able to complete the base functionality?

Yes

### Which extensions, if any, did you complete?

I completed inline editing.

### Attach a .gif, or images of any extensions work being used on the site.

Editing Inline:

![Extension Screenshot](images/david_stinnette_extension_screenshot.png)

# Code Quality

### Link to a specific block of your code on Github that you are proud of

[Link](https://github.com/dastinnette/idea-box2.0/blob/23688202a5c59053f9dbe215c64a927175a68dad/app/assets/javascripts/idea_post.js#L1-L21)

Nothing particularly groundbreaking about this create idea function but I like it for two reasons. One, this is where I pseudocoded and figured out the solution step by step - gained a lot of knowledge and confidence along the way. Two, I simplified all of my js functions by pull out each action into its own file. If I were to keep working on this I might consider limiting the scope or availability of these functions are they're currently global.

### Link to a specific block of your code on Github that you feel not great about

[Link](https://github.com/dastinnette/idea-box2.0/blob/23688202a5c59053f9dbe215c64a927175a68dad/app/assets/javascripts/idea_index.js#L1-L19)

Surely there must be a better way to do this, right? Seeing all this string concatenation makes me sad on the inside. This function holds a lot of power as it is called in several other functions such as truncate and ideaQuality. While this keeps my app somewhat DRY, I'd really like to learn how to work with js objects in a better, more effective way.

### Attach a screenshot or paste the output from your terminal of the result of your test-suite running.

```
11:30 PM   ~/Turing/4module/IDEABOX/ideabox   master
$ rspec
......

Finished in 0.47586 seconds (files took 4.1 seconds to load)
6 examples, 0 failures

Coverage report generated for RSpec to /Users/davidstinnette/Turing/4module/IDEABOX/ideabox/coverage. 20 / 20 LOC (100.0%) covered.
```

### Provide a link to an example, if you have one, of a test that covers an 'edge case' or 'unhappy path'

I removed my sad path tests for the idea model when I removed validations to make my app more flexible for the user - say if they want to create an idea where no description/body is necessary. 


---

## Points

Implemented inline editing. Hitting enter works, but clicking out of the box doesn't.

**Overall Points**: 150

### Project Requirements

* Data Model - 5
* Viewing Ideas - 10
* Adding a New Idea - 15
* Deleting an Existing Idea - 15
* Changing the Quality of the Idea - 15
* Editing an Existing Idea - 20
* Idea Filtering and Searching - 15
* Extensions - 5 


### Instructor Evaluation Points

* Specification Adherence - 10
* User Interface - 3
* Testing - 9
* Ruby on Rails Quality - 10
* JavaScript Style - 8
* Workflow - 10
