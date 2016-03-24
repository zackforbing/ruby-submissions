# Ideabox 2.0 Submission Form - Justin Pease

# Basics

### Link to the Github Repository for the Project
[My Repo](https://github.com/Jpease1020/Idea-Box-js)

### Link to the Deployed Application
[My Application](https://idea-box-jp.herokuapp.com/)

### Link to Your Commits in the Github Repository for the Project
[My Commits](https://github.com/Jpease1020/Idea-Box-js/commits/master)

### Provide a Screenshot of your Application
![](http://g.recordit.co/lbiPCbrZ0x.gif)

## Completion

### Were you able to complete the base functionality?

Yes

### Which extensions, if any, did you complete?

I completed the inline editing.  A user can edit the title or body of an idea in real time without the page reloading.  The changes are send over to the database and the updates are displayed if you refresh the page.
I also completed the sorting function.  A user can sort the ideas with the genius ideas defaulting to the top of the page.

### Attach a .gif, or images of any extensions work being used on the site.

Editing Inline:

![](http://g.recordit.co/LJrMGA0gOh.gif)

Sorting:

![](http://g.recordit.co/8OROWnaBp2.gif)

# Code Quality

### Link to a specific block of your code on Github that you are proud of

[Link](https://github.com/Jpease1020/Idea-Box-js/blob/6d7d2997bc6de2f3dd8b603752a08a243c8fa374/app/assets/javascripts/index.js#L19-L29)

I was very proud of this code when I wrote it.  I honestly feel that it's not incredible but I need to put something here.  I am pretty proud of the whole app and how much I accomplished.

### Link to a specific block of your code on Github that you feel not great about

[Link](https://github.com/Jpease1020/Idea-Box-js/blob/0d817d5c42721d4a1cef2897649cbe0cc9528a78/app/assets/javascripts/sort_idea_by_quality.js#L1-L17)

I don't know if this is the best way to achieve this functionality.  I needed to add blank elements to the page to keep track out the counter for the button being clicked and reseting it when the page gets refreshed.  It's either clever or just wrong.

### Attach a screenshot or paste the output from your terminal of the result of your test-suite running.

➜  Idea-box git:(master) rspec
Pending: (Failures listed here are expected and do not affect your suite's status)

  1) Api::V1::IdeasController Ideas controller update updates and returns an idea
     # Temporarily skipped with xit
     # ./spec/controllers/api_ideas_controller_spec.rb:31

  2) Api::V1::IdeasController Ideas controller delete deletes an idea
     # Temporarily skipped with xit
     # ./spec/controllers/api_ideas_controller_spec.rb:44

  3) User thumbs up an idea idea is created will default swill quality then upgraded
     # Temporarily disabled with xscenario
     # ./spec/features/user_thumbs_up_an_idea_spec.rb:4


Finished in 4.79 seconds (files took 3.36 seconds to load)
12 examples, 0 failures, 3 pending

➜  Idea-box git:(master)

### Provide a link to an example, if you have one, of a test that covers an 'edge case' or 'unhappy path'

[]()
