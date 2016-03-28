Assessed By: Mike

Repo: http://github.com/notmarkmiranda/black_thursday

Notes:
* 118 runs, 131 asertions, runs in 40s.
* 99 percent test coverage, test suite uses partial fixtures.
* Lower order classes have some extraneous getter methods.
* In Sales Analyst, some of the methods are overly long, some of the math
I'd like to have seen pulled out into another object like a helper class
or module or something.

### 1. Functional Expectations

* 3: Application implements iterations 0, 1, 2, 3, and either 4 or 5

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
