# Ideabox 2.0 Submission Form
[Project Spec](https://github.com/turingschool/curriculum/blob/master/source/projects/revenge_of_idea_box.markdown)

* Fork this repo, if you haven't already and check out a branch
* Use this README as a template to create a file in this folder with your name as the title.
* Submit a pull request
* Pro Tip: You can use [recordit.co](http://recordit.co/) to record interaction gifs.
* Secondary Pro Tip: [Here's how to link to specific line number(s) in Github](http://stackoverflow.com/questions/23821235/how-to-link-to-specific-line-number-on-github)
* Tertiary Pro Tip: You can re-use some of these things in your portfolio/resume

------

# Basics

### Link to the Github Repository for the Project
[https://github.com/scottfirestone/idea-box](https://github.com/scottfirestone/idea-box)

### Link to the Deployed Application
[https://shrouded-basin-90816.herokuapp.com/](https://shrouded-basin-90816.herokuapp.com/)

### Link to Your Commits in the Github Repository for the Project
[https://github.com/scottfirestone/idea-box/commits/master](https://github.com/scottfirestone/idea-box/commits/master)

### Provide a Screenshot of your Application
![](https://github.com/scottfirestone/idea-box/blob/master/Screen%20Shot%202016-05-12%20at%2012.47.28%20PM.png)

## Completion

### Were you able to complete the base functionality?
* Yes

### Which extensions, if any, did you complete?
* No

### Attach a .gif, or images of any extensions work being used on the site.
* No

# Code Quality

### Link to a specific block of your code on Github that you are proud of
[Cool Code](https://github.com/scottfirestone/idea-box/blob/master/app/models/idea.rb#L1-L16)
* I figured out (read: looked up) how to cycle through enum integer values. I preferred this approach to dealing with the strings.

### Link to a specific block of your code on Github that you feel not great about
[Uncool Code](https://github.com/scottfirestone/idea-box/blob/master/app/assets/javascripts/ideas.js#L137-L154)
* I feel like this could benefit from a lot of refactoring.

### Attach a screenshot or paste the output from your terminal of the result of your test-suite running.
```
$ rspec
......F......

Failures:

  1) User edits an idea they see the new idea info
     Got 0 failures and 2 other errors:

     1.1) Failure/Error: title.sendKeys("Updated-Title")

          NoMethodError:
            undefined method `sendKeys' for #<Capybara::Node::Element:0x007fbfa2541b40>
          # ./spec/features/user_edits_idea_spec.rb:10:in `block (2 levels) in <top (required)>'

     1.2) Failure/Error: idea = Idea.find(params[:id])

          ActiveRecord::RecordNotFound:
            Couldn't find Idea with 'id'=1
          # ./app/controllers/api/v1/ideas_controller.rb:20:in `update'
          # /Users/scottfirestone/.rvm/gems/ruby-2.2.1/gems/rack-1.6.4/lib/rack/etag.rb:24:in `call'
          # /Users/scottfirestone/.rvm/gems/ruby-2.2.1/gems/rack-1.6.4/lib/rack/conditionalget.rb:38:in `call'
          # /Users/scottfirestone/.rvm/gems/ruby-2.2.1/gems/rack-1.6.4/lib/rack/head.rb:13:in `call'
          # /Users/scottfirestone/.rvm/gems/ruby-2.2.1/gems/rack-1.6.4/lib/rack/session/abstract/id.rb:225:in `context'
          # /Users/scottfirestone/.rvm/gems/ruby-2.2.1/gems/rack-1.6.4/lib/rack/session/abstract/id.rb:220:in `call'
          # /Users/scottfirestone/.rvm/gems/ruby-2.2.1/gems/railties-4.2.5.1/lib/rails/rack/logger.rb:38:in `call_app'
          # /Users/scottfirestone/.rvm/gems/ruby-2.2.1/gems/railties-4.2.5.1/lib/rails/rack/logger.rb:20:in `block in call'
          # /Users/scottfirestone/.rvm/gems/ruby-2.2.1/gems/railties-4.2.5.1/lib/rails/rack/logger.rb:20:in `call'
          # /Users/scottfirestone/.rvm/gems/ruby-2.2.1/gems/rack-1.6.4/lib/rack/methodoverride.rb:22:in `call'
          # /Users/scottfirestone/.rvm/gems/ruby-2.2.1/gems/rack-1.6.4/lib/rack/runtime.rb:18:in `call'
          # /Users/scottfirestone/.rvm/gems/ruby-2.2.1/gems/rack-1.6.4/lib/rack/lock.rb:17:in `call'
          # /Users/scottfirestone/.rvm/gems/ruby-2.2.1/gems/rack-1.6.4/lib/rack/sendfile.rb:113:in `call'
          # /Users/scottfirestone/.rvm/gems/ruby-2.2.1/gems/railties-4.2.5.1/lib/rails/engine.rb:518:in `call'
          # /Users/scottfirestone/.rvm/gems/ruby-2.2.1/gems/railties-4.2.5.1/lib/rails/application.rb:165:in `call'
          # /Users/scottfirestone/.rvm/gems/ruby-2.2.1/gems/rack-1.6.4/lib/rack/urlmap.rb:66:in `block in call'
          # /Users/scottfirestone/.rvm/gems/ruby-2.2.1/gems/rack-1.6.4/lib/rack/urlmap.rb:50:in `each'
          # /Users/scottfirestone/.rvm/gems/ruby-2.2.1/gems/rack-1.6.4/lib/rack/urlmap.rb:50:in `call'
          # /Users/scottfirestone/.rvm/gems/ruby-2.2.1/gems/capybara-2.7.1/lib/capybara/server.rb:43:in `call'
          # /Users/scottfirestone/.rvm/gems/ruby-2.2.1/gems/rack-1.6.4/lib/rack/handler/webrick.rb:88:in `service'

Finished in 5.87 seconds (files took 2.14 seconds to load)
13 examples, 1 failure

Failed examples:

rspec ./spec/features/user_edits_idea_spec.rb:4 # User edits an idea they see the new idea info

Coverage report generated for RSpec to /Users/scottfirestone/Turing/4module/idea-box/coverage. 41 / 41 LOC (100.0%) covered.
```
* I couldn't figure out how to get capybara to fill-in content-editable elements. :(

### Provide a link to an example, if you have one, of a test that covers an 'edge case' or 'unhappy path'
* Whoops.
-----

### Please feel free to ask any other questions or make any other statements below!

142/150

# Instructor Feedback

### Data Model

(5 points total.)

### User Flows

#### Viewing ideas

(8 points total.)

(truncation truncates on edit)

#### Adding a new idea

(15 points total.)

#### Deleting an existing idea

(15 points total.)

#### Changing the quality of an idea

(15 points total.)

#### Editing an existing idea

(20 points total.)

#### Idea Filtering and Searching

(15 points total.)

## Instructor Evaluation Points

### Specification Adherence

* **10 points**: The application consists of one page with all of the major functionality being provided by jQuery. There is no use of `format.js` in Rails. There is no use of unobstrusive JavaScript. There are no front-end frameworks used in the application. No approach was taken that is counter to the spirit of the project and its learning goals. There are no features missing from above that make the application feel incomplete or hard to use.

### User Interface

* **5 points** - The application is pleasant, logical, and easy to use. There no holes in functionality and the application stands on it own to be used by the instructor _without_ guidance from the developer.

### Testing

* **8 points** - Project has a running test suite that tests and multiple levels but fails to cover some features. All controller actions are covered by tests. The application makes some use of integration testing.

### Ruby and Rails Quality

* **8 points** - Developer solves problems with a balance between conciseness and clarity and often extracts logical components. Developer can speak to choices made in the code and knows what every line of code is doing.

### JavaScript Style

* **8 points** - Application is thoughtfully put together with some duplication and no major bugs. Developer can speak to choices made in the code and knows what every line of code is doing.

### Workflow

* **10 points** - The developer effectively uses Git branches and many small, atomic commits that document the evolution of their application.
