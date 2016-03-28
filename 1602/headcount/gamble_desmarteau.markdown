Assessed By: Horace

Repo: https://github.com/mdes41/headcount

Notes:

* Functional through I5 -- hits requirements there
* 80% doing great with method size / complexity, then have a handful scattered around that are getting larger
* Mostly using enums to proper effect -- looked at a few spots where we're using map but not actually mapping or using each to iteratively modify some values
* Testing is quite strong -- one of the stronger points of the project; mostly because we're both doing small isolated unit tests with hand-rolled data on our low-level methods AND doing the high-level integration stuff by passing in the whole pile of CSV files
* Looked at method interface constraints -- often in this project the spec forces you to define methods in certain ways, but we can still manage that complexity internally by having that method actually delegate out to other methods that implement the various cases

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

* 4: Zero complaints
