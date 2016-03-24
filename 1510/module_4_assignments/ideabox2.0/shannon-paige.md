# Ideabox 2.0 Submission Form
[Project Spec](https://github.com/turingschool/curriculum/blob/master/source/projects/revenge_of_idea_box.markdown)

# Basics

### Link to the Github Repository for the Project
[My Amazing Repo](https://github.com/ShannonPaige/idea-box)

### Link to the Deployed Application
[My Wonderful Application](https://idea-box-shannon.herokuapp.com/)

### Link to Your Commits in the Github Repository for the Project
[My Awesome Commits](https://github.com/ShannonPaige/idea-box/commits/master)

### Provide a Screenshot of your Application
![idea-box screenshot](images/shannon.png)

## Completion

### Were you able to complete the base functionality?
* Yep

### Which extensions, if any, did you complete?
* Inline idea editing
* Sorting

### Attach a .gif, or images of any extensions work being used on the site.
* Inline idea editing:
![idea-box inline](images/shannon-inline.gif)

* Sorting:
![idea-box sorting](images/shannon-sort.gif)

# Code Quality

### Link to a specific block of your code on Github that you are proud of
* [Re-usable Code A](https://github.com/ShannonPaige/idea-box/blob/master/app/assets/javascripts/render_or_hide_idea.js#L33)
and [Re-usable Code B](https://github.com/ShannonPaige/idea-box/blob/master/app/assets/javascripts/all_ideas.js#L5): By sending the sort order to my getIdeas method and then clearing the entire div before I render the ideas, I was able to use the same code for default sort and the sort by quality functionality.

### Link to a specific block of your code on Github that you feel not great about
* [DOM Traversal](https://github.com/ShannonPaige/idea-box/blob/master/app/assets/javascripts/search_ideas.js#L6-L7): WTF am I doing here? I couldn't figure out a better way to grab this data.
* [Duplicate Code](https://github.com/ShannonPaige/idea-box/blob/master/app/assets/javascripts/edit_ideas.js#L38-L45): There's a lot of duplication with the makeEditable method above, but they had enough subtle differences that I couldn't seperate them.

### Attach a screenshot or paste the output from your terminal of the result of your test-suite running.
![idea-box screenshot](images/shannon-testSuite.png)

### Provide a link to an example, if you have one, of a test that covers an 'edge case' or 'unhappy path'
* I don't think I had any, since I didn't validate on Title or Body. That's the only part the user had a
choice on.

-----

### Please feel free to ask any other questions or make any other statements below!
* I feel like I set this project up wrong, cause I had such issues traversing the DOM to get data, sending it to an API, and then traversing again to replace the data. It seems like a smell to me that I should have done a better job storing objects in my javascript?
