Evaluated By: Mike

Repo:A http://github.com/roscalabrin/headcount

Notes:
* 45 tests, 87 assertions, 95 percent coverage
* Overall tested well, could have used some more tests that cover alternate
or sad path testing.
* look at not exposing the entire attributes hash of an object, and rahter
creating your own tight interfaces

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

* 1: More than ten complaints

