# Ideabox 2.0 Submission Form
[Project Spec](https://github.com/turingschool/curriculum/blob/master/source/projects/revenge_of_idea_box.markdown)

# Basics

### Github Repository
[Revenge of Ideabox](https://github.com/adamhundley/revenge_of_idea_box)

### Production Link
[Idea Lightbulb](https://idea-lightbulb.herokuapp.com/)

### Link to Your Commits in the Github Repository for the Project
[ Commit History](https://github.com/adamhundley/revenge_of_idea_box/commits/master)

### Screenshot
![Idea Lightbulb](images/idea-lightbulb.png)

## Completion

### Were you able to complete the base functionality?
* Yes.

# Code Quality

### Link to a specific block of your code on Github that you are proud of
* [happy code](CODECLIMATE_REPO_TOKEN=7ee4764d4423144e2c116494a5a7971a4ccf97536125f0c96087a87b2503d1c4 bundle exec rake)
* I am proud of this whole file. It originally had so much duplication in it that I wanted to vomit. I think the original file was around 200 lines long. I had never refactored js code before and with this I was able to write some functions that could be reused and move things around way more logically. It was very rewarding to see the final product.

### Link to a specific block of your code on Github that you feel not great about

* [not so happy code](https://github.com/adamhundley/revenge_of_idea_box/blob/master/app/assets/javascripts/voteAndDeleteIdeas.js#L11)
* I would've loved to divide some of this out into separate functions as well as re-use code between upvote and downvote, but ran into issues with the return value from the post request as well knowing what the actual idea was. In hindsight, I could've made a vote action and cut down on a lot of duplication.

### Attach a screenshot or paste the output from your terminal of the result of your test-suite running.
```

revenge_of_idea_box💀 (master) ⎆ rspec
...............................

Finished in 9.37 seconds (files took 14.72 seconds to load)
32 examples, 0 failures

revenge_of_idea_box💀 (master *) ⎆ be rake teaspoon
Starting the Teaspoon server...
Teaspoon running default suite at http://127.0.0.1:64491/teaspoon/default
...

Finished in 0.01300 seconds
3 examples, 0 failures
```

### Provide a link to an example, if you have one, of a test that covers an 'edge case' or 'unhappy path'

* [unhappy path](https://github.com/adamhundley/revenge_of_idea_box/blob/master/spec/features/user_edits_title_and_body_spec.rb#L30)
* An issue I was running into was once I edited a body, it wasn't being truncated anymore. This test verified truncation was happening after an edit if it hadn't been truncated on page load

### Please feel free to ask any other questions or make any other statements below!

I really enjoyed this project and being able to learn so much about Javascript in such a short period of time. I finally feel comfortable writing it and not just copy pasta from the internet.
