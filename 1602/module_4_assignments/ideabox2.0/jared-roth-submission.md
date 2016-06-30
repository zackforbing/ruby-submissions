# Basics

### [Boxes of Ideas Repo](http://github.com/JaredRoth/idea-box)

### [Boxes of Ideas App](http://boxes-of-ideas.herokuapp.com/)

### [Commits](https://github.com/JaredRoth/idea-box/commits/master)

![Boxes of Ideas](images/jared-roth-screenshot.png)

## Completion

### All base functionality is complete

### No extensions

# Code Quality

### [DRY'd up the thumb up/down into one method](https://github.com/JaredRoth/idea-box/blob/770257083d67ccdb0d053dc132b4e61e5e752c03/app/assets/javascripts/idea_box.js#L56-L68)
* Was able to specify the direction of the vote and then have the method handle it appropriately.

### [Feels too large](https://github.com/JaredRoth/idea-box/blob/770257083d67ccdb0d053dc132b4e61e5e752c03/app/assets/javascripts/idea_box.js#L70-L90)
* Besides the fact that everything just lives in one file, there's a lot going on in this method and I wasn't sure how to break it up better.

![Boxes of Ideas](images/jared-roth-test-output.png)

### [Tests what happens when an idea quality cannot be raised past Genius or lowerd past Swill](https://github.com/JaredRoth/idea-box/blob/master/spec/features/user_can_alter_idea_quality_spec.rb)
