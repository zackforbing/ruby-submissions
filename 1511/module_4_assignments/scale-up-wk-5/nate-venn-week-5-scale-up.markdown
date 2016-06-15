# Scale Up Submission Form

## Basics

### Link(s) to the PRs or Issues You Picked Up
-[#49 testing with enzyme/mocha](https://github.com/LookingForMe/lookingForFrontEnd/pull/49)

-[#46 Deploy to Heroku](https://github.com/LookingForMe/lookingForFrontEnd/pull/46)

-[#43 Change files to PascalCase](https://github.com/LookingForMe/lookingForFrontEnd/pull/43)

-[#25 move functions into modules](https://github.com/LookingForMe/lookingForFrontEnd/pull/25)

-[#14 move custom to css folder in root](https://github.com/LookingForMe/lookingForFrontEnd/pull/14)

### Summarize what you worked on the last two weeks

* I started off with Brian to setup bootstrap for the app and create a nav bar componenet
and serach bar componenet.
* I refactored all components into thier own modules so that I could isolate individual components to be tested.
Jest, facebooks testing suite, but found the syntax and structure too
unfamiliar to learn in a short period of time.
* I then went to AirBnB's testing framework which allows libraries that I was more familiar
with like Mocha and Chai. I was able to make some basic assertions one state and content on most
components. Unfortunately with all the quick changes happening to our React
component, after one day half of the tests were breaking.
* I was then pulled off to get our app pushed to Heroku. This caused a few
issues since Heroku doesnt serve static sites. Many blog posts later and
numerous trial and error runs, I finally got Heroku tricked into thinking that we
have a non-static app. It took adding a serve to the app (express), creating a
Procfile with just one line of code, creating a new script in package.json, and
a production webpack config file.
* Lastly I went back to testing and fixed all the broken tests and added a few
more.

### Hours logged this week?
* 32.5

### Talk about something from the pre-work that you didn't know about before this week.
* I learned the difference between state and props. The big difference is that
state lives close to all the logic and gets updated/changed on a UI event.
Props is the data from the state that gets passed down to child components and
should never be changed.

### Link to blog post(s) submitted
* Blog post [link](http://natevenn.github.io/2016/06/13/react-flux-patterns.html)

### Discuss: your experience doing PR reviews and getting PR feedback
* This was a positive experience. I found that getting extra eyes on my worked
helped me realize some of my shortcomings. Such as not paying close attention
to detail. I also learned how to do a more thorough review and give better
feedback based on all the great feedback I was given. In order to give good
feedback you have to take your time on reviewing others PRs.

### Discuss: your experience doing daily stand ups
* It was a great way to communicate what everyone on the team is working on,
  will work on, and any blockers they have. It allowed for more colaboration and
  redirect energy into what was priority.

### What features would you like to see LookingFor have in the future?
* I think one of the coolest features to get into the app would be
  ElasticSearch.

### Please feel free to ask any other questions or make any other statements below!
* This was one of my favorite group projects. We had a great team and the work
  pace was awesome. I hope you continue this in future cohorts.

-----

Instructor Evaluation:

Tackling testing and deployment for this was a big job -- you did a great job trouble shooting and figuring out how to do what was needed here. It was obvious that you were very involved with the team, we saw you popping up in PR reviews and Slack conversations a lot. It's great to see a team working together so well this late in the program when everyone is tired and the end is in sight. Good job!

**Final Points: 110/150 (blog post score of 0. submit blog post by tuesday AM for this score to be updated.)**

Points: (max 150)

### Blog Post (40 Points)
  <!--* 40: Developer has >= 2 blog posts documenting something they have worked on for their independent study or has one in depth blog post.-->
  <!--* 25: Developer has one blog post less than 500 words long.-->
  * 0: Developer created no blog posts. **(score of 0. submit blog post by tuesday AM for this score to be updated.)**

### Team Participation (40 points)

  * 40: Developer participated daily in stand ups with the group (remote or in person). Developer was able to speak to their work in stand ups in a way that was clear and informative. Developer was involved in pull request reviews.

### Hourly Work (30 points)

  * 30: Developer logged 7 to 8 hours per working day. Developer can speak to work completed during those hours.

### Risk Taking and Creativity (40 points)

  Instructor/Developer will select one feature in the project to review for this section of the rubric.

  * 40: Developer pushed themselves and their team by taking risks which is demonstrated by a delivered feature or well documented spike. Developers explored concepts and technologies outside the scope of the curriculum.
