Evaluated By: Mike

Repo: https://github.com/allindow/headcount

Notes:
* Did Iteration 6.
* 102 runs, 140 assertions, completed in 65 seconds, 98 percent test coverage.
* Has some fixture data, cool!
* very well tested - watch for situations where hardcoding can defeat tests
* tighten up interfaces by not giving access to the kitchen sink
* Spec harness took six seconds.
* think about controlling interfaces to objects better - split incoming hashes
at initialize, and dont make your own getter methods

Scores:

## Evaluation Rubric

The project will be assessed with the following guidelines:

### 1. Functional Expectations

* 3: Application fulfills expectations of Iterations 0 - 4 *as well as* one of Iterations 5 or 6

### 2. Test-Driven Development

* 4: Application is broken into components which are well tested in both isolation and integration using appropriate data

### 3. Encapsulation / Breaking Logic into Components

* 3: Application effectively breaks logical components apart but breaks the principle of SRP

### 4. Fundamental Ruby & Style

* 3:  Application shows strong effort towards organization, content, and refactoring

### 5. Enumerable & Collections

* 3: Application demonstrates comfortable use of appropriate Enumerable methods

### 6. Code Sanitation

The output from `rake sanitation:all` shows...

* 4: Zero complaints
