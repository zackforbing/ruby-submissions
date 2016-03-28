# Ideabox 2.0 Submission Form - Steven Olson

# Basics

### Link to the Github Repository for the Project
[My Repo](https://github.com/SteveOscar/idea_box)

### Link to the Deployed Application
[My Application](https://idea-box-of-dreams.herokuapp.com/)

### Link to Your Commits in the Github Repository for the Project
[My Commits](https://github.com/SteveOscar/idea_box/commits/master)

### Provide a Screenshot of your Application
![spacejam](http://i.imgur.com/vzbBwNH.png)

## Completion

### Were you able to complete the base functionality?

Yes

### Which extensions, if any, did you complete?

I completed the inline editing extension, allowing a user to click on a title or body field, edit it, and save changes by clicking outside of the field or hitting the 'enter' button. I also did some Selenium JS, testing which is not technically an extension, but is in my head.

### Attach a .gif, or images of any extensions work being used on the site.

Functionality with inline editing:

![](http://g.recordit.co/8KbeHPWaoW.gif)


# Code Quality

### Link to a specific block of your code on Github that you are proud of

[Link](https://github.com/SteveOscar/idea_box/blob/master/app/assets/javascripts/edit_inline.js)

I'm happy with this code because, although the methods aren't beautifully concise, I learned a lot in writing these methods for editing ideas inline. I had originally created this functionality with dedicated buttons and separate fields, so it was interesting to convert that to a much more compact UX. I was able to to extract the primary steps out into separate functions, and learned some new event listeners that will be useful in the future.

### Link to a specific block of your code on Github that you feel not great about

[Link](https://github.com/SteveOscar/idea_box/blob/master/app/assets/javascripts/ideas.js)

I don't like this giant block of html for rendering a new idea element on the page. I couldn't find a satisfying way to rearrange line breaks without breaking the code.

### Attach a screenshot or paste the output from your terminal of the result of your test-suite running.

```
.............................................

Finished in 10.184635s, 1.1782 runs/s, 2.5529 assertions/s.  


12 runs, 26 assertions, 0 failures, 0 errors, 0 skips
Coverage report generated for MiniTest to   
/Users/stevenolson/Turing/projects/idea_box/idea_box/coverage. 26 / 26 LOC (100.0%) covered.
```

### Provide a link to an example, if you have one, of a test that covers an 'edge case' or 'unhappy path'

[Create an idea with missing attributes ](https://github.com/SteveOscar/idea_box/blob/master/test/controllers/api/ideas_controller_test.rb)
