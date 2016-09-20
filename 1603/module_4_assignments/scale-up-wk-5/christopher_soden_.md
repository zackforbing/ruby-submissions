# Scale Up Submission Form

## Basics

### Summarize the work you completed over the last two weeks

We implemented the OmniAuth Gem on the rails server and created a controller and route to allow the ember front-end to trigger the OmniAuth process. We modified the handlebars sign-up view to handle the change and created a 'Welcome' page to display when the user is logged in. We also modified the navbar to change depending on logged in/out status and created a "Sign Out" link. We created a handlebars helper method to retrieve data from cookies.

### Link(s) to Your Work

 - [Github Back End](https://github.com/turingMentorSHIP/MentorSHIP-API)
 - [Github Front End](https://github.com/turingMentorSHIP/MentorSHIP-FrontEnd)

### Hours logged this week?

- Monday (0 hours):
- Tuesday (8:00 hours):
- Wednesday (8:10 hours):
- Thursday (8:00 hours):
- Friday (0 hours):

### Talk about something that you didn't know about before this week.
Before this week I had never heard of Handlebars helpers, and knew nothing about creating them. Handlebars in general seems very inflexible. ERB views are much easier to work with.

### Link to blog post(s)
[Blog](https://medium.com/@karavol27/basics-of-regexs-5e0a09c47b38#.j77bjmu0k)

### Discuss: your experience doing PR reviews and getting PR feedback
I like being able to help people with their PRs, but coming into an unfamiliar code base it's hard to feel like I can really contribute.

### Discuss: your experience doing daily stand ups
Doing the daily stand ups was very helpful. Being able to talk about problems with other people and explain your problems causes you to see them in a different context. And the group support is great.

### Please feel free to ask any other questions or make any other statements below!

-----

# Instructor Evaluation:

Points: 110/150

# Hours

57 total hours logged (between 7 to 8 hours a day)

# Code

For the links to the work, can you please make sure to link to the code/branches/prs specifically that you worked on - not just the entire repo? Makes it much easier for reviewers to know what you did there. 

The amount of code created is really impressive for this project, but I have concerns about some issues in the work flow and where the state of the app currently is : notes below. From a learning new technology standpoint, I’m impressed that you and Parker dove in and figured out how to make this code work — but as someone who has to maintain this application, I wish more time was taken on documenting and PR review and refactoring based on the PR feedback.

While you did post a PR for review here: https://github.com/turingMentorSHIP/MentorSHIP-API/pull/9 - there are multiple places where feedback and suggestions were given that were not addressed or cleaned up. At minimum, you need to respond to the feedback that you are given and let the reviewer know what steps you are taking and honor the fact that they took time to review your code. 

My expectation for handling PR comments is to create an issue that directly links to this code in the issue if you are going to merge the PR without fixing things that were pointed out - and that small syntax changes should be fixed before the PR is merged, or fixed ASAP and linked in a response if the PR was already merged.

To start, the following issues need more follow up - but I believe both sets of issues in either repo need clarity across the board: 

- https://github.com/turingMentorSHIP/MentorSHIP-API/issues/19
- https://github.com/turingMentorSHIP/MentorSHIP-FrontEnd/issues/9
- https://github.com/turingMentorSHIP/MentorSHIP-FrontEnd/issues/8
- https://github.com/turingMentorSHIP/MentorSHIP-FrontEnd/issues/7

In general, the issues that were created do that have enough detail. Since the work that was merged did not include any documentation updates, there would be no way for someone to pick up most of these issues without spending a ton of time digging throught he code and commit history.

I don't know from reading through the issues what the state of the application is. Does the product that is deployed and on master actually work right now?

Also - all work that went into the project needed to be done in a pull request: https://github.com/turingMentorSHIP/MentorSHIP-FrontEnd/commit/4b85c98642918824401d0cf95825c97850238e18 - multiple commits at the end look like they were pushed directly to master.

### Blog Post (40 Points)  

  * 40: Developer has >= 2 blog posts documenting something they have worked on for their independent study or has one in depth blog post.

### Team Participation (40 points)

  * 20: Developer was absent for 1 stand up, did not participate actively in code reviews.

### Hourly Work (30 points)

  * 30: Developer logged 7 to 8 hours per working day. Developer can speak to work completed during those hours.

### Risk Taking and Creativity (40 points)

  Instructor/Developer will select one feature in the project to review for this section of the rubric.

  * 20: Developers pushed themselves and their team by taking risks which is demonstrated by an almost delivered feature whose next steps are not well documented.
