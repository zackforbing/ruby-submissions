Assesed By: Horace

Github repo: https://github.com/AnnaCW/mastermind

Notes:

* like that we have a very small "runner" file that just calls into the main (start menu) class
* like to see so many classes -- might think of different names or different ways some of the classes get divided up -- but having all these tools in place is the first step
* small points -- people would probably move the core of our logic / operations out of initialze and into some extra method (`play`, `run`, etc )
* camel case constant (i.e. class) names
* main structural thing I would want to look at is possibly re-arranging the relationship between `Play` and `End` classes so it's possible to transition from one to the other without
"nesting" directly -- ideally one "session" class at the top runs the show between various actions, without those interactions needing to know about one another
* ^ look for ways to flatten out a deep tree structure into something more manageable or linear
* don't make something an instance variable unless necessary
* guess checking process could probably be cleaned up with the right enumerable -- would be an interesting thing to come back to in 2 weeks and see if you have a new tool that fits this problem

### 1. Fundamental Ruby & Style

* 3:  Application shows some effort toward organization but still has 6 or fewer long methods (> 8 lines) and needs some refactoring.

### 2. Enumerable & Collections

* 3: Application demonstrates comfortable use of several Enumerable techniques and collections

### 3. REPL Interface and Game Functionality

* 3: Application's REPL is clear and pleasant to use and application fulfills base expectations from the project spec

### 4. Breaking Logic into Components

* 3: Application consistently breaks concepts into logical methods to encapsulate functionality.
