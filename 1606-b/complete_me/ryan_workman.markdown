Assessed By:

Repo:

Notes:


## Extensions

### 1. Denver Addresses

Working with words was interesting, but what about a bigger dataset? Check out [this data file](http://data.denvergov.org/dataset/city-and-county-of-denver-addresses) (you'll want the CSV version) that contains all the known addresses in the city of Denver. Use the `full_address` field that's last in the row. Can you make your autocomplete work with that dataset?

### 2. Substrings

Could your word lookup possibly handle middle-of-the-word matches? So that `com` would list both the possibilities `complete` and `incomplete`? How does this change the memory requirements of your running program?

### 3. Visual Interface

Can you create a graphical user interface for your code? Something that a "normal person" might plausibly use? Consider a toolkit like [Shoes](http://shoesrb.com/) or [Ruby Processing](https://github.com/jashkenas/ruby-processing).

### 4. Automated Reporting

* Setup [SimpleCov](https://github.com/colszowka/simplecov) to monitor test coverage along the way

## Evaluation Rubric

The project will be assessed with the following rubric:

### 1. Functional Expectations

* 4: Application fulfills all base expectations and one extension
* 3: Application fulfills all base expectations
* 2: Application is missing one base expectation
* 1: Application is missing more than one base expectation

### 2. Test-Driven Development

* 4: Application is broken into components which are well tested in both isolation and integration using appropriate data
* 3: Application is well tested but does not balance isolation and integration tests, using only the data necessary to test the functionality
* 2: Application makes some use of tests, but the coverage is insufficient
* 1: Application does not demonstrate strong use of TDD

### 3. Encapsulation / Breaking Logic into Components

* 4: Application is expertly divided into logical components each with a clear, single responsibility
* 3: Application effectively breaks logical components apart but breaks the principle of SRP
* 2: Application shows some effort to break logic into components, but the divisions are inconsistent or unclear
* 1: Application logic shows poor decomposition with too much logic mashed together

### 4. Fundamental Ruby & Style

* 4:  Application demonstrates excellent knowledge of Ruby syntax, style, and refactoring
* 3:  Application shows strong effort towards organization, content, and refactoring
* 2:  Application runs but the code has long methods, unnecessary or poorly named variables, and needs significant refactoring
* 1:  Application generates syntax error or crashes during execution

### 5. Enumerable & Collections

* 4: Application consistently makes use of the best-choice Enumerable methods
* 3: Application demonstrates comfortable use of appropriate Enumerable methods
* 2: Application demonstrates functional knowledge of Enumerable but only uses the most basic techniques
* 1: Application demonstrates deficiencies with Enumerable and struggles with collections

