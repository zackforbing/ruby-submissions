# Scale Up Submission Form

## Basics

### Summarize the work you completed over the last two weeks

My goal over the past two weeks was to incorporate some charts into the LookingFor site. The charts would give some visual representation about the job market at the moment and over time. I decided to investigate using D3.js alongside the React front end. My work was mainly research focuses since I did not know React or the D3 libraries. In order to get charts to render on the page within the time allotted, I decided to use the rd3 library, which is a high-level version of D3.js and functions as React components.

### Link(s) to Your Work

 - Github Issues/Repo
  * [Original Issue](https://github.com/LookingForMe/lookingForFrontEnd/issues/74)
  * [Add rd3 to front end](https://github.com/LookingForMe/lookingForFrontEnd/pull/79)
  * [Add API endpoint for treemap](https://github.com/LookingForMe/lookingfor/pull/115)

### Hours logged this week?

(See Harvest logs - mixed between LookingFor app and Denver Startup Week)

### Talk about something that you didn't know about before this week.

Before this week, I didn't know the difference between state and props within React. I took some time to investigate this difference and know when to use either of them. The AJAX call to get data from the back-end uses state to pass that data to a component, and if I need to set an attribute of a component, that is most likely to be static, then I use props.

### Link to blog post(s)

[A Quick Foray Using React and D3 - Draft Link](https://medium.com/@jaeger.rob/7a2aae7df9e1)

### Discuss: your experience doing PR reviews and getting PR feedback

I merged a PR from Brian that fixed the bug for routing and opening links in new tabs. Before I merged it, I made sure there were comments from others and the comments were addressed. I also checked the staging app that Brian put together to test the bug in production. I could not reproduce the bug, so I went ahead and merged the PR.

I have submitted two PRs for review, but I am still waiting for feedback.

### Discuss: your experience doing daily stand ups

I found it difficult to know how much detail to put into my stand up talk. I tended to stay very high level unless I was having blockers or issues. Then I would go into a little more detail.

### Please feel free to ask any other questions or make any other statements below!

-----

# Instructor Evaluation:

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

  * 40: Developers pushed themselves and their team by taking risks which is demonstrated by a delivered feature or well documented spike. Developers explored concepts and technologies outside the scope of the curriculum.
  * 20: Developers pushed themselves and their team by taking risks which is demonstrated by an almost delivered feature whose next steps are not well documented.
  * 10: Developers attempted to implement extensions using technologies not covered in class but it did not result in code or documentation.
