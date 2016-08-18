#Ideabox 2.0 Submission Form

* [Project Spec](https://github.com/turingschool/curriculum/blob/master/source/projects/revenge_of_idea_box.markdown)
* [GitHub Repo](https://github.com/ErinGreenhalgh/ideabox)
* [Deployed Application](http://ideasfordays.herokuapp.com/)
* [My Commits](https://github.com/ErinGreenhalgh/ideabox/commits/master)

###My Application

![IdeaBox](http://i.imgur.com/Ibb8VEh.png)

###Completion

Base functionality is complete, with the exception of truncating the idea to the closest 100 words.
I did not complete any extensions.

###Code Quality

[Code I am proud of](https://github.com/ErinGreenhalgh/ideabox/blob/cce5a6fc8b173740c6b04e3d9cc307b8a6262349/app/assets/javascripts/update_quality.js#L3-L35)
####Why were you proud of this piece of code?
I was happy with figuring out how to send the parameters of the quality to the ajax call. It was conceptually challenging for me to figure out how this should work, since the quality has to be sent to the ajax call but it can't be grabbed from the page. It was new to me to store the logic of which quality to send to the ajax call in the javascript instead of in the model, as was my first instinct. This is not super DRY but I was happy to figure this part out.

[Code I don't feel great about](https://github.com/ErinGreenhalgh/ideabox/blob/cce5a6fc8b173740c6b04e3d9cc307b8a6262349/app/assets/javascripts/ideas.js#L51-L91)

####Why do you feel not awesome about the code? What challenges did you face trying to write/refactor it?
This code is not DRY at all and I know it could be refactored. I would like to have one helper function that toggles the 'contenteditable' class on whatever attribute you pass to it, instead of having essentially the same function with on different parameter. In the same way, the code for updating the title and body is nearly identical, so it would be nice to just have one function that I could pass 'title' or
'body' to. I did not refactor this code because I ran out of time, and wanted to make sure that I got all the base functionality completed first.

###Test Suite
![Test Suite](http://i.imgur.com/cH2bcKh.png)

###Edge Case/Sad Path Test
Yikes I don't really have any sad path tests :/
