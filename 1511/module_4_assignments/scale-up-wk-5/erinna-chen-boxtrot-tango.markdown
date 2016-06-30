# Scale Up Submission Form

## Basics

### Summarize the work you completed over the last two weeks
In week 1 of Scale Up, I was involved with the Boxtrot team working on the backend of Looking For. Over the first week and the beginning of the second week I accomplished the following:
- Explored different ways of parsing data from the job sites that LookingFor was subscribed to
- Normalized the database on job locations
- Added server side CORS responses with the rack-cors gem
- Implemented an API endpoint `api/v1/jobs/:id`

In week 2 of Scale Up, I moved to an independent project. I wanted to work in the Phoenix Framework to implement an application that could connect via HTTP to the [Clarke Coin DNS](http://dns1.clarkecoin.org/index.html) and [full nodes](http://159.203.206.49:3000), as well as to TCP clients (e.g. the [all_the_coins miner](https://github.com/erinnachen/all_the_coins)) through WebSockets. Over the course of the week, I accomplished the following:
- Researched how to work with the [Phoenix Framework](http://www.phoenixframework.org/)
- Deployed a simple Phoenix application to Heroku
- Got stuck trying to handshake with Clarke Coin nodes with an application deployed on Heroku
- Re-deployed the application on a Digital Ocean Droplet
- Explored how to deploy the application with nginx

### Link(s) to Your Work
Boxtrot (Week 1):
- [Parsing Gist](https://gist.github.com/erinnachen/e35003fc4cfb70819f41f89222f9c472)
- [Add rack-cors gem](https://github.com/LookingForMe/lookingfor/pull/75)
- [Jobs show endpoint](https://github.com/LookingForMe/lookingfor/pull/81)
- [Location normalization](https://github.com/LookingForMe/lookingfor/pull/72)

Whiskey Tango (Week 2):
- [Glorious Repo](https://github.com/erinnachen/clarke_coin_socket)
- [Currently deployed branch on said glorious repo](https://github.com/erinnachen/clarke_coin_socket/tree/calling_out_to_DNS-%231)
- [Semi-Production](http://107.170.205.129:4000/)
- [A handshake endpoint](http://107.170.205.129:4000/block_height)

### Hours logged this week?

- Tue: 7:15
- Wed: 7:30
- Thur: 4:45
- Sun: 5:45

### Talk about something that you didn't know about before this week.
Dear Heroku,

I love you to death. You make deploying most applications really really easy, so much so that I have no idea how to actually deploy applications without you. This week I spent way too much time trying to access my sweet sweet application by IP address and port. I knew that those dynos didn't have static addresses, but I thought I could be smart and get around that by passing Clarke Coin the dynamic IP and port. I was so wrong.

I moved to Digital Ocean and had to install many many packages. It felt weird to type `sudo` a ton of times. I bombed when I tried to figure out nginx. Also, logging is super annoying too.

This week, I learned how valuable you are to me. Please keep being you.

Much love,
Erinna

### Blog
[Cross-Origin Resource Sharing (CORS) and APIs](http://erinnachen.github.io/blog/2016/06/12/Cors-and-you#disqus_thread)

### Discuss: your experience doing PR reviews and getting PR feedback
I think one of the interesting things with working on LookingFor was the approach that others had w/r/t PR's. I'm definitely more inclined to look at code and comment inline. If something is confusing to me I'll pull down the branch and play around with it. It's never clear to me whether my collaborators appreciate the comments or are annoyed by them.

On the flip side, it's a bit frustrating to work on being quite verbose on PR's and make comments and feel like they're ignored. Also, I care about getting feedback, but it doesn't seem like others feel open to giving feedback to me.

### Discuss: your experience doing daily stand ups
I enjoyed daily stand ups in Week 2 more than in Week 1. It might have been the nature of the projects, but Whiskey Tango stand ups were definitely more to the point. I need to work on patience when people are expressing indecisiveness. It didn't seem like people had blockers very often; I would have liked to see how groups work through that in stand up.

### Please feel free to ask any other questions or make any other statements below!
These two weeks were definitely a lot slower than any other weeks at Turing. Week 1 felt like there really wasn't a huge push to get features done. Week 2 felt like I spent a ton of time just troubleshooting and wandering through the weeds. I'm going to try to work on the Phoenix project for awhile afterwards. After the struggle with deployment, I think I'm set up for moving forward with functionality.


-----

# Instructor Evaluation:

I'm glad you pivoted to the independant project for week 2, it seemed like a better fit interest-wise as well as where you were mentally. It's tough getting put on a big group project, and we're so glad you were able to move to a project/topic that would let feel good about your final weeks at Turing!

Final score: 150/150

Points: (max 150)

### Blog Post (40 Points)  

  * 40: Developer has >= 2 blog posts documenting something they have worked on for their independent study or has one in depth blog post.

### Team Participation (40 points)

  * 40: Developer participated daily in stand ups with the group (remote or in person). Developer was able to speak to their work in stand ups in a way that was clear and informative. Developer was involved in pull request reviews.

### Hourly Work (30 points)

  * 30: Developer logged 7 to 8 hours per working day. Developer can speak to work completed during those hours.

### Risk Taking and Creativity (40 points)

  Instructor/Developer will select one feature in the project to review for this section of the rubric.

  * 40: Developers pushed themselves and their team by taking risks which is demonstrated by a delivered feature or well documented spike. Developers explored concepts and technologies outside the scope of the curriculum.
