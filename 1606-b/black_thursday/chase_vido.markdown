Assessed By: Beth Sebian

Repo: https://github.com/Cdunagan05/black_thursday

Notes:
* Test suite with 174 examples, all passing 
* Sanitation passes with no errors 
* Test harness passing through 4 (i0-4)
* Some opportunities for refactoring: long methods (2), wonky if/else statements
* Overall fairly clean implementation of most functionality
* Test suite could benefit from mocking, sufficient to validate most functionality
* Would like to see integration testing of features as _supplement_ to isolation testing

### 1. Functional Expectations
3.5
* 4: Application implements iterations 0, 1, 2, 3, (4 or 5), and features of your own design
* 3: Application implements iterations 0, 1, 2, 3, and either 4 or 5

### 2. Test-Driven Development
* 3: Application is well tested but does not balance isolation and integration tests, using only the data necessary to test the functionality

### 3. Encapsulation / Breaking Logic into Components
* 3: Application effectively breaks logical components apart but breaks the principle of SRP

### 4. Fundamental Ruby & Style
2.5 
* 3:  Application shows strong effort towards organization, content, and refactoring
* 2:  Application runs but the code has long methods, unnecessary or poorly named variables, and needs significant refactoring

### 5. Enumerable & Collections
* 4: Application consistently makes use of the best-choice Enumerable methods

### 6. Code Sanitation
The output from `rake sanitation:all` shows...
* 4: Zero complaints
