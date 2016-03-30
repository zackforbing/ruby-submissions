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
[Your Repo](https://github.com/GregoryArmstrong/IdeaBox)

### Link to the Deployed Application
[Your Application](https://vast-basin-70734.herokuapp.com/)

### Link to Your Commits in the Github Repository for the Project
[Your Commits](https://github.com/GregoryArmstrong/IdeaBox/commits/master)

### Provide a Screenshot of your Application
[IdeaBox](images/greg-armstrong-index.png)

## Completion

### Were you able to complete the base functionality?
* Yes, some of the 'Editing an existing idea' functionality isnt there because I did the inline-editing extension. Meeka mentioned that if we do that extension, we should
improve the UI to not need those additional editing buttons and such.

### Which extensions, if any, did you complete?
* Inline-Editing

### Attach a .gif, or images of any extensions work being used on the site.

[Inline Editing](http://g.recordit.co/p2ttLSnDdg.gif)

# Code Quality

### Link to a specific block of your code on Github that you are proud of

[Inline Edit Function](https://github.com/GregoryArmstrong/IdeaBox/blob/master/app/assets/javascripts/edit.js#L20-L30)
* Proud of it because it took me a while to understand how to have the inline-editing initial selection click allow for a subsequent trigger via keydown() of the enter key, or by clicking
outside the line being edited. Was able to have each subsequent action utilize the same function to submit the new data via AJAX request to my API, reducing duplication of code.

### Link to a specific block of your code on Github that you feel not great about
[AJAX Put Request Conditional](https://github.com/GregoryArmstrong/IdeaBox/blob/master/app/assets/javascripts/edit.js#L34-L38)
* Didnt feel awesome about this because it seems to be a clunky way to determine which value I wanted the variable to be set to. I tried to refactor it into its own function
to determine which value to set the variable, but then the following AJAX call didnt have access to the variable. I think I was returning the variable incorrectly or something.


### Attach a screenshot or paste the output from your terminal of the result of your test-suite running.

* Failures:

  1) IdeaIndices guest can see ideas on index
     Failure/Error: expect(page).to have_content(idea.title)
       expected to find text "test 1 title" in "Ideas Index Search Title Body"
     # ./spec/features/idea_indices_spec.rb:15:in block (2 levels) in <top (required)>

* Finished in 0.82516 seconds (files took 2.52 seconds to load)
* 8 examples, 1 failure, 1 pending

* Failed examples:

* rspec ./spec/features/idea_indices_spec.rb:4 # IdeaIndices guest can see ideas on index

* Coverage report generated for RSpec to /Users/gregoryarmstrong/turing/4module/Projects/IdeaBox/coverage. 33 / 33 LOC (100.0%) covered.

#### The pending test was the pre-made model test which I forgot to remove before running out of time. The failing test was for user functionality, didnt have enough time to properly
#### feature test things via Selenium. 100% coverage of controllers and models though.


### Provide a link to an example, if you have one, of a test that covers an 'edge case' or 'unhappy path'

[Unhappy Path for Quality not going Above Genius or Below Swill](https://github.com/GregoryArmstrong/IdeaBox/blob/master/spec/controllers/ideas_controller_spec.rb#L74-L95)
* In this test i was able to assert that the idea.quality value cannot be increased higher than 3 or lower than 1. (1: swill, 2: plausible, 3: genius).

-----

### Please feel free to ask any other questions or make any other statements below!
* I really liked this project. It seemed to have just enough difficulty to make it challenging without being out of reach. I learned a TON about the differences between functional and OO programming. I didnt test as well as I should have when it came to feature tests, I fell behind in using TDD because I wanted to make sure I finished the spec. I'll definitely push myself very hard to go back to TDD for the next project, it was at times difficult to find the errors/bugs occuring because I had no tests to help me determine that.
