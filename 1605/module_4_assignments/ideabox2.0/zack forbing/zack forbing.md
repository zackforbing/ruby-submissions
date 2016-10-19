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
[Idea Box JS](https://github.com/zackforbing/idea_box_js)

### Link to the Deployed Application
[Idea Box JS on Heroku](https://zacksideabox.herokuapp.com/)

### Link to Your Commits in the Github Repository for the Project
[My Commits](https://github.com/zackforbing/idea_box_js/commits/master)

### Provide a Screenshot of your Application
[idea box](images/ideabox.png)

## Completion

### Were you able to complete the base functionality?
Yes I was, aside from testing.

### Which extensions, if any, did you complete?
none. I attempted sorting, but ran out of time.

### Attach a .gif, or images of any extensions work being used on the site.

# Code Quality

### Link to a specific block of your code on Github that you are proud of
[the `stringTruncate` function.](https://github.com/zackforbing/idea_box_js/blob/c1d221bbbf63f76986e853b190a74ab658652bc2/app/assets/javascripts/idea_box.js#L23)
I liked this method because of the qualities of the `lastIndexOf` function. the first arg is a specific character to look for, and the second arg is the index where you want it to begin looking for that character. it then traverses the string backwards from that index until it finds the character. pretty neat!

[the `updateIdea` function.](https://github.com/zackforbing/idea_box_js/blob/c1d221bbbf63f76986e853b190a74ab658652bc2/app/assets/javascripts/idea_box.js#L95)
As I'm sure you're aware, Birdeck was a BIG help in getting me started on this project, and this method was the first that I really had to craft on my own. figuring out the DOM traversal for this was also difficult, as I initially tried to run it at the beginning of the file, but at that point there were not any Ideas on the page yet. I could have used Event Delegation, but ultimately I decided to move the function to the singular and group `renderIdea` functions along with upvote/downvote through the `addIdeaUpdateListeners` function.

[the `searchFilter` function.](https://github.com/zackforbing/idea_box_js/blob/c1d221bbbf63f76986e853b190a74ab658652bc2/app/assets/javascripts/idea_box.js#L147)
Regis helped Matt Campbell and I build this one. I just really love the `.on("keyup")` listener. The immediate gratification is so satisfying.

### Link to a specific block of your code on Github that you feel not great about
[the `addIdeaUpdateListeners` function.](https://github.com/zackforbing/idea_box_js/blob/c1d221bbbf63f76986e853b190a74ab658652bc2/app/assets/javascripts/idea_box.js#L63)
I don't necessarily feel bad about this per se, but it just doesn't feel like good use of JS. it doesn't save any lines by the time I'm done writing it, and it's one more function to track down to someone new looking at my code. but I felt worse about leaving the render functions each with a list of the same three functions.

[the createIdeaHTML function.](https://github.com/zackforbing/idea_box_js/blob/c1d221bbbf63f76986e853b190a74ab658652bc2/app/assets/javascripts/idea_box.js#L35)
again, I don't feel super bad about it, I'm just sure there has to be a better way to build an html response than bargain-basement concatenation.

### Attach a screenshot or paste the output from your terminal of the result of your test-suite running.
[](images/testsuite.png)

### Provide a link to an example, if you have one, of a test that covers an 'edge case' or 'unhappy path'
I do not have one.
-----

### Please feel free to ask any other questions or make any other statements below!

I'm pretty happy with this project. I didn't get as far as I would have liked with respect to testing and extensions, but that's okay. I plan to finish out my testing this weekend, as I know I need more experience with that. At the beginning of the week I was feeling bad about my decision to move forward to mod 4, but after this week, I know I made the right decision. JavaScript is awesome.

### Data Model

(5 points total.)

### User Flows

#### Viewing ideas

(10 points total.)

#### Adding a new idea

(15 points total.)

#### Deleting an existing idea

(15 points total.)

#### Changing the quality of an idea

(15 points total.)

#### Editing an existing idea

(20 points total.)

#### Idea Filtering and Searching

(15 points total.)

## Instructor Evaluation Points

### Specification Adherence

* **10 points**: The application consists of one page with all of the major functionality being provided by jQuery. There is no use of `format.js` in Rails. There is no use of unobstrusive JavaScript. There are no front-end frameworks used in the application. No approach was taken that is counter to the spirit of the project and its learning goals. There are no features missing from above that make the application feel incomplete or hard to use.

### User Interface

* **5 points** - The application is pleasant, logical, and easy to use. There no holes in functionality and the application stands on it own to be used by the instructor _without_ guidance from the developer.

### Testing

* **5 points** - Project has sporadic use of tests and multiple levels. Not all controller actions are tested. There are little or no attempts at integration testing.


### Ruby and Rails Quality

* **9 points** - Developer solves problems with a balance between conciseness and clarity and often extracts logical components. Developer can speak to choices made in the code and knows what every line of code is doing.

### JavaScript Style

* **8 points** - Application is thoughtfully put together with some duplication and no major bugs. Developer can speak to choices made in the code and knows what every line of code is doing.

### Workflow

* **10 points** - The developer effectively uses Git branches and many small, atomic commits that document the evolution of their application.
