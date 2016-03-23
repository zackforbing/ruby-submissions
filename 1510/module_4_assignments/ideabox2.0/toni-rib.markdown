# Ideabox 2.0 Submission Form - Toni Rib

# Basics

### Link to the Github Repository for the Project
[My Repo](https://github.com/ToniRib/idea_box)

### Link to the Deployed Application
[My Application](https://toni-rib-idea-box.herokuapp.com/)

### Link to Your Commits in the Github Repository for the Project
[My Commits](https://github.com/ToniRib/idea_box/commits/master)

### Provide a Screenshot of your Application
![spacejam](images/ideabox_2_screenshot_toni_rib.png)

## Completion

### Were you able to complete the base functionality?

Yes

### Which extensions, if any, did you complete?

I completed part of the inline editing by allowing the user to edit inline and to click anywhere on the page to save the changes. However, I was not able to get it working with the enter key.

I also completed the sorting portion, allowing a user to sort by quality both descending and ascending.

### Attach a .gif, or images of any extensions work being used on the site.

Editing Inline:

![](http://g.recordit.co/h6Kp4zegaG.gif)

Sorting:

![](http://g.recordit.co/aSaJ4vAVl3.gif)

# Code Quality

### Link to a specific block of your code on Github that you are proud of

[Link](https://github.com/ToniRib/idea_box/blob/4aaff2ecc317a2c10d19d75e87170e0250e68fdc/app/assets/javascripts/filtering.js#L12-L31)

I liked this code because I thought I broke out the various methods/conditions into easy to understand functions that were named appropriately. Additionally, Steve helped me use the `toggle` function really well here to cut down on a lot of lines of code. I think this makes the filtering methods very concise.

### Link to a specific block of your code on Github that you feel not great about

[Link](https://github.com/ToniRib/idea_box/blob/4aaff2ecc317a2c10d19d75e87170e0250e68fdc/app/assets/javascripts/sorting.js#L25-L43)

I don't feel great about this because in talking to Steve I probably could have set up my AJAX methods differently to always be saving the JSON of the current ideas in some object. Since I didn't do that, I only knew how to sort these by creating objects, then sorting them, then adding them all back to the page again. If I wanted to refactor this, I think I would have had to completely refactor most of my AJAX methods.

### Attach a screenshot or paste the output from your terminal of the result of your test-suite running.

```
idea_box { master |✔ }
  ➾ rspec                                                                           ruby-2.2.3
...........................................

Finished in 16.28 seconds (files took 2 seconds to load)
43 examples, 0 failures

Coverage report generated for RSpec to /Users/tonirib/turing/projects/4-mod/idea_box/coverage. 31 / 31 LOC (100.0%) covered.
```

### Provide a link to an example, if you have one, of a test that covers an 'edge case' or 'unhappy path'

-----

### Please feel free to ask any other questions or make any other statements below!
