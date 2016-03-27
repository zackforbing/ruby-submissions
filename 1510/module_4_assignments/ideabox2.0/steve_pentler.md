# Idea Box

### Link to the Github Repository for the Project
[GitHub Repo](https://github.com/stevepentler/IdeaBox)

### Link to the Deployed Application
[Live Link](https://pentler-ideas.herokuapp.com/)

### Link to Your Commits in the Github Repository for the Project
[Commits](https://github.com/stevepentler/IdeaBox/commits/master)

### Provide a Screenshot of your Application
![](http://g.recordit.co/jflg8dNj6L.gif)

## Completion

### Were you able to complete the base functionality?
All base functionality is complete.

### Which extensions, if any, did you complete?
Inline Editing(10)

### Attach a .gif, or images of any extensions work being used on the site.
![](http://g.recordit.co/Ov33UONm3n.gif)

# Code Quality

### Link to a specific block of your code on Github that you are proud of
- [qualityIdea](https://github.com/stevepentler/IdeaBox/blob/master/app/assets/javascripts/quality_idea.js#L30)
DRY after refactoring from seperate promote and demote methods.
- [searchIdea](https://github.com/stevepentler/IdeaBox/blob/master/app/assets/javascripts/search_idea.js#L1) : Well named, human-readable, abstracted code.
- [Controller Testing](https://github.com/stevepentler/IdeaBox/blob/master/test/controllers/ideas_controller_test.rb#L25)
Specific, realiable controller testing for create, update, and delete. Decent testing for idea promotion/demotion.

### Link to a specific block of your code on Github that you feel not great about
- [editIdea](https://github.com/stevepentler/IdeaBox/blob/master/app/assets/javascripts/edit_idea.js#L7): I tried to refactor this code on 5 seperate occassions, but kept running into a problem with the contentEditable function. I finally got it, but it still looks "chunky." I'm not a a fan of how much space the ideaParams take up, but they require a fair amount of local varaiables. 
- [Selenium Integration Test](https://github.com/stevepentler/IdeaBox/blob/master/test/integration/create_idea_test.rb): This isn't pretty, but I was excited to get Selenium working. I had trouble selecting specific elements.

### Attach a screenshot or paste the output from your terminal of the result of your test-suite running.

ideaBox ⚡ rake

Run options: --seed 50462

###### Running:

**************

Fabulous run in 14.942947s, 0.9369 runs/s, 4.3499 assertions/s.

14 runs, 65 assertions, 0 failures, 0 errors, 0 skips


### Provide a link to an example, if you have one, of a test that covers an 'edge case' or 'unhappy path'

- [Missing Validations](https://github.com/stevepentler/IdeaBox/blob/master/test/controllers/ideas_controller_test.rb#L53)

-----
