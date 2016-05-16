# Scale Up Submission Form

## Basics

### Link(s) to the PRs or Issues You Picked Up

LookingFor:

- [#51 Rake Task](https://github.com/LookingForMe/lookingfor/pull/51)

Whiskey Tango:

- [#2 Brant Wellman's Project](https://github.com/brantwellman/3D-graphics-engine/pull/2)
- [#3 Aaron Greenspan's Project](https://github.com/afg419/everybody_counts/pull/3)
- [#2 Hector Huertas' Project](https://github.com/hectorhuertas/colabora_api/pull/3)

### Talk about something from the pre-work that you didn't know about before this week.

- [Stubbing external services](https://robots.thoughtbot.com/how-to-stub-external-services-in-tests), I did not know about this, I thought the only way to test external API calls was to use VCR. I'm glad I learned about this, because it was a major part of the feature I implemented for LookingForMe.
- I also didn't know that you could pull or export data to the production database, that is super cool! And extremely useful if you want to use some real data for testing, or if you need to clean up data in your production database.

### Summarize what you worked on

[#46 Authentic Jobs API](https://github.com/LookingForMe/lookingfor/pull/46)

I worked on adding the Authentic Jobs API to the LookingForMe application. I built a service for the API, and built a sinatra application for testing the API. I added a rake task to iterate through the existing technologies and pull the jobs relevant to each technology. I also added links to the job sources on the index homepage.

I merged in Slota and Penney's changes into my PR and after I merged my PR, I pushed the updated master to Heroku. I helped Slota with rebasing and squashing commits. I helped Brant with his blog post that described his technically challenging 3D engine.

### Link to blog post(s) submitted

- [VCR versus Webmock](http://bethsecor.github.io/2016/04/12/vcr-versus-webmock.html)
- [SSL Server Tests](http://bethsecor.github.io/2016/04/13/ssl-tests.html)

### Discuss: your experience doing PR reviews and getting PR feedback

Doing PR reviews was a good experience, because sometimes I had good suggestions, but on code in Phoenix, I struggled to come up with useful comments. Some of the PR feedback was very helpful and I made good changes to my code. Some of the other feedback felt like people were just trying to come up with something to say, because it was part of the project.

### Discuss: your experience doing daily stand ups

Nice to hear what everyone was working on, so that others could reach out if they needed help. Wish it was just boxtrot folks, so it would be more focused, and I also wish we could have more discussion around the app after everyone had given their standup.

### What features would you like to see LookingFor have in the future?

- Be able to search for jobs by technology or company or location
- Searching for Go jobs is difficult in Authentic Jobs and StackOverflow since they are essentially searching the title and description for the word 'go'
- Distinction between junior and senior developer jobs.

### Please feel free to ask any other questions or make any other statements below!

- It was unclear when it was okay to merge pull requests.
- Seemed like there was not a lot of accountability in terms of how much got done on the project.
- I think the stand-ups might have been more useful if it was just boxtrot, and everyone had a little bit longer to talk.
- It was a cool experience!

-----

Instructor Evaluation:

Points: (max 150)

### Rubric

#### Blog Post (40 Points)  
  * 40: Developer has >= 2 blog posts documenting something they have worked on for Looking For or has one in depth blog post.

#### Participation (50 points)
  * 50: Developer participated daily in stand ups with the group (remote or in person). Developer was able to speak to their work in stand ups in a way that was clear and informative. Developer was involved in pull request reviews.

#### Risk Taking and Creativity (60 points)

Instructor/Developer will select one feature in the project to review for this section of the rubric.

  * 60: Developers pushed themselves and their team by taking risks which is demonstrated by a delivered feature. Developers explored concepts and technologies outside the scope of the curriculum.
