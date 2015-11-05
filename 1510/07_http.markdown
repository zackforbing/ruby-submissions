## Template

Group:

Assessed By:

Github:

Notes:

Scores:

1. Overall Functionality

4: Application implements all five iterations and at least one extension
3: Application implements four iterations
2: Application implements three iteration
1: Application implements two or fewer iterations

2. Fundamental Ruby & Style

4: Application demonstrates excellent knowledge of Ruby syntax, style, and refactoring
3: Application shows some effort toward organization but still has 6 or fewer long methods (> 8 lines) and needs some refactoring.
2: Application runs but the code has many long methods (>8 lines) and needs significant refactoring
1: Application generates syntax error or crashes during execution

3. Test-Driven Development

4: Application is broken into components which are well tested in both isolation and integration
3: Application uses tests to exercise core functionality and some edge cases, but fails to break out component objects/tests.
2: Application uses tests to exercise core functionality but leaves many common edge cases untested.
1: Application does not demonstrate strong use of TDD

4. Breaking Logic into Components

4: Application effectively breaks logical components apart with clear intent and usage
3: Application has multiple components with defined responsibilities but there is some leaking of responsibilities
2: Application has some logical components but divisions of responsibility are inconsistent or unclear and/or there is a "God" object taking too much responsibility
1: Application logic shows poor decomposition with too much logic mashed together

## Lenny & Alex

Group: Lenny & Alex

Assessed By: Horace

Github: https://github.com/Salvi6God/http_yeah_you_know_me

Notes:

* Some initial progress on a procedural solution the problem
* Struggled to make layered progress on problem components, largely
due to difficulties in applying dev processes and techniques
* Struggled with outpacing feedback - no tests to provide feedback,
seems to have led to difficulty understanding the progress that had
been made thus far and the scope of the problem

Scores:

* Overall Functionality 1: Application implements two or fewer iterations
* Fundamental Ruby & Style 2: Application runs but the code has many long methods (>8 lines) and needs significant refactoring
* Test-Driven Development 1: Application does not demonstrate strong use of TDD
* Breaking Logic into Components 1: Application logic shows poor decomposition with too much logic mashed together

## Brant & Beth

Group: Beth & Brant

Assessed By: Horace

Github: https://github.com/brantwellman/Turing-HTTP-Yeah-You-Know-Me

Notes:

* Good organization overall at the high level
* Some methods could use some love in terms of breaking apart
the logic and steps
* Test coverage is thorough and does a good job of dealing with
clear inputs and outputs
* Some portions of the project are lacking in tests and it very clearly
shows in the structure of the corresponding code

Scores:

1. Overall Functionality

3: Application implements four iterations

2. Fundamental Ruby & Style

3: Application shows some effort toward organization but still has 6 or fewer long methods (> 8 lines) and needs some refactoring.

3. Test-Driven Development

3: Application uses tests to exercise core functionality and some edge cases, but fails to break out component objects/tests.

4. Breaking Logic into Components

3: Application has multiple components with defined responsibilities but there is some leaking of responsibilities

## JP & Steve O

Group: JP & Steve O

Assessed By: Horace

Github: https://github.com/jwperry/5project_repo

Notes:

* Good functionality hitting up to I5
* Testing is good; using relatively clear inputs and outputs
to test the logic in isolation of the HTTP server
* Don't love the rigid approach to parsing body vs. headers;
leads to some weird behavior if you use different clients or browsers
* Also would have simplified test data if we were able to take a different
approach to parsing the inputs
* Overall abstraction of Server class to handle responsibilities is good,
but there are other tasks that could have been split out of it -- esp.
Path/Action identification; Response generation and formatting; actual
action performance
* Testing covers main paths and usage pretty well but didn't turn up some
prominent edge-cases

Scores:

* Overall Functionality 3: Application implements four iterations
* Fundamental Ruby & Style 3: Application shows some effort toward organization but still has 6 or fewer long methods (> 8 lines) and needs some refactoring.
* Test-Driven Development 3: Application uses tests to exercise core functionality and some edge cases, but fails to break out component objects/tests.
* Breaking Logic into Components 3: Application has multiple components with defined responsibilities but there is some leaking of responsibilities

## Penney

Group: Penny

Assessed By: Horace

Github: https://github.com/PenneyGadget/http_yeah_you_know_me

Notes:

* Solid functionality through I3
* Starting on a good attempt toward class extraction and
refactoring, but the extraction is not totally complete so
we end up with duplicated responsibilities between various classes
* More diagramming / sketching / dependency tracking / state examination
(what classes rely on each other; what instance variables are being tracked in
each object)
* Testing is pretty lacking -- might have been helpful to focus on stripping down
overall functionality into cleaner inputs/outputs that could be tested more
granularly
* Kudos being alone for the project and struggling through the many unknowns

Scores:

* Overall Functionality 2: Application implements three iteration
* Fundamental Ruby & Style 3: Application shows some effort toward organization but still has 6 or fewer long methods (> 8 lines) and needs some refactoring.
* Test-Driven Development 1: Application does not demonstrate strong use of TDD
* Breaking Logic into Components 2: Application has some logical components but divisions of responsibility are inconsistent or unclear and/or there is a "God" object taking too much responsibility

## Steve and Emily

Group: Steve and Emily

Assessed By: Horace

Github: https://github.com/emblou2/http-yeah-you-know-me

Notes:

* Overall structure is heading in a good direction - parsing request info
into semantically named keys and values of a hash is useful
* Some leakage of non-parsing responsibilities into the parser object,
so be attentive to that.
* Think especially about names and responsibilities of objects with respect
to the methods they are performing -- do they actually fit
* Testing is good on the things it covers but overall lacking in quantity
* Completion is solid through I3 but didn't get into game application

Scores:

1. Overall Functionality

2: Application implements three iteration

2. Fundamental Ruby & Style

3: Application shows some effort toward organization but still has 6 or fewer long methods (> 8 lines) and needs some refactoring.

3. Test-Driven Development

2: Application uses tests to exercise core functionality but leaves many common edge cases untested.

4. Breaking Logic into Components

3: Application has multiple components with defined responsibilities but there is some leaking of responsibilities
