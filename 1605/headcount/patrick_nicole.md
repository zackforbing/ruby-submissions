Evaluated By:
Beth Sebian

Repo:
https://github.com/NicoleKMarino/headcount/

Notes:
- Ran into a merge conflict immediately before assessment -- spec harness failure, code not consolidated on one branch
- I0SH: pass, I1SH: fails, I4: pass, rest failures
- Group to address merge issues (touch only Headcount Analyst, Headcount Analyst Test, and merge)
- Test mostly covered high-level functionality, would like to see more unit testing
- Some gaps in testing, ex: parser
- Test suite would not complete
- Opportunities to refactor: if/else statements; code otherwise quite readable
- Sanitation: lines > 80 and white space trailing lines

Re-Assessment
- I0: pass, I1: error, I2: errors (file loading), 3 failed assertions


Scores:

## Evaluation Rubric

The project will be assessed with the following guidelines:

### 1. Functional Expectations
* 1: Application crashes during normal usage
* Reassessment score: 1 (Considering the spec harness failed during the assessment and when we reviewed the code later, the reassessment score remains a 1)

### 2. Test-Driven Development
* 0: Pending re-eval
* Reassessment score: 2 (Application makes some use of tests, but the coverage is insufficient)

### 3. Encapsulation / Breaking Logic into Components
* 3: Application effectively breaks logical components apart but breaks the principle of SRP

### 4. Fundamental Ruby & Style
* 3:  Application shows strong effort towards organization, content, and refactoring

### 5. Enumerable & Collections
* 3: Application demonstrates comfortable use of appropriate Enumerable methods

### 6. Code Sanitation
The output from `rake sanitation:all` shows...
* 3: Five or fewer complaints
