## Template

### Team:

### Repo:

### Assessed By:

### Notes

### Rubric

* **Functional Expectations** (1 - 4)
* **TDD** (1 - 4)
* **Encapsulation / Breaking Logic into Components** (1 - 4)
* **Fundamental Ruby & Style** (1 - 4)
* **Enumerable & Collections** (1 - 4)
* **Sanitation** (1 - 4)

#### 1. Functional Expectations

* 4: Application fulfills all base expectations and two extensions
* 3: Application fulfills all base expectations as tested by the spec harness
* 2: Application has some missing functionality but no crashes
* 1: Application crashes during normal usage

#### 2. Test-Driven Development

* 4: Application is broken into components which are well tested in both isolation and integration using appropriate data
* 3: Application is well tested but does not balance isolation and integration tests, using only the data necessary to test the functionality
* 2: Application makes some use of tests, but the coverage is insufficient
* 1: Application does not demonstrate strong use of TDD

#### 3. Encapsulation / Breaking Logic into Components

* 4: Application is expertly divided into logical components each with a clear, single responsibility
* 3: Application effectively breaks logical components apart but breaks the principle of SRP
* 2: Application shows some effort to break logic into components, but the divisions are inconsistent or unclear
* 1: Application logic shows poor decomposition with too much logic mashed together

#### 4. Fundamental Ruby & Style

* 4:  Application demonstrates excellent knowledge of Ruby syntax, style, and refactoring
* 3:  Application shows strong effort towards organization, content, and refactoring
* 2:  Application runs but the code has long methods, unnecessary or poorly named variables, and needs significant refactoring
* 1:  Application generates syntax error or crashes during execution

#### 5. Enumerable & Collections

* 4: Application consistently makes use of the best-choice Enumerable methods
* 3: Application demonstrates comfortable use of appropriate Enumerable methods
* 2: Application demonstrates functional knowledge of Enumerable but only uses the most basic techniques
* 1: Application demonstrates deficiencies with Enumerable and struggles with collections

#### 6. Code Sanitation

The output from `rake sanitation:methods` shows...

* 4: Zero complaints
* 3: Five or fewer complaints
* 2: Six to ten complaints
* 1: More than ten complaints

## Beth & Brennan

### Repo: https://github.com/brennanholtzclaw/headcount

### Assessed By: Horace

### Notes

* Great testing overall - quite thorough and voluminous and covering
juicy edge cases
* Completion is solid through I2; starting to dig into the I3 topics
* Code is pretty consistent across the board
* Main consistent weaknesses are over-reliance on `each` as the only
iterator and difficulty flattening code branches into more linear
steps that can be understood more easily
* Has handful of "whoa" methods where things break down in terms of structure,
hierarchy, and length

### Rubric

#### 1. Functional Expectations

* 2: Application has some missing functionality but no crashes

#### 2. Test-Driven Development

* 3: Application is well tested but does not balance isolation and integration tests, using only the data necessary to test the functionality

#### 3. Encapsulation / Breaking Logic into Components

* 3: Application effectively breaks logical components apart but breaks the principle of SRP

#### 4. Fundamental Ruby & Style

* 3:  Application shows strong effort towards organization, content, and refactoring

#### 5. Enumerable & Collections

* 2: Application demonstrates functional knowledge of Enumerable but only uses the most basic techniques

#### 6. Code Sanitation

The output from `rake sanitation:methods` shows...

* 3: Five or fewer complaints

## Beth & Brennan

### Repo: https://github.com/brennanholtzclaw/headcount

### Assessed By: Horace

### Notes

* Great testing overall - quite thorough and voluminous and covering
juicy edge cases
* Completion is solid through I2; starting to dig into the I3 topics
* Code is pretty consistent across the board
* Main consistent weaknesses are over-reliance on `each` as the only
iterator and difficulty flattening code branches into more linear
steps that can be understood more easily
* Has handful of "whoa" methods where things break down in terms of structure,
hierarchy, and length

### Rubric

#### 1. Functional Expectations

* 2: Application has some missing functionality but no crashes

#### 2. Test-Driven Development

* 3: Application is well tested but does not balance isolation and integration tests, using only the data necessary to test the functionality

#### 3. Encapsulation / Breaking Logic into Components

* 3: Application effectively breaks logical components apart but breaks the principle of SRP

#### 4. Fundamental Ruby & Style

* 3:  Application shows strong effort towards organization, content, and refactoring

#### 5. Enumerable & Collections

* 2: Application demonstrates functional knowledge of Enumerable but only uses the most basic techniques

#### 6. Code Sanitation

The output from `rake sanitation:methods` shows...

* 3: Five or fewer complaints

## Aaron & Toni

### Repo: https://github.com/ToniRib/headcount

### Assessed By: Horace

### Notes

* Excellent work overall; code is clean both at the low level (methods, lines, etc)
and at the high level design
* Good use of abstractions around pulling out and manipulating data -- helps
keep the analytical structure very clean
* Volumnious testing -- covering everything including various helper/data processing
operations within the test suite
* Completes all iterations and the team seems to have spent a lot of time helping
the group overall, including lots of spec harness contributions

### Rubric

* **Functional Expectations** 4
* **TDD** 4
* **Encapsulation / Breaking Logic into Components** 4
* **Fundamental Ruby & Style** 4
* **Enumerable & Collections** 4
* **Sanitation** 4

## Admir / Alex

### Repo:

https://github.com/Salvi6God/headcount/tree/iteration0

https://github.com/Draganovic/headcount

### Assessed By: Horace

### Notes

* Admir and Alex decided to split partway through the project and each
work independently
* The 2 projects reached a comparable level of completion -- still mostly
working through some basic data processing for the first iterations
* Struggles around workflow and process slowed down the project at the
beginning
* Main objective for next time around is to really hammer on fundamentals
so that when we get back to this project we can move at a much more
fluid pace

### Rubric

* **Functional Expectations** 1
* **TDD** 3 / 2
* **Encapsulation / Breaking Logic into Components** 3
* **Fundamental Ruby & Style** 3
* **Enumerable & Collections** 3
* **Sanitation** 3


## Hector & Taylor

### Repo: https://github.com/hectorhuertas/headcount

### Assessed By: Horace

### Notes

* Testing / TDD seems solid overall
* Good use of tests to make sure that each object can be used in
isolation
* Open-ended interfaces for objects makes it easy to pass customized
data in for each test case
* top-level data processing and repo / record-creation flow is clean
and easy to follow
* Code complexity & length starts to fall down a lot in the analysis
section. We discussed some ways to improve this by isolating argument
and option parsing (determining which branch is need) from the methods
that actually perform the calculations
* Overall we might not reduce the amount of code, but we can probably
organize in a way that's easier to follow
* Finally, completion issues with the spec harness seem to stem from
challenges dealing with data gaps or formats -- probably needed to
identify this problem earlier. maybe by including more "bad data"
in the tests from the beginning
* Completion is good through I2 baseline (happy path); then has gaps
around the missing data / edge case parsing

### Rubric

* **Functional Expectations** 2
* **TDD** 3
* **Encapsulation / Breaking Logic into Components** 3
* **Fundamental Ruby & Style** 2 -- needs some work refactoring analysis methods
* **Enumerable & Collections** 4
* **Sanitation** 3
