Assessed By: Beth Sebian

Repo: https://github.com/kswhyte/battleship.1mod

Notes:
- Project missing some functionality: allowed player to place ships where they shouldn't be placed, play loop not developed
- Testing strong
- Existing REPL interface strong, but incomplete
- Enumerables weak since play loop missing
- Nice division of responsibility between methods in game, would like to see a method to manage the flow from one to another, instead of each method waterfalling to the next. 

## Evaluation Rubric

The project will be assessed with the following rubric:

### 1. Fundamental Ruby & Style
* 3:  Application shows strong effort towards organization, content, and refactoring

### 2. Enumerable & Collections
* 2: Application demonstrates functional knowledge of Enumerable but only uses the most basic techniques

### 3. Test-Driven Development
* 3: Application is well tested but does not balance isolation and integration tests

### 4. REPL Interface
* 2: Application's REPL has some inconsistencies or rough edges

### 5. Breaking Logic into Components
* 2: Application shows some effort to break logic into components, but the divisions are inconsistent or unclear
