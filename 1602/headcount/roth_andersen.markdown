Assessed By: Horace

Repo: https://github.com/jaredroth/headcount

Notes:

* Passes spec harness through i5 -- solid 3 on completion
* Overall succesful in managing data flow and processing through the repos
* In general strong style around how we're handling things; only a few quibbles around naming, method division, etc
* Looked at some interesting ideas around how we might pull out handlers for different processes in a more declarative way
* enums, etc are pretty string; using some group by especially; maybe think about reduce instead of each with object
* Where this starts to break down is in the Analyst -- you have the right pieces and some good techniques, but they could benefit from more organizaiton,
especially from the perspective of carving out smaller helper classes to do some of the lower responsibilities
* test coverage and breadth are both great; still would like to see more usage of more curated / specific data and attacking the tests
at lower levels

### 1. Functional Expectations

* 3: Application fulfills expectations of Iterations 0 - 4 *as well as* one of Iterations 5 or 6

### 2. Test-Driven Development

* 3: Application is well tested but does not balance isolation and integration tests, using only the data necessary to test the functionality

### 3. Encapsulation / Breaking Logic into Components

* 3: Application effectively breaks logical components apart but breaks the principle of SRP

### 4. Fundamental Ruby & Style

* 3:  Application shows strong effort towards organization, content, and refactoring

### 5. Enumerable & Collections

* 4: Application consistently makes use of the best-choice Enumerable methods

### 6. Code Sanitation

The output from `rake sanitation:all` shows...

* 4: Zero complaints
