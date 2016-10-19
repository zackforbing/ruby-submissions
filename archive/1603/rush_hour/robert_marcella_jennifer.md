Assessed By: Jeff

github_repo: https://github.com/MsJennyGiraffe/rush-hour-skeleton

## Rush Hour Evaluation

#### Notes:

* Tests: 73 runs, 103 assertions
*  Overall testing good. One thing: change of state is what we are seeking to figure out in the test, so for a test that displays an error when a duplicate payload request is submitted, for instance, add an additional assertion to confirm that the error does not appear until repeat request sent. 
*  As you get more experienced with TDD and programming process, you'll come to anticipate small potential errors of aspects of the program in advance. For instance, you could have added edge cases like substrings that had occurred in a previous request. Each minor function of a program in the industry commonly has two plus tests.
* When testing, remember that you're often watching state change. 
  * Assert that something exists before creating a duplication and checking for an error.
* Would have liked to see more tests that reveal how program actually works, not just spec functionality.
  * Each minor piece of functionality should have two tests.
* With data breakdowns, it's a good idea to include percentages.
* Always test error pages. 
* Feature tests often get long when you're thoroughly testing, so group by scenario.
* Some of your tests have walls of data, and it's hard to tell what's unique for each instance. Create a base_payload and change only the element you want to change between payload requests so we can see what information is unique.
  * You can use merge({key: "change"}) to make and highlight changes that come from the same base hash.
* Functionality good.
* Well broken apart
* Could use more file structure.
  * As soon as models has 13 files, maybe it's time to further organize them.
* Think about ownership and push logic down the stack.
* Presentational should be in the views, not models.
* Stay away from magic numbers.
* Like the use of modules to make the server skinny. Instead of putting server modules in models, put them in a separate folder, their own (server_models)
* Components not quite isolated and pushed down stack enough - URL knows too much about payload_requests
* Like the simplicity of the web interface and use of tables.
* Impressed by effective use of ActiveRecord methods for the time you've been introduced to them.

#### 1. Functional Expectations

* 3: Application fulfills base expectations

#### 2. Test-Driven Development

* 3: Application is well tested but does not balance isolation and integration/feature tests

#### 3. Encapsulation / Breaking Logic into Components

* 4: Application is expertly divided into logical components each with a clear, single responsibility

#### 4. Fundamental Ruby & Style

* 3: Application shows strong effort towards organization, content, and refactoring

#### 5. Sinatra / Web and Business Logic

* 4: Application takes advantage of all the features Sinatra has to offer and effectively separates the web application from the business logic.

#### 6. View Layer

* 3: Application breaks components out to view partials but has some logic or complexity leaking into the view
