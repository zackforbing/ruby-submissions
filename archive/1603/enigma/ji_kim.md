Assessed By: Horace

Repo: https://github.com/jkim55/enigma

Additional Feature: Character map extension

Notes:

* completed most of the base spec; some slight issues with cracking
* code is pretty straightforward and tidy for the most part
* some extraction of additional classes to handle specific jobs (like Key generation and offset generation)
* would like to keep seeing more of this -- especially as a means of extracting some of the repeated logic between
encryption and decryption
* testing is good -- sounds like we worked on some more intermediate unit tests to help us along the way but then removed
them for conciseness -- talked about how these are actually good and we should leave them next time


### 1. Overall Functionality

* 3: Application encrypts, decrypts, and cracks files as described

### 2. Fundamental Ruby & Style

* 3:  Application shows some effort toward organization but still has 6 or fewer long methods (> 8 lines) and needs some refactoring.

### 3. Test-Driven Development

* 3: Application uses tests to exercise core functionality, but has some gaps in coverage or leaves edge cases untested.

### 4. Breaking Logic into Components

* 3: Application has multiple components with defined responsibilities but there is some leaking of responsibilities
