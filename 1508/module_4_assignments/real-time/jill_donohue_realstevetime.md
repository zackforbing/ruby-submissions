# Basics

### Link to the Github Repository for the Project
[Your Repo](https://github.com/jillmd501/stevetime)

### Link to the Deployed Application
[Your Application](https://realstevetime.herokuapp.com/)

### Link to Your Commits in the Github Repository for the Project
[Your Commits](https://github.com/jillmd501/stevetime/commits/master)

### Provide a Screenshot of your Application
![spacejam](http://i.imgur.com/oypEwbp.png)

## Completion

### Were you able to complete what you feel is the base functionality?
#### If not, list what functionality you think may be missing missing.

Everything works except that I was not able to close the poll.

### What features did you complete which you feel 'exceeded expectations'?


# Code Quality

### Link to a specific block of your code on Github that you are proud of
[test](https://github.com/jillmd501/new-steve-time/blob/master/test/count-test.js#L4-L15)
#### Why were you proud of this piece of code?
Since API-Curious, I have realllllly struggled with using Test Driven Development. I have had the mind set of just getting it to work, and then worrying about getting enough tests that looked like I deserved at least a three. I used this test to build out so much functionality and while it is only one, it covers a lot of ground.  Honestly, I am mostly happy that I learned how all the pieces of this crazy express app work together. 💪

### Link to a specific block of your code on Github that you feel not great about
[client.js](https://github.com/jillmd501/new-steve-time/blob/master/public/client.js#L11-L19)


#### Why do you feel not awesome about the code? What challenges did you face trying to write/refactor it?
It just looks super hacky to me and I know there are ways I could have made this whole process more seamless.  I need to be much more explicit in naming conventions because that in itself caused me so many problems that slowed me down.  EXPLICIT IS KEY.
### Attach a screenshot or paste the output from your terminal of the result of your test-suite running.
![test](http://i.imgur.com/1tQume6.png)

### Provide a link to an example, if you have one, of a test that covers an 'edge case' or 'unhappy path'

it('will not tally multiple votes', function(){
  var expectedResult = {'jill': 2, 'joe': 1}
  expect(countVotes(poll)).to.deep.equal(expectedResult)
});

-----

### Please feel free to ask any other questions or make any other statements below!
