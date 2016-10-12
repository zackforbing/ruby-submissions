Assessed By: Jeff 

github_repo: https://github.com/Riizu/rush-hour

Notes: 
* write at least 2 tests for each error code - test each error code in different ways
* watch for subtle naming problems (create_payload v. create payload and client) 
* if you get a detailed spec, think about the right things AND all the ways things could go wrong
* be more detailed, specific when displaying data such as most frequent request types - be clearer with labeling, and show percentages, for example, rather than just a list
* limit DB queries - access DB once, then manipulate the data 
* TDD: tests should be a little more advanced, more coverage 
* consistency in formatting (!client vs. existance == false) 
* long if/else statements: first pull out any long code within so that you can see what is going on within if/else - whether some are really the same, etc. 
* create a payload build method so that the setup can be changed easily if you find a better way to create payload 


## Evaluation Rubric

The project will be assessed with the following rubric:

#### 1. Functional Expectations


* 3: Application fulfills base expectations


#### 2. Test-Driven Development


* 3: Application is well tested but does not balance isolation and integration/feature tests


#### 3. Encapsulation / Breaking Logic into Components


* 3: Application effectively breaks logical components apart but breaks the principle of SRP


#### 4. Fundamental Ruby & Style


* 3: Application shows strong effort towards organization, content, and refactoring

#### 5. Sinatra / Web and Business Logic


* 3: Application makes good use of Sinatra but has some mixing of the web and business logic.


#### 6. View Layer


* 3: Application breaks components out to view partials but has some logic or complexity leaking into the view


While you won't be graded on workflow for Rush Hour, here's an example of how you will be evaluated on workflow later in the module:

#### Workflow (NOT GRADED)

* 4: Excellent use of branches, pull requests, and a project management tool.
* 3: Good use of branches, pull requests, and a project-management tool.
* 2: Sporadic use of branches, pull requests, and/or project-management tool.
* 1: Little use of branches, pull requests, and/or a project-management tool.
