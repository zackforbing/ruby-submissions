Assessed By: Beth Sebian

Repo: https://github.com/kctrlv/black_thursday/

Notes: 
* Test-suite: 130 examples, all passing
* Spec-harness passes i0-3, 5
* Sanitation: no errors 
* Solid test suite, some inconsistencies with mocking (marginal issue) 
* Extracted MathAnalyst into module
* Best-choice enumerables used, overall clean codebase
* One highlighted integration test with invoices...great concept, would like to see more
* Generally strong application of SRP, would like to see SalesAnalyst broken apart, more intuitive delegation to modules

### 1. Functional Expectations
3.5
* 4: Application implements iterations 0, 1, 2, 3, (4 or 5), and features of your own design

### 2. Test-Driven Development
* 3: Application is well tested but does not balance isolation and integration tests, using only the data necessary to test the functionality

### 3. Encapsulation / Breaking Logic into Components
3.5
* 4: Application is expertly divided into logical components each with a clear, single responsibility
* 3: Application effectively breaks logical components apart but breaks the principle of SRP

### 4. Fundamental Ruby & Style
3.5
* 4:  Application demonstrates excellent knowledge of Ruby syntax, style, and refactoring
* 3:  Application shows strong effort towards organization, content, and refactoring

### 5. Enumerable & Collections
* 4: Application consistently makes use of the best-choice Enumerable methods

### 6. Code Sanitation
The output from `rake sanitation:all` shows...
* 4: Zero complaints
