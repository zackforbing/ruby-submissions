# Ideabox 2.0 Submission Form
[Project Spec](https://github.com/turingschool/curriculum/blob/master/source/projects/revenge_of_idea_box.markdown)

------

# Basics

### Link to the Github Repository for the Project
[My IdeaBox Repo](https://github.com/allindow/idea_box)

### Link to the Deployed Application
[IdeaBox on Heroku](https://afternoon-spire-33792.herokuapp.com/)

### Link to Your Commits in the Github Repository for the Project
[My Commits](https://github.com/allindow/idea_box/commits/master)

### Provide a Screenshot of your Application
![Screenshot](images/angela_ideabox_ss.png)

## Completion

### Were you able to complete the base functionality?
* Yes

### Which extensions, if any, did you complete?
* None

# Code Quality

### Link to a specific block of your code on Github that you are proud of
* Why were you proud of this piece of code?
 [editIdea](https://github.com/allindow/idea_box/blob/master/app/assets/javascripts/edit_idea.js#L5-L15)

 I'm proud of it because originally this whole JS file was very *not* DRY, and I wasn't going to bother with refactoring it because I felt like there was a lot going on. I decided to try it, and in the process got more practice traversing the DOM. I think the each loops could have been pulled out into separate functions, too, but I'm happy that I got to this point.

### Link to a specific block of your code on Github that you feel not great about
* Why do you feel not awesome about the code? What challenges did you face trying to write/refactor it?
[getIdeas](https://github.com/allindow/idea_box/blob/master/app/assets/javascripts/get_all_ideas.js#L1-L17)

Clearly all of this is commented out. I wouldn't say I don't feel awesome about it because I think the implementation is ok, and it worked when I was in the browser. However, it made a majority of my tests fail because with Selenium, it wasn't getting the ideas to load to the page for some reason. I tinkered around for quite a while but wasn't able to figure it out, so I left in my original code in index.html.erb where I'm iterating through `@items` on the initial page load.

### Attach a screenshot or paste the output from your terminal of the result of your test-suite running.
```
idea_box git/master  11s
❯ rspec
............

Finished in 7.54 seconds (files took 2.55 seconds to load)
12 examples, 0 failures

Coverage report generated for RSpec to /Users/Angela/turing/4module/projects/idea_box/coverage. 30 / 30 LOC (100.0%) covered.
```


### Provide a link to an example, if you have one, of a test that covers an 'edge case' or 'unhappy path'

-----

### Please feel free to ask any other questions or make any other statements below!
* Any ideas on the weird selenium not loading my ideas thing? 
