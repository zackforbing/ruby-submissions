Assessed By: Andrew

Repo: github.com/theonlyrao/black_thursday

Notes:

* Functionally everything works well, tests run, harness passes. A little redundant code, but overall looked really good.
* Tests were getting to a good place but were lacking a little. Need to be a little more disciplined with writing tests. Also saw some tests with fixtures and some without.
* Logic was broken into components pretty well. There was some repetitive code in each repository to parse the csv and when commented out the tests still passed. So there is room for improvement, but on the right track.
* Enumerables looked really good. Where they were implemented there is significant room to refactor, particularly for clarity, but good use of group_by, reduce, map etc. 


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
