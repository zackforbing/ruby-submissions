## Self Directed Project

### Eval Template

#### Completion

* 4 - Developer completed all the user stories and requirements set by the client in timely manner.
* 3 - Developer completed all the user stories and requirements set by the client.
* 2 - Developer completed most of the user stories and requirements set by the client.
* 1 - Developer completed the user stories and requirements partially.

#### Organization

* 4 - Developer used a project management tool and updated their progress in real-time.
* 3 - Developer used a project management tool to keep their project organized.
* 2 - Developer used a project management tool but didn't update the progress frequently.
* 1 - Developer failed to use a project management tool to track its progress.

#### Test-Driven Development

* 4 - Project shows exceptional use of testing at different layers (above 95% coverage).
* 3 - Project shows adequate testing (90% - 95% coverage).
* 2 - Project shows gaps in test usage/coverage/design (85 - 90% coverage).
* 1 - Project lacks sufficient testing (under 85% coverage).

#### Code Quality

* 4 - Project demonstrates exceptionally well factored code.
* 3 - Project demonstrates solid code quality and MVC principles.
* 2 - Project demonstrates some gaps in code quality and/or application of MVC principles.
* 1 - Project demonstrates poor factoring and/or understanding of MVC.

#### User Experience

* 4 - Project exhibits a production-ready and polished UX.
* 3 - Project exhibits a production-ready user experience.
* 2 - Project exhibits some gaps in the UX.
* 1 - Project exhibits inattention to the user experience.

#### Performance

* 4 - Project pages load on average under 300 milliseconds.
* 3 - Project pages load on average under 400 milliseconds.
* 2 - Project pages load on average under 500 milliseconds.
* 1 - Project pages load on average over 500 milliseconds.

### Evaluations

#### Chelsea Worrel

Github:
Production:

* **Completion**:
* **Organization**:
* **Test-Driven Development**:
* **Code Quality**:
* **User Experience**:
* **Performance**:

#### Vanessa Gomez

Github: https://github.com/vanegomez/kindtripper<br>
Production: https://kindtripper.herokuapp.com

