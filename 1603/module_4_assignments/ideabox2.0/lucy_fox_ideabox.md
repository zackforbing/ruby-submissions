## Lucy Fox, Idea Box

### Important Links:

[Github Repo](https://github.com/lucyfox4131/idea_box.git)

[Production Link](https://all-the-ideas.herokuapp.com/)

[Github Commits](https://github.com/lucyfox4131/idea_box/commits/master)

### Screenshot:
[Screenshot](http://i.imgur.com/N0awFGq.png)

### Completion:
##### Were you able to complete the base functionality?
I was able to complete the bas functionality

##### Which extensions, if any, did you complete?
I did not complete any extensions

### Code Quality:
##### Link to a specific block of code on Github that you are proud of
 [Helper Methods for Upvote/Downvote Quality](https://github.com/lucyfox4131/idea_box/blob/master/app/assets/javascripts/quality_helpers.js)

##### Why were you proud of this piece of code?
I found that the upvote and downvote functions had quite a few similarities. I'm proud of the code I was able to refactor to pull out some of the common code between these two features. It feels like a good step towards learning how to refactor code.

##### Link to a specific block of your code on Github that you feel not great about
[Delete A Row](https://github.com/lucyfox4131/idea_box/blob/master/app/assets/javascripts/delete.js)

##### Why do you feel not awesome about the code? What challenges did you face trying to write/refactor it?
I struggled with the Delete function. I don't feel extremely good about deleting the row right without having some reliance on the ajax call. However, I struggled with "This" quite a bit and still feel I don't understand it quite as well as I should. Especially in terms of scope within different functions.

##### Attach a screenshot or past the output from your terminal of the result of your test-suite running.
[RSpec and Rake Teaspoon Tests Running](http://i.imgur.com/jtUtk8g.png)

##### Provide a link to an example, if you have one, of a test that covers an 'edge case' or 'unhappy path'
[Github Link - Sad Path Test - Idea won't be created without a title](https://github.com/lucyfox4131/idea_box/blob/master/spec/requests/api/v1/ideas_controller_spec.rb)
