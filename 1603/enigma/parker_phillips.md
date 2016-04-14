Assessed By: Horace

Repo: https://github.com/excaelum/enigma

Additional Feature: Keywords

Notes:

* overall very successful project -- completed base features as well as supporting feature and an extension
* seem to be doing pretty well with testing workflow -- classes are well-tested especially from a verification / functionality perspective
* looked at a few spots where some subtle improvements in naming could help clarify intent of the code a bit
* main improvement that stands out to be made would be extracting and reusing the duplicated code between the encrypt and decrypt classes --
when we see stuff like this look for a way to pull the similar code out into a new class and pass in some parameter that allows it to customize between the 2 different approaches

### 1. Overall Functionality

* 4: Application follows the complete spec and one extension

### 2. Fundamental Ruby & Style

* 3:  Application shows some effort toward organization but still has 6 or fewer long methods (> 8 lines) and needs some refactoring.

### 3. Test-Driven Development

* 4: Application is broken into components which are well tested in both isolation and integration

### 4. Breaking Logic into Components

* 3: Application has multiple components with defined responsibilities but there is some leaking of responsibilities
