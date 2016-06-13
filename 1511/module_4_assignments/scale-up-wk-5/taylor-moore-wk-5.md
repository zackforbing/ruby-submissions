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
