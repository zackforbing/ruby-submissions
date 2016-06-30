# Ideabox 2.0 Submission Form
[Project Spec](https://github.com/turingschool/curriculum/blob/master/source/projects/revenge_of_idea_box.markdown)
------

# Basics

### Link to the Github Repository for the Project
[Your Repo](https://github.com/patrickwhardy/idea_box)

### Link to the Deployed Application
[Your Application](https://warm-tor-16277.herokuapp.com/)

### Link to Your Commits in the Github Repository for the Project
[Your Commits](https://github.com/patrickwhardy/idea_box/commits/master)

### Provide a Screenshot of your Application
![Ideabox Gif](http://recordit.co/XYSMrOeAnU.gif)

## Completion

### Were you able to complete the base functionality?
* Yes

### Which extensions, if any, did you complete?
* None

### Attach a .gif, or images of any extensions work being used on the site.
* Attached above
# Code Quality

### Link to a specific block of your code on Github that you are proud of
[Internal Api](https://github.com/patrickwhardy/idea_box/blob/master/app/controllers/api/v1/ideas_controller.rb)

* Why were you proud of this piece of code?
* Line 16 - Despite doing so much rails I was suprised to realized that updates are not set up to return data and was proud to figure out the work-around of stating json: @idea to make the app work as planned.

### Link to a specific block of your code on Github that you feel not great about
[Search Feature](https://github.com/patrickwhardy/idea_box/blob/master/app/assets/javascripts/ideas.js)

* Why do you feel not awesome about the code? What challenges did you face trying to write/refactor it?
* (Line 69) - This felt really hacky. I tried writing this block with .match and just could not get it to return true. I'm using .search when it is really meant for finding the index of chars. I also know that the search will also return matching html tags which is definitely not ideal.

### Attach a screenshot or paste the output from your terminal of the result of your test-suite running.

Patricks-MacBook-Pro-2:idea_box patrickwhardy$ rake test
Run options: --seed 60669

# Running:

..............

Fabulous run in 5.262109s, 2.6605 runs/s, 5.1310 assertions/s.

14 runs, 27 assertions, 0 failures, 0 errors, 0 skips
Patricks-MacBook-Pro-2:idea_box patrickwhardy$

### Provide a link to an example, if you have one, of a test that covers an 'edge case' or 'unhappy path'

[Idea Test](https://github.com/patrickwhardy/idea_box/blob/master/test/models/idea_test.rb)

* This refutes saving an idea with invalid attributes.

-----

### Please feel free to ask any other questions or make any other statements below!
