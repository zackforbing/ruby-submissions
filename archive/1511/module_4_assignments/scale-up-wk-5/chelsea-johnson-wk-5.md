# Scale Up Submission Form

## Basics

### Link(s) to the PRs or Issues You Picked Up
- [#31 Search By Tech Stack](https://github.com/LookingForMe/lookingForFrontEnd/pull/50)
- [#45 Format Landing page](https://github.com/LookingForMe/lookingForFrontEnd/pull/48)
- [#44 Add New Endpoints](https://github.com/LookingForMe/lookingForFrontEnd/pull/44)
- [#37 Search By Location](https://github.com/LookingForMe/lookingForFrontEnd/pull/41)
- [#95 Search By Location Endpoint](https://github.com/LookingForMe/lookingfor/pull/95)

### Summarize what you worked on the last two weeks
 * I worked on creating a React front end for the Lookingfor application. I had a hand in loading jobs, showing individual jobs, searching jobs by location (also helped with endpoint), and searching jobs by tech stack.

### Hours logged this week?
 * 32

### Talk about something from the pre-work that you didn't know about before this week.
 * I finally have class functions for my React components- for some reason last week I kept getting syntax errors when trying to implement. They are pretty simple, however:

 `handleChange(event) {this.setState({inputValue: event.target.value});}`
 
You call the function by using `this.handleChange` like you would for a regular JavaScript class function.

### Link to blog post(s) submitted
- [React: State, Props, and Keys](https://medium.com/@cheljoh/react-state-props-and-keys-4363901d9948#.9bicmmffm)
- [React-Rails Gem or React/Node?](https://medium.com/@cheljoh/react-rails-gem-or-react-node-c75c41eaaca3#.52di5oy9d)

### Discuss: your experience doing PR reviews and getting PR feedback
- Receiving my partner feedback was a positive experience- they often noticed naming inconsistencies or ways I could refactor my code. I also liked doing PR reviews- it allowed me to make sure all new code was up to standards before getting merged.

### Discuss: your experience doing daily stand ups
- I liked them, they allowed us to keep in touch with the back end team. There were times we may have needed to reserve discussions for after stand up if they were only between 2-3 people (and not the entire group).

### What features would you like to see LookingFor have in the future?
- Elastic search instead of current location/tech search. 
- When you view details for a job resulting from a search and go back to the root page, your previous search results disappear. May need to implement some kind of caching. 
- More testing would be nice, do not have tests for all components right now. 
- Refactoring of components (break out SearchBarAndListings component into two separate components).

### Please feel free to ask any other questions or make any other statements below!
- Don't have any, was a good experience!

-----

Instructor Evaluation:

150/150

Good work on this team for both weeks. You did a really great job on being involved in communication on pull requests as well as stepping into a leadership role during standups.

Good feedback on standups as well - more aggressive parkinglotting! 

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
