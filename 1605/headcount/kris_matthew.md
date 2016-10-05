Evaluated By: Mike

Repo: http://github.com/matthewecampbell/headcount

Notes:
* 33 seconds to run tests,
*  84 tests, 143 asertions, 98.16 coverage
* Look to use instance variable instead of exposing the entire hash to the
outside
* Extensive use of modules, to separate code, but needs to take it to the
next level, some classes are a wee bit too long.
* Some repetition of code especially with FILE IO stuff.
* The each pattern where shovelling into a collection instead of using map
* Iteration six

Scores:

## Evaluation Rubric

The project will be assessed with the following guidelines:

### 1. Functional Expectations

* 3: Application fulfills expectations of Iterations 0 - 4 *as well as* one of Iterations 5 or 6

### 2. Test-Driven Development

* 3: Application is well tested but does not balance isolation and integration tests, using only the data necessary to test the functionality

### 3. Encapsulation / Breaking Logic into Components

* 3: Application effectively breaks logical components apart but breaks the principle of SRP

### 4. Fundamental Ruby & Style

* 3:  Application shows strong effort towards organization, content, and refactoring

### 5. Enumerable & Collections

* 3: Application demonstrates comfortable use of appropriate Enumerable methods

### 6. Code Sanitation

The output from `rake sanitation:all` shows...

* 4: Zero complaints

