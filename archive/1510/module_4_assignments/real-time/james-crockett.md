# RealTime Submission Form
[Project Spec](https://github.com/turingschool/curriculum/blob/master/source/projects/real_time.markdown)

# Basics

### Link to the Github Repository for the Project
[Repo](https://github.com/jecrockett/real-time)

### Link to the Deployed Application
[Application](https://poll-out.herokuapp.com/)

### Link to Your Commits in the Github Repository for the Project
[My Commits](https://github.com/jecrockett/real-time/commits/master)

### Provide a Screenshot of your Application
![Gif of App](http://g.recordit.co/LqaEN0H848.gif)

## Completion

### Were you able to complete functionality that fits both case studies?
Yessiree

### List any functionality from the case studies that is missing

### Did you do anything outside the scope of the case studies?
- I allow a user to add as many options as they want. I also explored efforts to authenticate as accurately as possible given the lack of an authentication tool. I cookie users and use the cookie as their voter ID rather than a socket ID so a user can't open various tabs and keep voting. I also don't add '/admin' on the end of the link for admin links, as a user could just type that in and see results, so I use random strings for both the poll ID and the admin ID.

# Code Quality

### Link to a specific block of your code on Github that you are proud of
[Code] (https://github.com/jecrockett/real-time/blob/5d64de0994b14d2ea2e199203719c05d05bffe08/public/client.js#L62-L69)
* I was proud of this because it was my first time using the promise() function to order animations and creating something that felt like a really elegant user interface.

### Link to a specific block of your code on Github that you feel not great about
[Code](https://github.com/jecrockett/real-time/blob/5d64de0994b14d2ea2e199203719c05d05bffe08/server.js#L94-L110)
* There's a couple things I don't like about this. One, I set the active flag to false when a poll is deactivated, but don't actually check that active/inactive flag. I feel I should be using it on line 98, but even if it's true I still need to check if the poll being voted on is still open or not, so it kind of feels pointless. I also don't like that I have slightly different Date syntax where the first time I just call toLocaleString() on a new date and the second time I'm saving it as a variable and calling toLocaleString() on that -- it should be cleaner.

### Attach a screenshot or paste the output from your terminal of the result of your test-suite running.
```
[real-time] (master)
$ npm test

> real-time@1.0.0 test /Users/JEC/where_the_magic_happens/Turing/4Module/projects/real-time
> mocha



  Server
    GET /
      ✓ should return a 200 (43ms)


  1 passing (58ms)
```

### Provide a link to an example, if you have one, of a test that covers an 'edge case' or 'unhappy path'

-----

### Please feel free to ask any other questions or make any other statements below!


-----

## Instructor Feedback

144/200

### Concept and Features

Does it have the expected features?

* 75 points - Met expectations as outlined by the user personas, the application is a solid first version. All planned features were delivered.

### Code Quality (JavaScript and/or Ruby)

* 25 points - Developer solves problems with a balance between conciseness and clarity and often extracts logical components. Developer can speak to choices made in the code and knows what every line of code is doing.

### Client-Side Application

* 25 points - Your application is thoughtfully put together with some duplication and no major bugs.

### Test-Driven Development

* 10 points - Many areas of the code are not covered by tests.

### Interface

* 5 points - The application is pleasant, logical, and easy to use

### Workflow

* 4 points - The developer makes a series of small, atomic commits that document the evolution of their application. There are no formatting issues in the code base.
