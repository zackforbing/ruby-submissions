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
[Your Repo](https://github.com/lingtran/idea_box)

### Link to the Deployed Application
[Idea Box](http://my-ideabox.herokuapp.com/)

### Link to Your Commits in the Github Repository for the Project
[Your Commits](https://github.com/lingtran/idea_box/commits/master)

### Provide a Screenshot of your Application
![ling-tran](images/ling-tran.png)

## Completion

### Were you able to complete the base functionality?
* Yes

### Which extensions, if any, did you complete?
* Self-directed extension - escaping filtered search

### Attach a .gif, or images of any extensions work being used on the site.

```
function escapeSearch(ideas, behavior) {
  $('.search-field').delegate('.search-idea', behavior, function(e){
    if (behavior === 'keyup'){
      $('.search-field').attr('contentEditable', 'false');
      if (e.keyCode === 27){
        $(this).empty();
        $('.new-idea').show();
        ideas.show();
      }
    } else {
      $(this).empty();
      $('.new-idea').show();
      ideas.show();
    }
  })
}
```

### Link to a specific block of your code on Github that you are proud of
* Inline editing and search functionalities

### Link to a specific block of your code on Github that you feel not great about
* Why do you feel not awesome about the code? What challenges did you face trying to write/refactor it?
* https://github.com/lingtran/idea_box/blob/master/app/assets/javascripts/services_renderers_enablers.js.es6#L37-74
  - the enabler functions are not so DRY
* https://github.com/lingtran/idea_box/blob/master/app/assets/javascripts/formatters.js.es6#L11-50
  - the ```prepend``` and ```append``` functions are not so DRY
* Challenge of considering writing a dynamic function that does not rely so much on conditionals

### Attach a screenshot or paste the output from your terminal of the result of your test-suite running.
![ling-tran-test](images/ling-tran-test.png)

### Provide a link to an example, if you have one, of a test that covers an 'edge case' or 'unhappy path'

-----

### Please feel free to ask any other questions or make any other statements below!
