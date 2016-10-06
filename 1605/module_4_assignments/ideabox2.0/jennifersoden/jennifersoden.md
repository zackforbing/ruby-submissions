# Ideabox 2.0 Submission Form
[Project Spec](https://github.com/turingschool/curriculum/blob/master/source/projects/revenge_of_idea_box.markdown)


------

# Basics

### Link to the Github Repository for the Project
[Your Repo](https://github.com/MsJennyGiraffe/idea_box)

### Link to the Deployed Application
[Your Application](http://buckets-of-ideas.herokuapp.com/)

### Link to Your Commits in the Github Repository for the Project
[Your Commits](https://github.com/MsJennyGiraffe/idea_box/commits/master)

### Provide a Screenshot of your Application
![spacejam](http://i67.tinypic.com/m125g.png)

## Completion

### Were you able to complete the base functionality?
No

* If not, list what functionality is missing.
Missing
* Body truncation for ideas
* Thumbs
* Search


### Which extensions, if any, did you complete?
None

### Attach a .gif, or images of any extensions work being used on the site.
N/A

# Code Quality

### Link to a specific block of your code on Github that you are proud of

https://github.com/MsJennyGiraffe/idea_box/blob/master/app/assets/javascripts/idea_index.js#L10

* Why were you proud of this piece of code?
  * I'm proud of this code because it is the result of the first time I tried to refactor code, and I think it turned out fairly clean. I was really afraid to break out a long method that wasn't named and was doing far too much, because it also included the ajax call, but I am happy with the way it turned out.

### Link to a specific block of your code on Github that you feel not great about

https://github.com/MsJennyGiraffe/idea_box/blob/master/app/assets/javascripts/idea_service.js#L40-64

* Why do you feel not awesome about the code? What challenges did you face trying to write/refactor it?

  * I don't like how repetitive it is, but I couldn't think of a way to change the idea title/body dynamically, and I send only one at a time. This is probably an issue with how I chose to the structure of the editable content, I'm sure there is a better way, and I'd love to look into it.

### Attach a screenshot or paste the output from your terminal of the result of your test-suite running.

Finished in 0.49334 seconds (files took 1.41 seconds to load)

7 examples, 0 failures

### Provide a link to an example, if you have one, of a test that covers an 'edge case' or 'unhappy path'

https://github.com/MsJennyGiraffe/idea_box/blob/master/spec/requests/api/v1/ideas_controller_spec.rb#L68-84

-----

### Please feel free to ask any other questions or make any other statements below!
