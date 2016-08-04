Assessed By: Beth Sebian

Repo: https://github.com/bfpepper/black_thursday

Notes:
* Spec harness passes, i1-4
* Test suite: 137 examples, zero failures
* Sanitation: 0 errors 
* Nice use of ||= with ivars (hence the 3.5) - some other areas warrant improvement (redundant calling of local vars)
* Completed i0-4 plus extension
* Best-choice enumerables

### 1. Functional Expectations
* 4: Application implements iterations 0, 1, 2, 3, (4 or 5), and features of your own design

### 2. Test-Driven Development
* 3: Application is well tested but does not balance isolation and integration tests, using only the data necessary to test the functionality

### 3. Encapsulation / Breaking Logic into Components
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
