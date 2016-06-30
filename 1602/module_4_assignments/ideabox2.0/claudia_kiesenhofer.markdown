# Basics

### Link to the Project Specs
[Project Specs](https://github.com/turingschool/curriculum/blob/master/source/projects/revenge_of_idea_box.markdown)

### Link to the Github Repository for the Project
[My Repo](https://github.com/Claudia108/IdeaBox)

### Link to the Deployed Application
[My Application](https://stormy-waters-29939.herokuapp.com/)

### Link to Your Commits in the Github Repository for the Project
[My Commits](https://github.com/Claudia108/IdeaBox/commits/master)

### Provide a Screenshot of your Application
![IdeaBox](https://s3.amazonaws.com/mysubmissionimages/Screen+Shot+2016-06-30+at+11.10.37+AM.png)

## Completion

### Were you able to complete the base functionality?
* Yes, I finished all base functionality.

### Which extensions, if any, did you complete?
* I did not complete any extensions.

### Attach a .gif, or images of any extensions work being used on the site.

# Code Quality

### Link to a specific block of your code on Github that you are proud of
[Code example](https://github.com/Claudia108/IdeaBox/blob/0bb5cc1e98ed4f650cbafb6093f5bdc04255d2d6/app/assets/javascripts/display_ideas.js#L22)
* This is the beginning of a refactoring process which I wish I had more time for. The idea is that all events that will ultimatley change an idea would be defined in this container. Each of them would call the function that changes the event.

### Link to a specific block of your code on Github that you feel not great about
[Code example](https://github.com/Claudia108/IdeaBox/blob/f3e03d9a3de77348c90c1e00014b8a3c5ea6a63f/app/assets/javascripts/display_ideas.js#L105)
* Why do you feel not awesome about the code? What challenges did you face trying to write/refactor it?

### Attach a screenshot or paste the output from your terminal of the result of your test-suite running.

```
Claudias-MacBook-Pro-2:IdeaBox claudia$ rspec
..................

Finished in 13.47 seconds (files took 2.62 seconds to load)
18 examples, 0 failures

Coverage report generated for RSpec to /Users/claudia/Turing/4module/projects/IdeaBox/coverage. 28 / 28 LOC (100.0%) covered.
Claudias-MacBook-Pro-2:IdeaBox claudia$
```

### Provide a link to an example, if you have one, of a test that covers an 'edge case' or 'unhappy path'
```
RSpec.feature "user changes quality of idea" do
  scenario "user upvotes idea", js: true do
    idea = create(:idea)
    visit '/'
    expect(page).to have_content("swill")
    within("#idea-#{idea.id}") do
      find(".upvote").click
    end
    expect(page).to have_current_path('/')
    expect(page).to have_content("plausible")
    within("#idea-#{idea.id}") do
      find(".upvote").click
    end
    expect(page).to have_content("genius")
    within("#idea-#{idea.id}") do
      find(".upvote").click
    end
    expect(page).to have_content("genius")
  end
  ```
-----

### Please feel free to ask any other questions or make any other statements below!
