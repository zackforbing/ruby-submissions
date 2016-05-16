# Ideabox 2.0 Submission Form - Brant Wellman
[Project Spec](https://github.com/turingschool/curriculum/blob/master/source/projects/revenge_of_idea_box.markdown)

# Basics

[Github Repo](https://github.com/brantwellman/Ideabox_2)

[Production Application](https://pacific-basin-33271.herokuapp.com/)

### Link to Your Commits in the Github Repository for the Project
[My Commits](https://github.com/brantwellman/Ideabox_2/commits/master)

![IdeaBox](images/wellman_idea_box.png)

## Completion

### Were you able to complete the base functionality?  
Yes, all of the base functionality was completed

### Which extensions, if any, did you complete?  
I completed the inline editing extension

![](http://g.recordit.co/XwoBFa9D8S.gif)

# Code Quality

### Link to a specific block of your code on Github that you are proud of
I am proud of both my [filter ideas](https://github.com/brantwellman/Ideabox_2/blob/master/app/assets/javascripts/filter_ideas.js) implementation.

#### Why were you proud of this piece of code?  
I am proud of this implementation because I was able to filter content based on both the title and the body of the ideas. I had an idea of how I originally wanted to implement it and didn't stray far from my original idea.

### Link to a specific block of your code on Github that you feel not great about  
I am not particularly fond of my [edit idea](https://github.com/brantwellman/Ideabox_2/blob/master/app/assets/javascripts/edit_idea.js) implementations.
#### Why do you feel not awesome about the code? What challenges did you face trying to write/refactor it?  
There is a lot of duplication between the editBody and editTitle functions. I would like to go back to them and refactor them to reduce the duplication, and possibly reduce it to one function. Although I was pleased to be able to bind the update portion of the function to two separate events.

### Attach a screenshot or paste the output from your terminal of the result of your test-suite running.
![IdeaBox Tests](images/wellman_idea_box_tests.png)

### Provide a link to an example, if you have one, of a test that covers an 'edge case' or 'unhappy path'
I don't have any true unhappy path tests - The closest I have are tests for the validations on my Idea model.

-----

### Please feel free to ask any other questions or make any other statements below!  
I had trouble with accessing a variable that should have been within the scope of the function I was writing. I noticed that it may have had something to do with how the variable was defined using `this`.  
How do you send a flash message to the user when an object doesn't save due to a validation failure?  
Difficult but fun project!

---

## Points

Caveot that when you truncate, the characters after the body get thrown out. If you then do inline editing, the rest of the body gets deleted.

**Overall Points**: 153

### Project Requirements

* Data Model - 5
* Viewing Ideas - 10
* Adding a New Idea - 15
* Deleting an Existing Idea - 15
* Changing the Quality of the Idea - 15
* Editing an Existing Idea - 20
* Idea Filtering and Searching - 15
* Extensions - 10 (inline editing)

### Instructor Evaluation Points

* Specification Adherence - 10
* User Interface - 3
* Testing - 5
* Ruby on Rails Quality - 10
* JavaScript Style - 8
* Workflow - 10
