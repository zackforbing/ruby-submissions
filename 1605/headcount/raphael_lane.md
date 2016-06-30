Evaluated By: Beth Sebian

Repo: https://github.com/Laner12/headcount

Notes:
- Completed through I4
- All spec harness tests pass through I4
- All team-generated tests pass
- Need more unit testing and edge cases, some nice testing around edge case -- want to see consistency here
- Lots of long methods (5+), if/else statements
- Nice use of enumerables, some areas could be tighter
- One code sanitation failure, line >80 chars; excluding given spec's long method names

Scores:
## Evaluation Rubric

The project will be assessed with the following guidelines:

### 1. Functional Expectations
* 2: Application has some missing functionality but no crashes

### 2. Test-Driven Development
* 3: Application is well tested but does not balance isolation and integration tests, using only the data necessary to test the functionality

### 3. Encapsulation / Breaking Logic into Components
* 3: Application effectively breaks logical components apart but breaks the principle of SRP

### 4. Fundamental Ruby & Style
* 2:  Application runs but the code has long methods, unnecessary or poorly named variables, and needs significant refactoring

### 5. Enumerable & Collections
* 3: Application demonstrates comfortable use of appropriate Enumerable methods

### 6. Code Sanitation
The output from `rake sanitation:all` shows...
* 4: Zero complaints

