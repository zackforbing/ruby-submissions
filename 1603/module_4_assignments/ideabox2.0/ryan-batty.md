# Ideabox 2.0 Submission Form
[Project Spec](https://github.com/turingschool/curriculum/blob/master/source/projects/revenge_of_idea_box.markdown)

------

# Basics

[Idea Box - Repo](https://github.com/Riizu/idea_box)

[Idea Box - Heroku](https://boiling-dawn-58829.herokuapp.com/)

[Idea Box - Commits](https://github.com/Riizu/idea_box/commits/master)

### Screenshot
![idea_box](http://i.imgur.com/cMG3dp8.png)

## Completion

### Were you able to complete the base functionality?
* The only missing requirement was truncation of idea bodies.

### Extensions
* N/A - No extensions were completed

# Code Quality

### Proud Moment: [Idea Quality Change](https://github.com/Riizu/idea_box/blob/master/app/models/idea.rb)
* I like this piece of code because I felt it was a very robust solution to handling upvoting/downvoting with enums. It allows for easy extendability and additional requirements.

### Weak Moment: [generateIdeaHtml function](https://github.com/Riizu/idea_box/blob/master/app/assets/javascripts/idea.js)
* While simple, I feel like this method is needlessly long. It seems like it could be shortened in some manner with dynamic generation of tags, but adding that seemed to go against the KISS principle.

### Test Suite: [Rails/Teaspoon Album](http://imgur.com/a/XsmDU)

### Sad Path Test: [Search Spec Failure](https://github.com/Riizu/idea_box/blob/master/spec/features/visitor_can_search_ideas_spec.rb)

-----

### Thoughts:
> Overall, I feel this was a successful project. While I wish I had been able to get extensions, as I definitely feel capable of completing them, the First Week slowness was definitely in effect, and motivation ended up being a challenge. I also think that the idea (hah puns) of the project itself was hard to get excited about, but thats okay - thats a common thing in real life.
