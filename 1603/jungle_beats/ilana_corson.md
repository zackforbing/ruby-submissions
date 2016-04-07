Assessed By: Horace

Repo: https://github.com/icorson3/jungle_beats

Notes:

* Overall implementation is clean; using a mix of recursion and iteration
* got a lot of tests and they cover most of our cases pretty effectively
* looked at a couple of testing edge cases that got skipped -- mostly a) 0 (what happens when theres nothing) b) number of times iterations -- keep an eye on the possibility that we run out of nodes before we run out of numbers
* tidied up one iteration example (insert) -- usually for a structure like this when you need to work with multiple nodes in sequence its better to stop early and pull the next one when
you need it than to go past the first one (cuz then you have to go back for it)
* fulfills all requirements through i6


### 1. Functional Expectations

* 3: Application fulfills all base expectations

### 2. Test-Driven Development

* 3: Application is well tested but does not balance isolation and integration tests, using only the data necessary to test the functionality

### 3. Encapsulation / Breaking Logic into Components

* 3: Application effectively breaks logical components apart but breaks the principle of SRP

### 4. Fundamental Ruby & Style

* 3:  Application shows strong effort towards organization, content, and refactoring

### 5. Looping *or* Recursion

* 3: Application makes effective use of loop/recursion techniques
