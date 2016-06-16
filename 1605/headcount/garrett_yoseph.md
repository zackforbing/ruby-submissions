Evaluated By:
Beth Sebian

Repo: https://github.com/Yoyo2Code/headcount

Notes:
- Spec harness: I0SH: pass, I1SH: pass, I2SH: pass, I3SH: two failures
- Some long methods juggling a lot of detailed responsibility
- Missing some unit tests, would like to see more unit testing to drive development
- Some nice implementations of enumerables
- Code sanitation: several >80 char lines: blaming it on spec's long method names. Pass

Scores:
## Evaluation Rubric
The project will be assessed with the following guidelines:

### 1. Functional Expectations
* 2.5: Application has some missing functionality but no crashes

### 2. Test-Driven Development
* 3: Application is well tested but does not balance isolation and integration tests, using only the data necessary to test the functionality

### 3. Encapsulation / Breaking Logic into Components
2.5 - (Application effectively breaks logical components apart but breaks the principle of SRP / Application shows some effort to break logic into components, but the divisions are inconsistent or unclear)

### 4. Fundamental Ruby & Style
* 2:  Application runs but the code has long methods, unnecessary or poorly named variables, and needs significant refactoring

### 5. Enumerable & Collections
* 3: Application demonstrates comfortable use of appropriate Enumerable methods

### 6. Code Sanitation
The output from `rake sanitation:all` shows...
* 4: Zero complaints

