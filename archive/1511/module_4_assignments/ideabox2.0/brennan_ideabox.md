# Ideabox 2.0 Submission Form
[Project Spec](https://github.com/turingschool/curriculum/blob/master/source/projects/revenge_of_idea_box.markdown)

* Submit a pull request
* Pro Tip: You can use [recordit.co](http://recordit.co/) to record interaction gifs.
* Secondary Pro Tip: [Here's how to link to specific line number(s) in Github](http://stackoverflow.com/questions/23821235/how-to-link-to-specific-line-number-on-github)
* Tertiary Pro Tip: You can re-use some of these things in your portfolio/resume

------

# Basics

### Link to the Github Repository for the Project
[My Repo](https://github.com/brennanholtzclaw/idea_box)

### Link to the Deployed Application
[My Application](http://brennan-idea-box.herokuapp.com/)

### Link to Your Commits in the Github Repository for the Project
[My Commits](https://github.com/brennanholtzclaw/idea_box/commits/master)

### Provide a Screenshot of your Application
![Boxing up ideas](images/ideabox.png)

# Completion

### Were you able to complete the base functionality?
This application is able to perform all base functionality. You can submit an idea with a title and body, by clicking "Create Idea".
Once ideas have been created, you can promote or demote ideas with the 'Thumbs Up' and 'Thumbs Down' buttons, and if an idea is really bad, you can just delete it with 'Delete Idea'.

### Which extensions, if any, did you complete?
No Extensions

### Attach a .gif, or images of any extensions work being used on the site.

# Code Quality

### Link to a specific block of your code on Github that you are proud of
[Filtering Ideas](https://github.com/brennanholtzclaw/idea_box/blob/master/app/assets/javascripts/filter.js#L1-L11)
 I honestly don't know if I *should* be happy with this code, but I like how it makes use of the simple ```show``` and ```hide``` methods. It also uses indexOf which we just covered in class to determine whether or not a text string matches with text in the titles of ideas.

### Link to a specific block of your code on Github that you feel not great about
[Voting for Ideas](https://github.com/brennanholtzclaw/idea_box/blob/master/app/assets/javascripts/voteForIdea.js#L1-L30)
There just has to be a better way of doing this huge if/else block. I kept having a mix of weird problems with either Rails or Javascript when I tried to implement quality as an enum on the idea model. Because of the validation on the idea model, its impossible to assign an incorrect quality, but the lengthy if/else that had to be written for Up and Down just seems wrong...

### Attach a screenshot or paste the output from your terminal of the result of your test-suite running.
![The Test Results Came Back Positive](images/small_test_suite.png)

### Provide a link to an example, if you have one, of a test that covers an 'edge case' or 'unhappy path'

-----

### Please feel free to ask any other questions or make any other statements below!
