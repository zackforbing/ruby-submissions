Assessed By: Horace

Repo: https://github.com/twhitinger/battleship

Notes:

* somewhat miraculously made a working game out of some pretty gnarly code
* there are a lot of small things adding up to make the code especially complex and hard to read,
but the general theme is that we just need more **abstractions** -- More classes, more methods, and
to think a little more carefully about the interfaces between those things in such a way that we can make them
fit together more nicely
* also need to lean a little more heavily on the classes and methods that he *have* implemented -- dont forget that
you have some method and end up re-implementing it in another class
* we have some tests but most of them are fairly tautological -- the structure of the code and the lack of clean
interfaces and connections therein makes testing this basically impossible
* Good: Logic, patience, diligence, attention to detail
* Bad: Structure, organization, and design
* "move slow to go fast"

Scores:

### 1. Fundamental Ruby & Style

* 2:  Application runs but the code has many long methods (>8 lines) and needs significant refactoring

### 2. Enumerable & Collections

* 3: Application demonstrates comfortable use of several Enumerable techniques

### 3. Test-Driven Development

* 2: Application makes some use of tests, but the coverage is insufficient

### 4. REPL Interface

* 3: Application's REPL is clear and pleasant to use

### 5. Breaking Logic into Components

* 2: Application shows some effort to break logic into components, but the divisions are inconsistent or unclear