I committed the code that we changed on the branch
[evaluation-refactorings](https://github.com/vanegomez/kindtripper/commits/evaluation-refactorings),
so if you want to see how some of the ideas in the feedback
manifest, then check here. **--Josh**

* **Completion**: 4 - Developer completed all the user stories and requirements set by the client in timely manner.
* **Organization**: 3 - Developer used a project management tool to keep their project organized.
* **Test-Driven Development**:
  * Score: 4
  * All Files (100.0% covered at 14.08 hits/line)
  * The test that hits the api depends on the specific current data.
    This will be painful as it will likely change frequently and arbitrarily.

    If we look at how the numbers change rather than what their specific values are,
    then we can have the same confidence, but without the fragility.

    Eg, we can rewrite this test:

    ```ruby
    it 'can find or create a job' do
      jobs = Opening.find_or_create_job
      expect(jobs.count).to eq(198)

      Opening.find_or_create_job
      expect(Opening.count).to eq(198)
    end
    ```

    ```ruby
    expect(Opening.count).to eq 0
    jobs = Opening.find_or_create_job
    expect(jobs.length).to be > 0

    expect(Opening.count).to eq(jobs.length)
    Opening.find_or_create_job
    expect(Opening.count).to eq(jobs.length)
    ```
* **Code Quality**:
  * Score: 4
  * A nice small amount of JS to get just the right flourishes of interactivity (filtering / images)
  * Controllers were nice
  * No issues with any of the code
  * One thing we might do is pull the `find_or_create_job` method out of Opening and give it its own class or module.
    We can identify things like this because they wind up with a couple of methods to do a job that isn't inherently a part of being whatever the model is
    (eg this is a way to populate openings, but you can imagine any number of other ways to do this, including making test pulling from another api,
    caching the results on the file system rather than directly inserting them into the database, etc).
    When this happens, there will be independent sets of methods that work together amongst themselves, but not with the other methods on the class.
    This is a good indication that there is more than one responsibility, and they're all sitting in the same class, because they're related to it in some way.
    In the small, it's not a problem, but as we work in this code base for an extended period of time, we'll find that more and more of these independent responsibilities
    get added, and it becomes harder and harder to take any given method, understand the larger picture of how it fits into some workflow,
    who calls it, why, and to pull it out into its own object.

    People typically call this idea "cohesion". If the object does one thing, then we'll find that almost all of its methods operate on almost all of its data
    (because why else would the method be there?). This implies high cohesion, which implies that this method belongs with all the other ones around it.
    When an object has low cohesion, it's an indication that there is more than one responsibility in this class, and thus more than one object
    here. So if we have a class with 6 methods, method 1, 3, and 5 are all working together to do something useful, and methods 2, 5, and 6 are doing the same,
    but at no time do any of the methods in the first set work together with any of the methods in the second set, then we would identify this class as having
    low cohesion. From this, we can identify that there are probably two objects stuck together as one.

    So if we are attentive to such things, then we can spot these cases early, and pull them out into their own classes.
    In our case, we did this by pulling `Opening.find_or_create_job` and `Opening.parse_response` out into
    a module, `ImportOpenings`. Rails doesn't give you a place to put these kinds of things, but any directory that you create in `app`
    will be added to its autoload paths (and if you have one that's outside of app... ie lib), you can add it to autoload paths in [config](http://guides.rubyonrails.org/configuring.html)
    Which means that we can just replace any code that does `Opening.find_or_create_job` with `ImportOpenings.call`.
* **User Experience**: 4 - Project exhibits a production-ready and polished UX.
* **Performance**: 4 - Project pages load on average under 300 milliseconds.

#### Drew Reynolds

Github: http://github.com/NYDrewReynolds/collaborave<br>
Production: http://collaborave.herokuapp.com

* **Completion**: 4 - Developer completed all the user stories and requirements set by the client in timely manner.
* **Organization**: 3 - Developer used a project management tool to keep their project organized.
* **Test-Driven Development**: 2 - 88.41% (Includes Omniauth not being tested which we don't care about, but it does not include the API controller that should be tested)
* **Code Quality**: 3 (API controller has more logic than it should. Using non-RESTful actions in the API controller)
* **User Experience**: 4 - Project exhibits a production-ready and polished UX.
* **Performance**: 4 - Project pages load on average under 300 milliseconds.

#### Lev Kravinsky

Github: https://github.com/levthedev/CUPeru | https://github.com/levthedev/CUPeru-API<br>
Production: https://cuperu.herokuapp.com/

* **Completion**: 4 - Developer completed all the user stories and requirements set by the client in timely manner.
* **Organization**: 4 - Developer used a project management tool and updated their progress in real-time.
* **Test-Driven Development**: 3
* **Code Quality**: 3.5 - Try to avoid repetition of variables and split out logic to a place that it can be shared in multiple places, use methods to better express concepts*
* **User Experience**: 2 - Project exhibits some gaps in the UX.
* **Performance**: 4 - Project pages load on average under 300 milliseconds.

#### Erik Butcher

Github: https://github.com/with-a-k/trouble-center
Production:

* **Completion**:
* **Organization**:
* **Test-Driven Development**:

  ```
  2: Project shows gaps in test usage/coverage/design (85 - 90% coverage).

  5 runs, 10 assertions, 0 failures, 0 errors, 0 skips
  Coverage report generated for MiniTest to /Users/josh/deleteme/personal-projects/erik-butcher/coverage. 135 / 158 LOC (85.44%) covered.

  Some coverage is from test files
  ```
* **Code Quality**:
  * Score: 3
  * ActiveRecord classes are nice
  * A bit more consideration within Controllers as to how they affect the user flow through the app would
    lead to a few small changes that would turn into pretty big gains. eg troubles created while signed out
    being linked to the user when they sign in
  * Invalid troubles being rendered back into the form
  * Ability to edit troubles
* **User Experience**:
* **Performance**:

#### Rick Bacci

Github: https://github.com/RickBacci/foobr<br>
Production: https://foobr.herokuapp.com

* **Completion**:
* **Organization**:
* **Test-Driven Development**:
* **Code Quality**:
* **User Experience**:
* **Performance**:

#### Dave Mauer

Github: https://github.com/davemaurer/beer_bank<br>
Production: http://beerbank.herokuapp.com

* **Completion**: 3 - Developer completed all the user stories and requirements set by the client.
* **Organization**: 2 - Developer used a project management tool but didn't update the progress frequently.
* **Test-Driven Development**:
* **Code Quality**:
* **User Experience**: 2 - Project exhibits some gaps in the UX.
* **Performance**:  3 - Project pages load on average under 400 milliseconds.

#### Max Tedford

Github: https://github.com/maxtedford/road_tripper<br>
Production: https://road-tripper.herokuapp.com

* **Completion**: 4 - Developer completed all the user stories and requirements set by the client in timely manner.
* **Organization**: 4 - Developer used a project management tool and updated their progress in real-time.
* **Test-Driven Development**: 3
* **Code Quality**: 3
* **User Experience**: 4 - Project exhibits a production-ready and polished UX.
* **Performance**: 4 - Project pages load on average under 300 milliseconds.

#### Sally MacNicholas

Github: https://github.com/sallymacnicholas/fitbot<br>
Production: http://protected-tor-9723.herokuapp.com

* **Completion**: 4 - Developer completed all the user stories and requirements set by the client in timely manner.
* **Organization**: 2 - Developer used a project management tool but didn't update the progress frequently.
* **Test-Driven Development**:
* **Code Quality**:
* **User Experience**: 4 - Project exhibits a production-ready and polished UX.
* **Performance**: 1 - Project pages load on average over 500 milliseconds.

#### Brett Grigsby

Github: https://github.com/brettgrigsby/pantry_raid<br>
Production: https://pantry-raid.herokuapp.com

* **Completion**: 4 - Developer completed all the user stories and requirements set by the client in timely manner.
* **Organization**: 3 - Developer used a project management tool to keep their project organized.
* **Test-Driven Development**: 3 - (Surprisingly, tested OmniAuth in User model. FormMonster was not tested -- not sure it should be?? )
* **Code Quality**: 3 - (Use more ActiveRecord for filtering data instead of Ruby)
* **User Experience**: 3 - Project exhibits a production-ready user experience.
* **Performance**: 2 - Project pages load on average under 500 milliseconds.

#### Margarett Ly

Github: https://github.com/aoili/drank<br>
Production: https://dranks.herokuapp.com

* **Completion**: 2 - Developer completed most of the user stories and requirements set by the client.
* **Organization**: 4 - Developer used a project management tool and updated their progress in real-time.
* **Test-Driven Development**:
* **Code Quality**:
* **User Experience**: 3 - Project exhibits a production-ready user experience.
* **Performance**: 1 - Project pages load on average over 500 milliseconds.

#### Josh Cass

Github:
Production:

* **Completion**:
* **Organization**:
* **Test-Driven Development**: 3 - (Some sad paths not tested and Omniauth tests are missing but all core functionality is tested)
* **Code Quality**: 4 (Could split out HTTP requests into service objects instead of the model, but the controllers and methods are very clean.)
* **User Experience**:
* **Performance**:

#### Jamie Kawahara

Github:
Production:

* **Completion**:
* **Organization**:
* **Test-Driven Development**: 3 - 91.5% (Omniauth not tested)
* **Code Quality**: 3 - Good use of Service object and Background workers. Could refactor Service usage duplication, using a presenter in the controller, and using ActiveRecord to limit records loaded into memory.
* **User Experience**:
* **Performance**:

#### Robert Cornell

Github: https://github.com/RMCornell/one_feed<br>
Production: https://one-feed.herokuapp.com

* **Completion**: 3 - Developer completed all the user stories and requirements set by the client.
* **Organization**: 3 - Developer used a project management tool to keep their project organized.
* **Test-Driven Development**:
* **Code Quality**:
* **User Experience**: 2 - Project exhibits some gaps in the UX.
* **Performance**: 3 - Project pages load on average under 400 milliseconds.

#### Justin Holmes

Github: https://github.com/Justin-Holmes/Spoterize<br>
Production: https://the-real-spotifize.herokuapp.com

* **Completion**: 4 - Developer completed all the user stories and requirements set by the client in timely manner.
* **Organization**: 4 - Developer used a project management tool and updated their progress in real-time.
* **Test-Driven Development**: 4 - Project shows exceptional use of testing at different layers (above 95% coverage)
* **Code Quality**:    4 - Project demonstrates exceptionally well factored code
* **User Experience**: 4 - Project exhibits a production-ready and polished UX.
* **Performance**: 2.5 - Project pages load on average under 500 milliseconds.

#### Whitney Hiemstra

Github: https://github.com/whithub/music_story<br>
Production: http://music-story.herokuapp.com

* **Completion**: 4 - Developer completed all the user stories and requirements set by the client in timely manner.
* **Organization**: 4 - Developer used a project management tool and updated their progress in real-time.
* **Test-Driven Development**:
* **Code Quality**:
* **User Experience**: 2 - Project exhibits some gaps in the UX.
* **Performance**: 1 - Project pages load on average over 500 milliseconds.

#### Morgan Miller

Github: https://github.com/morganmiller/whats-in-a-word<br>
Production: https://whatsinaword.herokuapp.com

* **Completion**: 4 - Developer completed all the user stories and requirements set by the client in timely manner.
* **Organization**: 3 - Developer used a project management tool to keep their project organized.
* **Test-Driven Development**:
* **Code Quality**:
* **User Experience**: 4 - Project exhibits a production-ready and polished UX.
* **Performance**: 2 - Project pages load on average under 500 milliseconds.

#### Andrew Fink

Github: https://github.com/adfink/tribehire<br>
Production: https://thawing-mesa-2346.herokuapp.com

* **Completion**: 2 - Developer completed most of the user stories and requirements set by the client.
* **Organization**: 1 - Developer failed to use a project management tool to track its progress.
* **Test-Driven Development**:
* **Code Quality**:
* **User Experience**: 2.5 - Project exhibits some gaps in the UX.
* **Performance**: 2 - Project pages load on average under 500 milliseconds.

#### Jack Yeh

Github:
Production:

* **Completion**:
* **Organization**:
* **Test-Driven Development**:
* **Code Quality**:
* **User Experience**:
* **Performance**:
