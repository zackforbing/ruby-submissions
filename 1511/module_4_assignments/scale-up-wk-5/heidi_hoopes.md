# Scale Up Submission Form

## Basics

### Link(s) to the PRs or Issues You Picked Up
- [#71 Compare New Relic](https://github.com/LookingForMe/lookingfor/issues/71)
- [#80 Database Load Testing](https://github.com/LookingForMe/lookingfor/pull/80)
- [#82 Capitalization for technologies](https://github.com/LookingForMe/lookingfor/issues/82)
- [#92 Endpoint for technologies](https://github.com/LookingForMe/lookingfor/issues/92)
- [#97 Add scoping by technology to recent jobs controller](https://github.com/LookingForMe/lookingfor/issues/97)

### Summarize what you worked on the last two weeks
I started off by comparing various methods of obtaining performance data for an app and its database, and concluded in addition to keeping New Relic that we also needed a method to generate data. I created a rake task that would do this, and documented all of this. After this, I jumped into providing endpoints for the front end team, refactoring the recent_jobs index method to be able to respond to multiple scopes. I also provided a lot of QA to my teammates on both the back-end and front-end teams.

### Hours logged this week?
About 34

### Talk about something from the pre-work that you didn't know about before this week.
I was not aware of the technique of using Sinatra to create a fake service for testing purposes. It's interesting that when we learned Sinatra in mod 2, it was in a context of "no one really uses this except when they do" and I am slowly learning what the "when they do" part entails. In mod 3 I used Sinatra on a Rails app to create an endpoint to hit for statistics, which was also interesting. 

While I didn't get around to pulling an issue on Boxtrot to test using Sinatra, I did look over the ones that were already implemented.

### Link to blog post(s) submitted
Will be providing this link before Tues am.

### Discuss: your experience doing PR reviews and getting PR feedback
I was curious what this experience would be like since I thought doing group projects would have prepared me for a bigger team. However, I found that I was often lacking context for a PR I was supposed to review, especially early in the project when I was working on entirely different topics. By forcing myself to switch contexts and thoroughly read and test the PR, it left me in a better place when I did move onto issues more relevant to the whole team.

While I tried to make my PRs as good as possible, it was a relief knowing that someone would look over it again for me. However, even still people missed things they should've caught (though I'm sure I did the same).

### Discuss: your experience doing daily stand ups
It was hard knowing how much detail to provide, how long to go, and how much to interrupt/interact with other people's reports. I'm sure time and experience will give a feel for interacting in a standup. I also felt like talking about my code purposefully was a good experience as it would probably help me in interviews.

### What features would you like to see LookingFor have in the future?
I would prefer to see it have analytics before it had user-input (like from mentors or Lia). I think it's more likely we'd learn something interesting from the analytisc than create a tool that people will reliably use, especially if they already have a workflow.

However, user accounts probably are the next step, if nothing else to drive out common features on job sites, like a preferred stack and location. 

I am curious to see how Elastic Search evolves. I wonder if AWS' elastic search could help get around some problems.

### Please feel free to ask any other questions or make any other statements below!

-----

Instructor Evaluation:

You really threw yourself into this project. You were very visible commenting on PR reviews, comments, and on slack. It's obvious you were invested in this and you were an asset to the team. Also, want to give you props for taking it upon yourself to QA other's work. That's a really important job that's easy to brush off when you just want to build features. Good job!

Final Score: 110/150 (reflects 0 score for blog post, will be updated when blog post is submitted)

Points: (max 150)

### Blog Post (40 Points)  
  <!--* 40: Developer has >= 2 blog posts documenting something they have worked on for their independent study or has one in depth blog post.-->
  <!--* 25: Developer has one blog post less than 500 words long.-->
  * 0: Developer created no blog posts. (Scoring this as 0 for now, will adjust final score once the blog post is submitted! Recognize that you have an extension, so do not fret about the blog scoring)

### Team Participation (40 points)

  * 40: Developer participated daily in stand ups with the group (remote or in person). Developer was able to speak to their work in stand ups in a way that was clear and informative. Developer was involved in pull request reviews.

### Hourly Work (30 points)

  * 30: Developer logged 7 to 8 hours per working day. Developer can speak to work completed during those hours.

### Risk Taking and Creativity (40 points)

  Instructor/Developer will select one feature in the project to review for this section of the rubric.

  * 40: Developer pushed themselves and their team by taking risks which is demonstrated by a delivered feature or well documented spike. Developers explored concepts and technologies outside the scope of the curriculum.
