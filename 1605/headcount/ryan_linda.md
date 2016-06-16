Evaluated By: Horace

Repo: https://github.com/ryanflach/headcount

Notes:

* Completed required iterations and iteration 5 for spec harness woooo
* Overall very clean code that aims for conciseness and is relatively readable
* Doing pretty well at pulling logic into the smaller objects in the system -- however
we could still do more of that
* so far doing some formatting and presence-checking on e.g. StatewideTest, Enrollment, EconProfile
* Those are great but these classes can also shoulder some of the weight for actual calculations as well
* tend to end up with headcount analyst doing: 1) data acquisition and aggregation 2) data validation and formatting,
3) actual calculations
* We could get this to be just #3 and maybe a bit of #1
* Enums are overall pretty solid -- main theme here is looking at separating complex processes into multiple steps
that each leverage a dedicated enum technique (rather than cramming various logic into one pass)

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

* 4:  Application demonstrates excellent knowledge of Ruby syntax, style, and refactoring

### 5. Enumerable & Collections

* 3: Application demonstrates comfortable use of appropriate Enumerable methods

### 6. Code Sanitation

The output from `rake sanitation:all` shows...

* 4: Zero complaints
