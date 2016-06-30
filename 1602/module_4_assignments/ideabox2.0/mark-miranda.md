# Mark Ideabox 2.0 Submission
[Project Spec](https://github.com/turingschool/curriculum/blob/master/source/projects/revenge_of_idea_box.markdown)

------

# Basics

### Link to the Github Repository for the Project
[Ideabox](https://github.com/notmarkmiranda/idea-box)

### Link to the Deployed Application
[Idea Thingy](http://ideathingy.herokuapp.com/)

### Link to Your Commits in the Github Repository for the Project
[Commits](https://github.com/notmarkmiranda/idea-box/commits/master)

### Provide a Screenshot of your Application
![ideabox](images/mark.png)

## Completion

### Were you able to complete the base functionality?
Yes!


### Which extensions, if any, did you complete?
I started tags, did not finish them.

### Attach a .gif, or images of anys extensions work being used on the site.

# Code Quality

### Link to a specific block of your code on Github that you are proud of
[search_box.js](https://github.com/notmarkmiranda/idea-box/blob/master/app/assets/javascripts/search_box.js)
* I feel like this is sometihng I was terrified about actually implementing. I'm proud of how clean it is and compact the code is.

### Link to a specific block of your code on Github that you feel not great about
[vote.js](https://github.com/notmarkmiranda/idea-box/blob/master/app/assets/javascripts/vote.js)

* I feel like I could've refactored this into at least one less function

### Attach a screenshot or paste the output from your terminal of the result of your test-suite running.
```
[idea-box] (master) rspec

Idea validations
  should validate that :title cannot be empty/falsy
  should validate that :body cannot be empty/falsy
  should have many idea_tags
  should have many tags through idea_tags

IdeaTag validations
  should belong to idea
  should belong to tag

Tag validations
  should validate that :name cannot be empty/falsy
  should have many idea_tags
  should have many ideas through idea_tags

post /api/v1/ideas
  POST#create
  POST#create, with one tag
  POST#create, with two tags
  POST#create, with three tags

delete /api/v1/ideas
  DELETE#destroy

update /api/v1/ideas - happy paths
  PATCH#update - +1
  PATCH#update - -1

update /api/v1/ideas - sad paths - 1
  PATCH#update - -1
  PATCH#update - +1

get /api/v1/ideas
  GET#index

Finished in 1.01 seconds (files took 4.61 seconds to load)
19 examples, 0 failures
```

### Provide a link to an example, if you have one, of a test that covers an 'edge case' or 'unhappy path'

[Rating not impacted by invalid ratings](https://github.com/notmarkmiranda/idea-box/blob/d60803626433810069a01298ed61aaf3e66b7826/spec/requests/user_updates_an_idea_spec.rb#L24-L28)

-----

### Please feel free to ask any other questions or make any other statements below!
