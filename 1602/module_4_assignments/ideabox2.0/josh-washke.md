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
[Your Repo](https://github.com/jwashke/idea-box)

### Link to the Deployed Application
[Your Application](http://ideas-box.herokuapp.com/)

### Link to Your Commits in the Github Repository for the Project
[Your Commits](https://github.com/jwashke/idea-box/commits/master)

### Provide a Screenshot of your Application
![spacejam](https://s3-us-west-2.amazonaws.com/rails-misc-pictures/Screen+Shot+2016-06-30+at+10.47.45+AM.png)

## Completion

### Were you able to complete the base functionality?

* Yes

### Which extensions, if any, did you complete?

* Tagging, and sorting by quality

### Attach a .gif, or images of any extensions work being used on the site.

![GIF](http://g.recordit.co/8HuLPvgaZe.gif)

# Code Quality

### Link to a specific block of your code on Github that you are proud of
* Why were you proud of this piece of code?
```
app/assets/javascripts/handlers.js
```
```ruby
delegateClick: function(event) {
  var target = event.target;
  var id = target.id
  if (target.className.includes('deleteButton')) {
    this.deleteIdea(id);
  } else if (target.className.includes('thumbsUpButton')) {
    this.thumbsUpIdea(id);
  } else if (target.className.includes('thumbsDownButton')) {
    this.thumbsDownIdea(id);
  } else if (target.className.includes('ideaTitle')) {
    $(target).attr('contenteditable', 'true');
  } else if (target.className.includes('ideaBody')) {
    $(target).attr('contenteditable', 'true');
  }
},
```

Proud of this because originally I was attaching multiple event listeners to every idea on the page. When I was able to rewrite it to a single event listener for the entire block of ideas that depends on the event target to delegate the click event i was pretty excited.
### Link to a specific block of your code on Github that you feel not great about
* Why do you feel not awesome about the code? What challenges did you face trying to write/refactor it?

```
app/assets/javascripts/idea_service.js
```
```ruby
getIdeas: function() {
  $.getJSON("/api/v1/ideas").then(function(response) {
    var ideas = response.ideas
    ideas.forEach(function(idea) {
      if (idea.body.length > 100)
        idea.body = idea.body.substring(0, 100).split(" ").slice(0, -1).join(" ") + "...";
      var tags = idea.tags.map(function(tag) {
        var containsTag = tagList.tags.filter(function(oldTag) {
          return tag.name === oldTag.name;
        }).length > 0
        var newTag = new Tag(tag.name)
        if (!containsTag) {
          tagList.tags.push(newTag)
        }
        return newTag;
      })
      var newIdea = new Idea(idea.id, idea.title, idea.body, idea.quality, tags)
      ideaList.ideas.push(newIdea)
    });
    view.drawIdeas();
  });
},
```
its ugly and has too much going on. I tried to refactor but kept just breaking everything.

### Attach a screenshot or paste the output from your terminal of the result of your test-suite running.
```
Finished in 0.48944 seconds (files took 1.59 seconds to load)
27 examples, 0 failures, 1 pending
```
### Provide a link to an example, if you have one, of a test that covers an 'edge case' or 'unhappy path'
```
spec/models/idea_spec.rb
```
```ruby
context "with quality genius" do
  it "does not change the quality" do
    idea = create(:genius_idea)
    idea.cycle_quality_up
    expect(idea.quality).to eq("genius")
  end
end
```
-----

### Please feel free to ask any other questions or make any other statements below!
