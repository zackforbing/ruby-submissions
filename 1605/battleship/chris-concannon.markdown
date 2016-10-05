Assessed By: Horace

Repo: https://github.com/concach/battleship

Notes:

* Managed the complexities of the problem very effectively to produce a game that works smoothly and reliably
* Have a couple of "god" classes that are clearly consuming large chunks of the application logic
* Testing is good at the lower layers of the application tree but falls off significantly at the higher layers
* Talked about how the program probably needs a firmer boundary between any user input and (especially) the Gameplay
class
* If you like this "bottom-up" design approach, an interesting technique could be to focus on pushing the program as far
along as possible using Testing exclusively, then toward the end add in a think User I/O layer that connects to this code
* Testing is the biggest thing I'd like to keep seeing more of in the remaining projects; i think this will also help sort out
some of the "god class" syndrome as well

Scores:

### 1. Fundamental Ruby & Style

* 3:  Application shows strong effort towards organization, content, and refactoring

### 2. Enumerable & Collections

* 3: Application demonstrates comfortable use of several Enumerable techniques

### 3. Test-Driven Development

* 2: Application makes some use of tests, but the coverage is insufficient

### 4. REPL Interface

* 3: Application's REPL is clear and pleasant to use

### 5. Breaking Logic into Components

* 3: Application effectively breaks logical components apart with clear intent and usage
