# Ideabox 2.0 Submission Form
[Project Spec](https://github.com/turingschool/curriculum/blob/master/source/projects/revenge_of_idea_box.markdown)

# Basics

### Link to the Github Repository for the Project
[My Repo](https://github.com/Kealii/ideabox)

### Link to the Deployed Application
[My Application](https://ideabox-wong.herokuapp.com)

### Link to Your Commits in the Github Repository for the Project
[My Commits](https://github.com/Kealii/ideabox/commits/master)

### Provide a Screenshot of your Application
![ideabox](images/wong-ideabox.png)

## Completion

### Were you able to complete the base functionality?

All base functionality Complete.

### Which extensions, if any, did you complete?

No Extensions

# Code Quality

### Link to a specific block of your code on Github that you are proud of

Proud of [Search](https://github.com/Kealii/ideabox/blob/a3dd10e5616aa0ea6192373ad3bce3c2baf5ed39/app/assets/javascripts/ideas.js#L107)

#### Why were you proud of this piece of code?

This code accomplishes a lot while being both consistent with the rest of my code
and still being easily readable.

### Link to a specific block of your code on Github that you feel not great about

Not proud of [queries provided by Stack Overflow](https://github.com/Kealii/ideabox/blob/a3dd10e5616aa0ea6192373ad3bce3c2baf5ed39/app/controllers/ideas_controller.rb#L6)

#### Why do you feel not awesome about the code? What challenges did you face trying to write/refactor it?

I don't feel awesome about this because I didn't come up with the query myself. I was unsure of how to match both a
title and body and found through Stack that you could use arel_table Or.

### Attach a screenshot or paste the output from your terminal of the result of your test-suite running.

![Test Suite](images/wong-test.png)

### Provide a link to an example, if you have one, of a test that covers an 'edge case' or 'unhappy path'

[Example](https://github.com/Kealii/ideabox/blob/a3dd10e5616aa0ea6192373ad3bce3c2baf5ed39/spec/features/ideas_spec.rb#L82)
This test covers clicking the + button while rating is maxed.