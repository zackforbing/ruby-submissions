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
[My GitHub Repo](https://github.com/GSmes/ideabox_2.0)

### Link to the Deployed Application
[My Heroku Application](https://ideasinabox.herokuapp.com/)

### Link to Your Commits in the Github Repository for the Project
[My Git Commits](https://github.com/GSmes/ideabox_2.0/commits/master)

### Provide a Screenshot of your Application
![Application Screenshot](images/Application_Screenshot.png)

## Completion

### Were you able to complete the base functionality?
No.

_Functionality missing:_
* Idea filtering and searching

### Which extensions, if any, did you complete?
None.

# Code Quality

### Link to a specific block of your code on Github that you are proud of
[(updateAjax)](https://github.com/GSmes/ideabox_2.0/blob/master/app/assets/javascripts/vote.js#L44)
* I'm proud of this because initially I was getting it to save the updated quality in the database, but it often wasn't reflecting on the page. My initial solution was _extremely_ lengthy, and contained traversals like `.parent().parent().parent().prev()`. It took me longer than I care to admit to figure out a concise, accurate way of updating what's on the page (like using `.closest("td")`).

### Link to a specific block of your code on Github that you feel not great about
[(parseInt)](https://github.com/GSmes/ideabox_2.0/blob/master/app/assets/javascripts/vote.js#L10)
* I'm pretty proud of all my code, I guess, so I'm just picking my least favorite. I'm not proud of my use of `parseInt` so frequently. I initially only had it in my updateAjax method, but for some reason that I was never able to figure out, voting would occasionally fail, and I was at a point of frustration, so I ended up just putting it everywhere that it _might_ need to be.

### Attach a screenshot or paste the output from your terminal of the result of your test-suite running.
![Testing Screenshot](images/Testing_Screenshot.png)

### Provide a link to an example, if you have one, of a test that covers an 'edge case' or 'unhappy path'

-----

### Please feel free to ask any other questions or make any other statements below!
