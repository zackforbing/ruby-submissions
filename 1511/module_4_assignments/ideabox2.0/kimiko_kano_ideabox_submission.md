# Ideabox 2.0 Submission Form
[Project Spec](https://github.com/turingschool/curriculum/blob/master/source/projects/revenge_of_idea_box.markdown)

# Basics

### Link to the Github Repository for the Project
[My Repo](https://github.com/ksk5280/js_idea_box)

### Link to the Deployed Application
[My Application](http://js-idea-box.herokuapp.com/)

### Link to My Commits in the Github Repository for the Project
[My Commits](https://github.com/ksk5280/js_idea_box/commits/master)

### Provide a Screenshot of your Application
![screenshot](images/screenshot.jpg)

## Completion

### Were you able to complete the base functionality?
* Yes

### Which extensions, if any, did you complete?
* I completed the sorting extension

### Attach a .gif, or images of any extensions work being used on the site.
http://recordit.co/eNDiVxxkwb

# Code Quality

### Link to a specific block of your code on Github that you are proud of
* Why were you proud of this piece of code?

https://github.com/ksk5280/js_idea_box/blob/master/app/assets/javascripts/add_ideas.js#L1-14

I think this block of code is pretty clean. The serialize method is convenient because it gets the info from the form and you can easily pass that data to the ajax call.


### Link to a specific block of your code on Github that you feel not great about
* Why do you feel not awesome about the code? What challenges did you face trying to write/refactor it?

https://github.com/ksk5280/js_idea_box/blob/master/app/assets/javascripts/sort_ideas.js#L19-57

I was happy to be able to get the sorting to work, but I used the same code to sort ascending and descending. I'm sure I could refactor it relatively easily, but it's late and I'm so tired...

### Attach a screenshot or paste the output from your terminal of the result of your test-suite running.
```
 --> rspec
.......................

Finished in 17.45 seconds (files took 2.79 seconds to load)
23 examples, 0 failures

Coverage report generated for RSpec to /Users/kimiko/Documents/Turing/4module/projects/js_idea_box/coverage. 30 / 30 LOC (100.0%) covered.

--> rake teaspoon
Starting the Teaspoon server...
Teaspoon running default suite at http://127.0.0.1:55839/teaspoon/default
..

Finished in 0.00800 seconds
2 examples, 0 failures
```
### Provide a link to an example, if you have one, of a test that covers an 'edge case' or 'unhappy path'

https://github.com/ksk5280/js_idea_box/blob/master/spec/requests/api/v1/ideas_controller_spec.rb
-----
