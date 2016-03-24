# Ideabox 2.0 Submission Form
[Project Spec](https://github.com/turingschool/curriculum/blob/master/source/projects/revenge_of_idea_box.markdown)

# Basics

### Link to the Github Repository for the Project
[My Repo](https://github.com/jecrockett/idea_box)

### Link to the Deployed Application
[Deployed App](https://jec-idea-box.herokuapp.com/)

### Link to Your Commits in the Github Repository for the Project
[My Commits](https://github.com/jecrockett/idea_box/commits/master)

### Provide a Screenshot of your Application
![ideabox](images/jamie_crockett_ideabox.png)

## Completion

### Were you able to complete the base functionality?
* Yes

### Which extensions, if any, did you complete?
* I completed quality sorting and inline editing.

### Attach a .gif, or images of any extensions work being used on the site.
Inline Editing
![](http://g.recordit.co/kd62FrmCww.gif)

Sorting
![](http://g.recordit.co/he0CiLOGKz.gif)

# Code Quality

### Link to a specific block of your code on Github that you are proud of
[Code](https://github.com/jecrockett/idea_box/blob/14ff893de16818cd193154ae67ffc1e1c1138b84/app/assets/javascripts/sort_quality.js#L14-L30)

I thought it was clever to have an if else that determines whether the set of ideas actually needs to be sorted or if it simply can be reversed. If it's already been sorted and no new ideas have been added, the logic simply flips the ideas rather than performing any analysis.

### Link to a specific block of your code on Github that you feel not great about
[Code](https://github.com/jecrockett/idea_box/blob/14ff893de16818cd193154ae67ffc1e1c1138b84/app/assets/javascripts/update_idea_quality.js#L1-L12)

I was proud that I was able to refactor this from two separate increase/decrease functions into one, but it still feels like I'm assigning too many variables and in general too much is going on. I'm still struggling to think of JS in an OO way and give small responsibilities to objects. I'm just throwing a bunch of variables into a magic machine that gives me what I want.

### Attach a screenshot or paste the output from your terminal of the result of your test-suite running.
```
$ rspec
.................

Finished in 9.08 seconds (files took 2.12 seconds to load)
17 examples, 0 failures
```

### Provide a link to an example, if you have one, of a test that covers an 'edge case' or 'unhappy path'

-----

### Please feel free to ask any other questions or make any other statements below!
Really enjoyed this project. Made me feel capable at JS, but also open my eyes to how much I don't understand and how far I have to go in terms of 'thinking' in the language.
