# Scale Up Submission Form

## Basics

### Link(s) to the PRs or Issues You Picked Up
-[#7 Create app component with Header and JobListings](https://github.com/LookingForMe/lookingForFrontEnd/pull/7)

-[#9 Render Jobs](https://github.com/LookingForMe/lookingForFrontEnd/pull/9)

-[#16 Render Jobs from API](https://github.com/LookingForMe/lookingForFrontEnd/pull/16)

-[#24 Change app title to LookingFor](https://github.com/LookingForMe/lookingForFrontEnd/pull/24)

-[#27 Use browserHistory for Routes](https://github.com/LookingForMe/lookingForFrontEnd/pull/27)

-[#29 Remove trimmed job description from job show page](https://github.com/LookingForMe/lookingForFrontEnd/pull/29)

-[#35 Style Updating](https://github.com/LookingForMe/lookingForFrontEnd/pull/35)

-[#38 Link "Looking For" text in header to the home page](https://github.com/LookingForMe/lookingForFrontEnd/pull/38)

-[#39 Add pagination to job index page](https://github.com/LookingForMe/lookingForFrontEnd/pull/39)

-[#89 Add recent jobs api endpoint](https://github.com/LookingForMe/lookingfor/pull/89)

-[#93 Change recent_jobs scope to last month and paginate to 25 per page](https://github.com/LookingForMe/lookingfor/pull/93)

### Summarize what you worked on the last two weeks

I worked on setting up the React app with Webpack and then creating components and an ajax call to pull the data from the actual production API endpoint and render the jobs in the view. I helped fix some issues with the routes so that they display properly and without a hash and other random characters that were being added due to the hash history. I debugged and fixed an error that was occurring when displaying partial job descriptions. I worked on styling to display the job index and show page differently and more suitably for each page. I helped with the setting up the recent jobs API endpoint to scope to only displaying jobs from the last month and writing tests. I researched options for enabling the user to view more than just the first 25 jobs. I decided to go with using pagination and implemented the react bootstrap component.

### Hours logged this week? 35

### Talk about something from the pre-work that you didn't know about before this week.

Something I learned this week about React is that state doesn't always get changed immediately when you call setState. From the React docs: "setState() does not immediately mutate this.state but creates a pending state transition. Accessing this.state after calling this method can potentially return the existing value." When working on implementation of pagination, I was using setState to keep track of the current page and change the page number when a button was pressed. However, since the state ended up being set a step behind what I expected, the page change was always a click behind.

### Link to blog post(s) submitted

http://kimikokano.com/2016/06/12/connecting-a-react-app-to-an-existing-production-database/

### Discuss: your experience doing PR reviews and getting PR feedback

It went well. Our team did a good job of responding to PR requests quickly and thoroughly. Having my PR's checked by the whole group gave me confidence before they were merged. My inbox was full from all the messaging! I tried to be thorough in my reviews and everyone in the group was great about accepting and giving feedback.

### Discuss: your experience doing daily stand ups

It was good to have meetings daily to know where things stood with the project and where people were at with their tasks and whether there were and stumbling blocks. Doing it standing up is nice because by the end everyone wants to be done standing so the meeting is unable to persist too long. It's nice to get the gist of where everyone is at and then be done so we could all get back to work.

### What features would you like to see LookingFor have in the future?

I'd like to see LookingFor have email alerts so that you get an email if a job that fits your requirements comes up. It would be nice for it also save your searches and/or be able to send you an email to keep track of any jobs that you want to apply for.

### Please feel free to ask any other questions or make any other statements below!

-----

Instructor Evaluation:

You are a very strong team player. We saw your input and feedback all over the place on PR reviews -- it was great! When we were checking in with your teammates, we heard "Kimi said X" or "Kimi left me a comment on Y" a lot. That's very cool. It's obvious you threw yourself into this project. Good job!

Final Points: 150/150

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
