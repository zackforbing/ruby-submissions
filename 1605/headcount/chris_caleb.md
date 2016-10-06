Evaluated By: Horace

Repo: https://github.com/concach/headcount

Notes:

* Completed required iterations including iteration 5
* Overall ruby style is very concise and clean
* Still seeing handful of ruby weirdness -- returns, lots of ternaries, etc
* Established a very consistent pattern around how data is loaded and stored -- once we figure
out how Enrollment data works, the others follow that same pattern pretty consistently
* Good job isolating the "number crunching" in the analyst using that Data module from
the fetching / aggregating logic
* Biggest thing we could bring in is more responsibility and leverage on the "leaf" objects
-- how can we give these things bigger jobs to do so that the upper-layers in turn become simpler
* As a HeadcountAnalyst, I can get back some data and do a bunch of formatting/validating on that
myself, but it would be cooler if it just came back in the proper format (DDD -- etc)

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

