# Basics

### Link to the Github Repository for the Project
[My Repo](https://github.com/hhoopes/idea_box)

### Link to the Deployed Application
[Boxed-Ideas](http://boxed-ideas.herokuapp.com/)

### Link to Your Commits in the Github Repository for the Project
[My Commits](https://github.com/hhoopes/idea_box/commits/master)

### Provide a Screenshot of your Application
![Filtered](https://github.com/hhoopes/idea_box/blob/master/images/screenshot1.png)
![All Ideas](https://github.com/hhoopes/idea_box/blob/master/images/screenshot2.png)

## Completion

### Were you able to complete the base functionality?
* I literally got all of the functionality, except that I didn't label the search box "Search" (but put that text inside the box).

### Which extensions, if any, did you complete?
* I didn't complete any extensions

### Attach a .gif, or images of any extensions work being used on the site.
N/A

# Code Quality

### Link to a specific block of your code on Github that you are proud of
[Filtering ideas](https://github.com/hhoopes/idea_box/blob/master/app/assets/javascripts/idea_filter.js#L1)

* Why were you proud of this piece of code?
I started off a little scared of the feature, but learned a lot about various events(keypress, keyup, change) and different ways you could match text in JS(match, indexOf). Because I gradually refactored it, I'm very happy with how well my search works. It's both case-insensitive and looks in the middle of the words or at partial words. And now I know the subtleties of using various keyboard events!

### Link to a specific block of your code on Github that you feel not great about
[Editing idea](https://github.com/hhoopes/idea_box/blob/master/app/assets/javascripts/idea_editor.js#L23)

* Why do you feel not awesome about the code? What challenges did you face trying to write/refactor it?
I had to duplicate a lot of code at first because I implemented enums in the database. It meant when I called an idea's quality on the front end, I was returned the string value. I realized later that there is a method for accessing the integer, but it's not as obvious. So I could refactor it now so I can do math with the qualities a little more easily and not have to use multiple if loops to handle different contexts.

### Attach a screenshot or paste the output from your terminal of the result of your test-suite running.
![Test Suite](https://github.com/hhoopes/idea_box/blob/master/images/tests.png)

### Provide a link to an example, if you have one, of a test that covers an 'edge case' or 'unhappy path'
* I didn't do great at this, so this is probably one of my best in this sense.

[link](https://github.com/hhoopes/idea_box/blob/master/spec/features/visitor_sees_all_ideas_spec.rb)
-----

### Please feel free to ask any other questions or make any other statements below!
