# Scale Up Submission Form

## Basics

### Link(s) to the PRs or Issues You Picked Up
-[#70 Research spike adding Elasticsearch](https://github.com/LookingForMe/lookingfor/issues/70)
  - The original issue to look into the feasibility of this project.

-[#83 Database import task](https://github.com/LookingForMe/lookingfor/issues/83)
  - Actually implementing code to copy all rows from the existing database into an Elasticsearch database.

### Summarize what you worked on the last two weeks

I'll try to do this briefly. In the last couple of weeks I did a large amount of research into Elasticsearch, the perks it brings to a project, and the obstacles faces by adding it in.

I fell down a couple different rabbit holes in the first week. ES is just huge, there are multiple ways to do anything and everything. This meant that I ended up spending a huge amount of time trying to figure out how to alter out current Model structure to fit the Elasticsearch-Models gem before realizing that we didn't actually need that at all. The task that I wrote took care of indexing the information correctly, so we didn't need to worry about how models talked to the PostgreSQL database.

In the second week is when I improved the import task, wrote an `after_save` task to copy in new jobs, and then fought with Heroku to try and deploy this thing.

I made my own copy of the project to put on Heroku, and added the Bonsai add-on and tried to get the two to talk.

I was unsuccessful.

### Hours logged this week?
28:30
### Talk about something from the pre-work that you didn't know about before this week.

I started some of my research into Elasticsearch as part of my pre-work. I knew that in the demo we were given we curl'ed queries into the database, but I didn't realize that's because ES is basically a packaged up API. It was cool to piece that in with what I knew about API's and JSON objects to make a little more sense of how ES works.

### Link to blog post(s) submitted

[Do you actually need Elasticsearch](https://medium.com/@brennanholtzclaw/do-you-really-need-elasticsearch-or-do-your-active-record-queries-just-suck-79aa45345506#.txhaebwgb)

I can totally write a second blog, but this one just kept going. I'm pretty verbose usually, but this is over 12-hundred words. If you'd like a second one, I have the outline and rough draft, I can have it in by Tuesday morning.

### Discuss: your experience doing PR reviews and getting PR feedback
This was pretty weird for me. I was in a weird place by trying to add my own feature to the project and not having anyone else working on something connected.

Initially I was excited to get to do my own thing since it's kind of what I wanted in the first place, but in the end it sort of isolated me from the group. I wasn't always able to answer questions the front-end team had because of a couple PR's that had HUGE comment logs that I wasn't keeping up with. It definitely took extra time to catch up with what was going on, and at the end of week-two I consciously put my work aside and worked on pairing with other team members to try and get some issues resolved and merged in.

### Discuss: your experience doing daily stand ups

I liked stand ups way more than I thought I would. I worked on a team that did, what I now know were, terrible stand ups. The 30ish minutes let me feel like I was still a part of the team, field questions about what I was doing, and clarify any questions I might have been asked the day before that I wanted to know the answer to.

Stand ups also act as a gentle push to keep you motivated. More than once I would get frustrated and want to stop and think, "What have I got to show for stand up tomorrow?" If the answer was unacceptable I just had to keep going.

### What features would you like to see LookingFor have in the future?

[Elasticsearch](http://giphy.com/gifs/black-and-white-sad-L8Ni9T9cgk716)

### Please feel free to ask any other questions or make any other statements below!

How would you like me to deal with this partial branch going forward? I am writing up some (probably too detailed) documentation right now, that I thought I would leave in the issue on the project.

Also, I really can have another blog written really quickly, but you had said something about one big one or two smaller ones... That guy is really big.

-----

Instructor Evaluation:

Points: (max 150)

### Blog Post (40 Points)  
  * 40: Developer has >= 2 blog posts documenting something they have worked on for their independent study or has one in depth blog post.
  * 25: Developer has one blog post less than 500 words long.
  * 0: Developer created no blog posts.

### Team Participation (40 points)

  * 40: Developer participated daily in stand ups with the group (remote or in person). Developer was able to speak to their work in stand ups in a way that was clear and informative. Developer was involved in pull request reviews.
  * 30: Developer participated daily in stand ups with the group (remote or in person). Developer has difficulty speaking to their work in stand ups.
  * 20: Developer was absent for 1 stand up, did not participate actively in code reviews.
  * 0: Developer was absent for > 1 standup, did not participate actively in lessons and peer reviews. Did not deliver or almost deliver any features.

### Hourly Work (30 points)

  * 30: Developer logged 7 to 8 hours per working day. Developer can speak to work completed during those hours.
  * 20: Developer logged between 6 to 7 hours per working day
  * 5: Developer logged < 6 hours per working day OR developer is unable to speak to or justify hours logged.
  * 0: Developer did not track hours

### Risk Taking and Creativity (40 points)

  Instructor/Developer will select one feature in the project to review for this section of the rubric.

  * 40: Developer pushed themselves and their team by taking risks which is demonstrated by a delivered feature or well documented spike. Developers explored concepts and technologies outside the scope of the curriculum.
  * 20: Developer pushed themselves and their team by taking risks which is demonstrated by an almost delivered feature whose next steps are not well documented.
  * 10: Developer attempted to implement extensions using technologies not covered in class but it did not result in code or documentation.
