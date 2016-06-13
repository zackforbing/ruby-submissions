# Scale Up Submission Form

## Basics

### Summarize the work you completed over the last two weeks

My original plan was to re-create a more focused version of Google Docs. Unfortunately,
this proved to be a lot more work than I expected along with job related activities taking
up a good portion of my time. Knowing this, I decided to pivot towards something that
would allow me to learn the ins and outs of React. Specifically, learning about
writing React using ES6, implementing a state container and persisting data. My next
inspiration ended up being Trello, which I was able to create a MVP version of. During
these two weeks I have been able to not only grasp many of the concepts behind React,
but also wrap may head around Flux architecture, ES6 features that I wasn't aware
of and the many different ways you could structure a React app. Even with the
job hunt going on, I felt I learned an invaluable amount of JS and React that I
can use to begin to build dynamic Front Ends that can consume data from a variety
of resource (localStoarge, Firebase, Rails API, etc..)

### Link(s) to Your Work

 - [Github Repo](https://github.com/julsfelic/kanban-app)
 - [Production](http://julsfelic.github.io/kanban-app/)

### Hours logged this week?

Mon: 1:36
Tue: 4:02
Wed: 6:32
Thu: 5:19
Fri: 11:43
Sat: 9:21
Sun: 6:51

### Talk about something that you didn't know about before this week.

What the heck Flux was. All I can remember is always reading that it is a
'predictable state container'. After digging and reading and implementing a
Flux architecture myself I 'think?' finally grok what it does and why we would
want to use it. The key take away is that React is just the view layer, and though
you can handle state from your components, when a project begins to get bigger
it becomes tough to reason about your state. The views should just display the
views and nothing else. With a flux architecture you have a uni-directional
state flow that consists of actions -> dispatcher -> store -> view. It is another
pattern (like MV* patterns) that makes debugging and reasoning about your state
a little easier and takes away the responsibility of maintaining state from the
view.

### Link to blog post(s)

**Coming Tuesday Morning!**

### Discuss: your experience doing PR reviews and getting PR feedback

Doing PR reviews is a slightly weird thing when you aren't familiar with what
the code base is. While looking at a PR that Scott had put up, I had the hardest
time reasoning about the code until I just went to him to discuss the PR in person.
I can see how being very explicit about the pieces of code you want looked at is
beneficial to helping the reviewer quickly jump in a give feedback.

I didn't receive much in the way of feedback since I did decided to switch up
my Scale Up, but when Allan would look at some of my PR's he would run into similar
issues of navigation and understanding the code base.

My main takeaway is to look more into good PR practices to allow for better
communication between parties.

### Discuss: your experience doing daily stand ups

I loved it! Especially since I have been mad stressing with all the job related
things it allowed me to get off my chest what are my blockers and what I am trying
to accomplish with my project. Having others go through similar hurdles reminded
me that my struggles are not unique and that this is just how it is. I really hope
I end up working for a company that has some form of stand up.

### Please feel free to ask any other questions or make any other statements below!

Statement #1 - Programming is hard!
Statement #2 - It has been a pleasure having ya'll as instructors!
Statement #3 - I need 136 points to not take the final. That would be nice.
Statement #4 - Programming is hard!

-----

# Instructor Evaluation:

Great job! You did a great job of adjusting the scope and scale of your project as you dug into the work. It's a great example of the agile idea that **working** software is more important than cranking out half-baked features. The trello-type board you made is nicely executed.

Final Score: 110/150 (score will be adjusted when blog post is submitted)

Points: (max 150)

### Blog Post (40 Points)  

  <!--* 40: Developer has >= 2 blog posts documenting something they have worked on for their independent study or has one in depth blog post.-->
  <!--* 25: Developer has one blog post less than 500 words long.-->
  * 0: Developer created no blog posts. (has an extension on blog post, score of 0 will be updated when blog post is turned in)

### Team Participation (40 points)

  * 40: Developer participated daily in stand ups with the group (remote or in person). Developer was able to speak to their work in stand ups in a way that was clear and informative. Developer was involved in pull request reviews.

### Hourly Work (30 points)

  * 30: Developer logged 7 to 8 hours per working day. Developer can speak to work completed during those hours.

### Risk Taking and Creativity (40 points)

  Instructor/Developer will select one feature in the project to review for this section of the rubric.

  * 40: Developers pushed themselves and their team by taking risks which is demonstrated by a delivered feature or well documented spike. Developers explored concepts and technologies outside the scope of the curriculum.
