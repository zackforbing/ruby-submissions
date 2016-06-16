Evaluated By: Horace

Repo: https://github.com/twhitinger/headcount

Notes:

* completed project, passes spec harness; includes good amount of their own tests; code runs pretty quickly
* Overall good job managing complexities of data loading and ingestion
* Looked at a couple habits around over-use of instance variables, especially using them as a way to return data
between methods and using them as a bit of a crutch during complex looping operations -- in general see if you can
do this with local data instead
* Other major theme around analysis is trying to push more robust logic and responsibilities down to the "leaf" objects
in your project tree -- we tend to treat these things as dumb containers for data but we can distribute some of the
responsibilities more evenly by leveraging these objects as well (law of demeter, etc)
* handful of strange style thigns going on (indentation, creative use of "\")

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

