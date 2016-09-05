Assessed By: Horace

Repo: https://github.com/gkhalsa/black_thursday

Notes:

* Sales engine basic setup is good; maybe could have used some enumeration over the data hash to avoid some of the long argument lists
* Don't use memoize if you dont need it (esp. in  initialize methods)
* Collection organization is good within the repos
* Don't forget to utilize finder methods that were already defined instead of re-implementing them in multiple places
* Really like extraction of analytics work into multiple dedicated classes for each one
* Even could have gone farther in this direction by pushing some of the simpler, "1st-pass" methods into the respective Record classes (e.g. Merchant#average_item_price)
* Appreciate the additional features -- glad to see yall are having fun with some programming
* Tests are good -- got a lot of them, they cover the high level functionality; would love to see using at least fixtures (slimmer data set of some sort) or even some more hand-written simple ruby data
* Esp. looking at the anlytics test, it covers the top-level interface; would love to see it covering more of the "under the hood" intermediate steps or other helper methods


### 1. Functional Expectations

* 4: Application implements iterations 0, 1, 2, 3, (4 or 5), and features of your own design

### 2. Test-Driven Development

* 3: Application is well tested but does not balance isolation and integration tests, using only the data necessary to test the functionality

### 3. Encapsulation / Breaking Logic into Components

* 3: Application effectively breaks logical components apart but breaks the principle of SRP

### 4. Fundamental Ruby & Style

* 3:  Application shows strong effort towards organization, content, and refactoring

### 5. Enumerable & Collections

* 4: Application consistently makes use of the best-choice Enumerable methods

### 6. Code Sanitation

* 4: Zero complaints
