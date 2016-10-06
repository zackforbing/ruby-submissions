# Scale Up Submission Form

## Basics

### Link(s) to the PRs or Issues You Picked Up

-[#37 Bug in Location Gathering from StackOverflow Service](https://github.com/LookingForMe/lookingfor/issues/37)

-[#74 Change StackOverflow Job Search](https://github.com/LookingForMe/lookingfor/pull/74)

-[#76 API Jobs and Technologies Keys](https://github.com/LookingForMe/lookingfor/issues/76)

-[#79 Adjust Jobs and Technologies Output](https://github.com/LookingForMe/lookingfor/pull/79)

### Summarize what you worked on the last two weeks

I worked on the Boxtrot back-end team, where I first started working on normalizing locations from StackOverflow. The way we were getting the locations were using Feedjira and regex to scrape from the job title. This was giving us quite a bit of false locations. I was able to fix that method going forward by switching the service over from Feedjira to Nokogiri. With Nokogiri I was able to target the location tag directly and grab it. So that was one part of the problem,  the other part was that I needed to go back into the database and fix all the jobs with bogus locations. This was tricky because it involved using the Geocoder gem to verify that a location was legit. There was also a good of amount of regex involved. What was happening in the past was we were using regex to find the first parentheses in the job title and returning that value to set as the location. This was wrong because a lot of job titles had stacks in parentheses, or the company name in parentheses, or just plain gibberish in parentheses. I rewrote the regex to grab all of the parentheses in the job title and match each one against the geocoder gem. Then I had to add a few edges that would return false positives as a double check. I'm running the rake task on heroku right now so hopefully it does it's job correctly!

### Hours logged this week?

35:02 hours logged this week. There may have been a few more that I missed from this weekend but that's ok.

### Talk about something from the pre-work that you didn't know about before this week.

I don't know what this question is trying to ask me, but I guess I would say "JabaScripps"??? That was a joke, but also for serious. I didn't know GuavaScript that well and now I do! Thank you!

### Link to blog post(s) submitted

-[NokogiriVSFeedjira](https://medium.com/@NickyNoNaps/nokogiri-vs-feedjira-1725fb894b71#.w2d8j83qb)

-[GameTimeMaths](https://medium.com/@NickyNoNaps/recently-i-learned-javascript-and-while-i-was-two-weeks-into-the-learning-of-js-i-wrote-a-game-67bde19df9b5#.9qs0ntp2e)

### Discuss: your experience doing PR reviews and getting PR feedback

My experience doing PR reviews has been great. Code reviewing is something I take very seriously, and I often enjoy seeing how other people code. Sometimes I see some things and I'm like "oh yeah, that's hot fire! I'm gonna use that!", then other times I'm like "Meh." Both situations are beneficial for me, just reinforces the do's and don't's of programming. Then I leave comments accordingly. The PR feedback I've received has been great. I listen to what other people say and change my code to work perfectly with their code. This was especially true working with the front end team. I gave them exactly what they wanted/needed.

### Discuss: your experience doing daily stand ups

Daily stand ups was a great experience and I hope I get to work in a company that does that. It's nice to hear from everyone on the whole team and see what they're up to. Maybe it pertains to what you are working on and can possible enhance your feature, or you can enhance their feature. And I also liked having the ability to get feedback from everyone on the team.

### What features would you like to see LookingFor have in the future?

Putting the locations on to some kind of map would be cool. Possibly displaying whether or not Turing alum work there or not.

### Please feel free to ask any other questions or make any other statements below!



-----

Instructor Evaluation:

You were a great team player on this project! It was so good in standups to see how you were working between front and backend teams. You provided value to both teams, and that's impressive. Great job!

Final Score: 150/150

Points: (max 150)

### Blog Post (40 Points)  
  * 40: Developer has >= 2 blog posts documenting something they have worked on for their independent study or has one in depth blog post.


### Team Participation (40 points)

  * 40: Developer participated daily in stand ups with the group (remote or in person). Developer was able to speak to their work in stand ups in a way that was clear and informative. Developer was involved in pull request reviews.


### Hourly Work (30 points)

  * 30: Developer logged 7 to 8 hours per working day. Developer can speak to work completed during those hours.
 
### Risk Taking and Creativity (40 points)

  Instructor/Developer will select one feature in the project to review for this section of the rubric.

  * 40: Developer pushed themselves and their team by taking risks which is demonstrated by a delivered feature or well documented spike. Developers explored concepts and technologies outside the scope of the curriculum.
