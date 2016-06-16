# Scale Up Submission Form

## Basics

### Summarize the work you completed over the last two weeks
I completed a few different tasks.
  - For one I got a stripped an old EchoNest API and used Spotify instead.   
  - I tried to play around with a schema which I'll post that terrible branch below.
  - I fixed many tests and got selenium up and running. Managed to get the test to do what I wanted it to but still somehow fails
  - Refactored a little bit.
  - Fixed invite issue that would break the entire database.
  - Tried, to fix group playlists songs. Still needs some work but given another day or two would have been finished

### Link(s) to Your Work

 - Github Issues/Repo
 - [Invite fixing](https://github.com/Jlawlzz/personal-project/pull/78#issuecomment-223649689 )
 - [8 Hour hole](https://github.com/Jlawlzz/personal-project/pull/77)
 - [Testing Destroy](https://github.com/Jlawlzz/personal-project/pull/82/files)

### Hours logged this week?

Clocked all my hours. I don't know if I deserve all the points. I was stressed and didn't get as much done as I would have liked.

### Talk about something that you didn't know about before this week.
  Selenium and VCR don't play nicely but you can add this is rails_helper to allow Selenium to make api calls.
  -   c.ignore_localhost = true  
      c.allow_http_connections_when_no_cassette = true

  That I should have been TDDing during the entire process of messing with the DB. I did a little TDD but wasn't really until I fixed the last test that I realized that yeah.. I needed that in the database. Boo.

  I learned that dependent :destroy is pretty powerful. I enjoyed refactoring this because I was able to strip out a lot of code. In doing this I found out that a lot of other things weren't working correctly. (Our tests were poor).

### Link to blog post
[API Fun](https://medium.com/@tmoore2272/apis-that-no-longer-take-requests-56a6c3ddc3b9#.k6zsn8o33)

### Discuss: your experience doing PR reviews and getting PR feedback
This was more enjoyable then I thought it would be! I didn't review to many PR reviews, but I did attempt to find a better way for Adrienne to store information in her database. I thought it might be a good idea to use :store and create a hash, but reading more into store I realized you couldn't complex queries and would have to rely on Ruby(SLOW)

In the Invite Fixing PR that I mentioned above, Adrienne asked about why I was using Group_playlists. This was exactly the same thing I thought before I went down that 8 hour hole to fix this! This also pushed me to want to help her out because although I had already found out it confirmed that the way we used it was a little weird(but necessary).

### Discuss: your experience doing daily stand ups
  I quite enjoyed the stand ups I was able to attend. Unfortunately I missed several in person stand ups.


-----

# Instructor Evaluation:

You did a great job on this project. Despite what was going on outside of Turing, you powered through and you did a **great job**. We are **so** impressed with how you handled the last couple of weeks and what you accomplished. It's hard to get back into an older (potentially messy) project and refactor it. You worked through frustration and feeling discouraged, hit major speed bumps, and overcame them to end up with something that will be fantastic to talk about in interviews. Really good job. Infinity high fives.

Final Score: 150/150

Points: (max 150)

### Blog Post (40 Points)  

  * 40: Developer has >= 2 blog posts documenting something they have worked on for their independent study or has one in depth blog post.

### Team Participation (40 points)

  * 40: Developer participated daily in stand ups with the group (remote or in person). Developer was able to speak to their work in stand ups in a way that was clear and informative. Developer was involved in pull request reviews. **(provided a write up of what you'd been up to and next steps for missed in-person standups)**

### Hourly Work (30 points)

  * 30: Developer logged 7 to 8 hours per working day. Developer can speak to work completed during those hours.

### Risk Taking and Creativity (40 points)

  Instructor/Developer will select one feature in the project to review for this section of the rubric.

  * 40: Developers pushed themselves and their team by taking risks which is demonstrated by a delivered feature or well documented spike. Developers explored concepts and technologies outside the scope of the curriculum.
