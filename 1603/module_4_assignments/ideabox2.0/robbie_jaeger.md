## Robbie Jaeger - Idea Box 2.0

### Important Links:

[Github Repo](https://github.com/robbiejaeger/idea_box.git)

[Production Link](https://ideabox-rj.herokuapp.com/)

[Github Commits](https://github.com/robbiejaeger/idea_box/commits/master)

### Screenshot:
[Idea Box Home Page](http://www.openscreenshot.com/img/57b6080bdb43b5-19195265)

### Completion:
##### Were you able to complete the base functionality?
Yes, I was able to complete the base functionality required in each section (I did not finish truncation).

##### Which extensions, if any, did you complete?
I did not complete any extensions.

### Code Quality:
##### Link to a specific block of code on Github that you are proud of
 [Upvote and Downvote](https://github.com/robbiejaeger/idea_box/blob/master/app/assets/javascripts/vote_idea.js)

##### Why were you proud of this piece of code?
I tried to pay attention to future changes when writing this code. Originally, I had a quality enum in my Idea ActiveRecord model, and I changed it to use integers only. This way, I could change the quality strings in my JS - the number of qualities and strings could be changed without changing the logic.

##### Link to a specific block of your code on Github that you feel not great about
[Editing Title and Body](https://github.com/robbiejaeger/idea_box/blob/master/app/assets/javascripts/update_idea.js)

##### Why do you feel not awesome about the code? What challenges did you face trying to write/refactor it?
In the current state of this code, if you click on a title and do not make any changes, the ajax call will still be sent unnecessarily. I wanted to get the original state of the text to be able to compare it to the edited version, but I wasn't able to get it for ideas that were added after the document was loaded.

##### Attach a screenshot or past the output from your terminal of the result of your test-suite running.
```
Teaspoon running default suite at http://127.0.0.1:55051/teaspoon/default
*

Pending:
  can render an idea should be a div with title and body
    # Not yet implemented

Finished in 0.00500 seconds
1 example, 0 failures, 1 pending


robbie: idea_box (master) $ rspec
*....

Pending: (Failures listed here are expected and do not affect your suite's status)

  1) Home should not have JavaScript errors
     # Temporarily skipped with xit
     # ./spec/features/user_can_delete_idea_spec.rb:4


Finished in 0.45938 seconds (files took 1.8 seconds to load)
5 examples, 0 failures, 1 pending
```

##### Provide a link to an example, if you have one, of a test that covers an 'edge case' or 'unhappy path'
I couldn't get my feature testing to work with webkit...so no sad path - I'm not proud of it.
