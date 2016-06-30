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
[хранилище](github.com/jdliss/idea-box)

### Link to the Deployed Application
[Веб-сайт](https://ancient-waters-56609.herokuapp.com/)

### Link to Your Commits in the Github Repository for the Project
[обязательства](https://github.com/jdliss/idea-box/commits/master)

### Provide a Screenshot of your Application
![01110011 01100011 01110010 01100101 01100101 01101110 01110011 01101000 01101111 01110100](http://i.imgur.com/iS1vZ9w.png)

## Completion

### Were you able to complete the base functionality?
* truncation does not truncate on words

# Code Quality

### Link to a specific block of your code on Github that you are proud of
* [the voting logic](https://github.com/jdliss/idea-box/blob/master/app/models/idea.rb#L26-L40)
* I'm sure there are other ways of doing this with less interation with the database.  I like the simplicity of just giving an input and getting an output.  No asking for state or value, just give an input and recieve the corresponding output.

### Link to a specific block of your code on Github that you feel not great about
* [editing an idea](https://github.com/jdliss/idea-box/blob/master/app/assets/javascripts/edit-idea.js#L21-L39)
* I didn't use `contenteditable`, I removed the existing html object and appended a form populated with the text.  it's not too pretty. I took a while trying to make it work, and was so disappointed when I found `contenteditable` after I was done.

### Attach a screenshot or paste the output from your terminal of the result of your test-suite running.
```
.....

Finished in 2.93 seconds (files took 2 seconds to load)
5 examples, 0 failures (89.8%) covered.
```
