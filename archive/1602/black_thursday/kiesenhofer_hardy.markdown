Assessed By: Horace

Repo: https://github.com/claudia108/black_thursday

Notes:

* Overall pretty well organized and clean
* Looked at a handful of naming questions; talked about separating out a complicated iterative process into a "pipeline" of multiple steps -- even if this is longer it's often easier to reason about
* Gives potential for "pluggability" of individual steps -- realizing i can improve upon one step in the process without affecting all the others
* Biggest takeaway from the analysis perspective is to simplify code by leveraging lower level objects more effectively -- i can sometimes push the first steps onto individual records and then only have to be responsible for the higher level analysis myself
* 1 - reduces amount of code in the 1 big object
* 2 - helps avoid writing repetitive finder logic -- find x by x over and over in different spots
* Talked about procs for probably too long

### 1. Functional Expectations

* 3: Application implements iterations 0, 1, 2, 3, and either 4 or 5

### 2. Test-Driven Development

* 3: Application is well tested but does not balance isolation and integration tests, using only the data necessary to test the functionality

### 3. Encapsulation / Breaking Logic into Components

* 3: Application effectively breaks logical components apart but breaks the principle of SRP

### 4. Fundamental Ruby & Style

* 3:  Application shows strong effort towards organization, content, and refactoring

### 5. Enumerable & Collections

* 4: Application consistently makes use of the best-choice Enumerable methods

### 6. Code Sanitation

* 3: Five or fewer complaints
