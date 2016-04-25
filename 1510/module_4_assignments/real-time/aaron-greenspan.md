# RealTime Submission Form
[Project Spec](https://github.com/turingschool/curriculum/blob/master/source/projects/real_time.markdown)

------

# Basics

### Link to the Github Repo
[Github](https://github.com/afg419/frozen-citadel-14380)

### Link to the Deployed App
[WordScram!](https://frozen-citadel-14380.herokuapp.com/)

### Link to Your Commits in the Github Repository for the Project
[Github Commits](https://github.com/afg419/frozen-citadel-14380/commits/master)

### Screenshot 
![Imgur](http://i.imgur.com/k4u6sZL.png?1)

## Completion

### Were you able to complete functionality that fits both case studies?  
  No.  I wanted to make a second mathy version of the game, never got to it.    
### List any functionality from the case studies that is missing  
  Beyond the mathy game, within the descrambling word game, I wanted to have some stats about the most recent game (top score, average score, etc...).  The app has been built as to easily iterate into this functionality (need one more cell in the user table for most recent score).    
### Did you do anything outside the scope of the case studies?

# Code Quality  

### Link to a specific block of your code on Github that you are proud of  
[channel controller](https://github.com/afg419/frozen-citadel-14380/blob/master/web/channels/counter_channel.ex)  
* Why were you proud of this piece of code?  
  This file represents both the biggest challenge of the project -- working with phoenix channels -- and also the greatest refactoring success.  By signing the socket with the username of the authenticated user, we can react to their disconnecting!
    
### Link to a specific block of your code on Github that you feel not great about  
[dictionary file](https://github.com/afg419/frozen-citadel-14380/blob/master/web/static/js/en_US.js)  
  
* Why do you feel not awesome about the code? What challenges did you face trying to write/refactor it?  
It infuriates me to no end that I had to include an entire dictionary slash list of words in my project to get spellchecking to work.  It is absurd that the built in HTML5 `spellcheck = true` property does not allow you to check whether or not  the words it is now spellchecking are spelled correctly.

### Attach a screenshot or paste the output from your terminal of the result of your test-suite running.  
![Imgur](http://i.imgur.com/W12Gxrn.png)

### Provide a link to an example, if you have one, of a test that covers an 'edge case' or 'unhappy path'  
[edge case testing](https://github.com/afg419/frozen-citadel-14380/blob/bc15ee82302e5ca207f79c7ccfc4e4baf1e735a4/test/models/user_test.exs#L17-L38)

-----

### Please feel free to ask any other questions or make any other statements below!


-----

## Instructor Feedback

164/200

### Concept and Features

Does it have the expected features?

* 75 points - Met expectations as outlined by the user personas, the application is a solid first version. All planned features were delivered.

### Code Quality (JavaScript and/or Ruby)

* 30 points - Developer writes code that is exceptionally clear and well-factored. Application is expertly divided into logical components each with a clear, single responsibility.

### Client-Side Application

* 30 points - Your application has exceptionally well-factored code with little or now duplication and all components separated out into logical components.

### Test-Driven Development

* 20 points - The code demonstrates high test coverage. One or more enpoints are not tested or the internal business logic is not fully tested.

### Interface

* 5 points - The application is pleasant, logical, and easy to use

### Workflow

* 4 points - The developer makes a series of small, atomic commits that document the evolution of their application. There are no formatting issues in the code base.
