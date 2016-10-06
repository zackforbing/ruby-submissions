
# Basics

### Link to the Github Repository for the Project
[Your Repo](https://github.com/Laner12/revenge_of_idea_box)

### Link to the Deployed Application
[Your Application](https://revenge-of-idea-box.herokuapp.com/)

### Link to Your Commits in the Github Repository for the Project
[Your Commits](https://github.com/Laner12/revenge_of_idea_box/commits/master)

### Provide a Screenshot of your Application
![Idea Box Homepage](./idea_box.jpg)

## Completion

### Were you able to complete the base functionality?

* I was unable to finish the filtering with the navbar search
* I was unable to finish sanitizing the body length

# Code Quality

### Link to a specific block of your code on Github that you are proud of
[Code link](https://github.com/Laner12/revenge_of_idea_box/blob/master/app/assets/javascripts/idea.js#L89-L98)
* Why were you proud of this piece of code?

* It is probably not anywhere near good javascript but this was how I figured out how to pass the information to the controller.

### Link to a specific block of your code on Github that you feel not great about
[Code link](https://github.com/Laner12/revenge_of_idea_box/blob/master/app/controllers/api/v1/ideas_controller.rb#L11-L19)
* Why do you feel not awesome about the code? What challenges did you face trying to write/refactor it?

* I was having issues with how to update the voting params so I sent params to the controller to handle it, but I think there was certainly a better way.

### Attach a screenshot or paste the output from your terminal of the result of your test-suite running.
![Test suite](./test_suite.jpg)

-----

### Please feel free to ask any other questions or make any other statements below!

* I was having issues grabing all of the ideas in order to filter them. I was trying ``` $idea = $(".idea") ``` assuming that it would return an array of all ideas on the DOM. How could I have got all ideas?
