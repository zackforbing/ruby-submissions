# Scale Up Submission Form

## Basics

### Link(s) to the PRs or Issues You Picked Up
-[#50 Travis CI](https://github.com/LookingForMe/lookingfor/pull/50)

-[#37 Bug in StackOverflow Service](https://github.com/LookingForMe/lookingfor/issues/37)

### Talk about something from the pre-work that you didn't know about before this week.
I didn't know about pulling down the production database from Heroku. It of course makes sense that you
would be able to do that, I have just never been in a situation where there was an established
database that I didn't already have locally because I created it myself.

There were quite a few methods in the Rspec model testing template that I hadn't seen before - I definitely bookmarked that gist for future reference!

Same goes for the Factory Girl Tips and Tricks article - lots of really good advice in there that I will definitely reference the next time I have tricky associations to contend with.

### Summarize what you worked on

I spent the majority of the week getting Travis CI set up. It ended up taking a lot longer than I anticipated due to snags along the way, but that made it all the more satisfying when I finally got it working. The setup involved upgrading the Ruby version of the project and learning how to write a build file through much trial and error. Because that file is so customizable and custom tailored to the project, you can't just google one thing and be good to go. Implementing Travis CI also involved good communication with the team in order to know if it was actually working.

The last day I picked up the StackOverflow locations bug issue, pryed into the code, and figured out why the current regex isn't working. I didn't have time to start to fix it, but I left good notes on the issue for the next person to pick up the issue.

### Link to blog post(s) submitted

[Outline](https://gist.github.com/PenneyGadget/b57f98e707b919b78514839f6f6bae0b)
(I will write these this weekend!)

### Discuss: your experience doing PR reviews and getting PR feedback

Great! I really enjoy the process. I do wish I had commented on more issues, and I would have if this week had been a bit less weird and crazy for me. I think it's a really great skill to be able to jump into someone else's code and understand what's going on - this is something I want to get better at, and practice is what I need for that to happen.

And I love having a second or third set of eyes on my own code. I think in all the other Turing projects we aren't given the time and space to fully appreciate this process. The PR process just seems annoying and superfluous. But because we got to slow things down a bit this week and it was understood that you would wait for feedback before merging, I finally got to see and feel the value in this process. Really great lessons learned.

### Discuss: your experience doing daily stand ups

I like it a lot! I'm often wondering what people are up to, what progress they've made, what lessons they've learned, etc. - so allowing time for this (but not too much time!) is fantastic. I really appreciate that standup was a way to check in with everyone both about the job at hand and also regarding what's up in their personal life. It felt respectful and caring and professional. And the laptops closed rule is great and very important to it remaining respectful.

### What features would you like to see LookingFor have in the future?

I'd very much want to be able to click on a job and see all the details (which should happen soon!)

I would also like to be able to search by location or language/stack.

### Please feel free to ask any other questions or make any other statements below!

-----

Instructor Evaluation:

Points: (max 150)

### Rubric

#### Blog Post (40 Points)  
  * 40: Developer has >= 2 blog posts documenting something they have worked on for Looking For or has one in depth blog post.
  * 25: Developer has one blog post less than 500 characters long.
  * 0: Developer created no blog posts.

#### Participation (50 points)
  * 50: Developer participated daily in stand ups with the group (remote or in person). Developer was able to speak to their work in stand ups in a way that was clear and informative. Developer was involved in pull request reviews.

#### Risk Taking and Creativity (60 points)

Instructor/Developer will select one feature in the project to review for this section of the rubric.

  * 60: Developers pushed themselves and their team by taking risks which is demonstrated by a delivered feature. Developers explored concepts and technologies outside the scope of the curriculum.
