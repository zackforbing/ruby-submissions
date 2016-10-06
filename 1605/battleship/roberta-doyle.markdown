Assessed By: Horace

Repo: https://github.com/roscalabrin/battleship

Notes:

* Lot of progress and seems like some good learning came out of all of it
* Game gets through most of the gameplay but has some trouble finishing out the sequence
when the player wins
* A few categories of improvements we might make stand out:
* Looked at taking sequences of methods that get used in a linear process and isolating them
from one another so that i could use JUST step 1 if i wanted to in isolation
* talked about focusing on return values of methods and how this improves testability of the project
* Also keep looking out for opportunities to take a handful of individual but similar values / variables / etc
and put them into 1 collection (rather than storing row_a, row_b, etc)
* Obviously using enumerable methods effectively will be the key to this
* Several of the objects are still a bit large, especially from the perspective of how many instance variables we
are storing -- when we start to see this, need to ask if we can make multiple different objects out of the big one


Scores:

### 1. Fundamental Ruby & Style

* 3:  Application shows strong effort towards organization, content, and refactoring

### 2. Enumerable & Collections

* 2: Application demonstrates functional knowledge of Enumerable but only uses the most basic techniques

### 3. Test-Driven Development

* 2: Application makes some use of tests, but the coverage is insufficient

### 4. REPL Interface

* 2: Application's REPL has some inconsistencies or rough edges

### 5. Breaking Logic into Components

* 3: Application effectively breaks logical components apart with clear intent and usage
