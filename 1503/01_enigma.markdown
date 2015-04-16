### Rick Bacci

* Project GitHub URL: https://github.com/RickBacci/enigma
* Fundamental Ruby:
* TDD:
* File I/O:
* Components:
* Notes:

### Erik Butcher

* Project GitHub URL: https://github.com/with-a-k/enigma
* Fundamental Ruby:
* TDD:
* File I/O:
* Components:
* Notes:

### Josh Cass

* Project GitHub URL: https://github.com/joshcass/enigma
* Fundamental Ruby:
* TDD:
* File I/O:
* Components:
* Notes:

### Rob Cornell

* Project GitHub URL: https://github.com/RMCornell/enigma_1.git
* Rubric: http://tutorials.jumpstartlab.com/projects/enigma.html
* Fundamental Ruby & Style
  * Naming of encryption and decryption is the same (Rotor), thus they override each other's methods
  * Score: 3
* Test-Driven Development
  * Missing tests on the code that has the design issues.
  * Score: 2
* File I/O
  * Score: 3
* Breaking Logic into Components
  * Some duplication in encryption / decryption that can be pulled into a method
  * Encryption and decryption are similar enough that there is likely a missing abstraction (prob a class)
  * Side-effecty things (knowledge of ARGV, file reading/writing) need to be pulled out, so that the library code can be used independently (eg for tests)
  * Score: 2
* Notes:
  * Rewrote it the night before in 4 hours

### Andrew Fink

* Project GitHub URL:
* Fundamental Ruby:
* TDD:
* File I/O:
* Components:
* Notes:

### Vanessa Gomez

* Project GitHub URL: https://github.com/vanegomez/enigma.git
* Fundamental Ruby:
* TDD:
* File I/O:
* Components:
* Notes:

### Brett Grigsby

* Project GitHub URL: https://github.com/brettgrigsby/projects/tree/master/enigma
* Rubric: http://tutorials.jumpstartlab.com/projects/enigma.html
* Fundamental Ruby & Style
  * No issues
  * Score: 3
* Test-Driven Development
  * Some tests don't run
  * Can't run all tests at once
  * Score: 3
* File I/O
  * Don't assume the files are in lib
  * Liked the responsibilities for these things were placed (above everything else)
  * Doesn't prompt when overriding files
  * Score 3
* Breaking Logic into Components
  * Pulled dependencies to the highest level (encrypt.rb / decrypt.rb)
  * Common responsibilities of encrypting and decrypting are pulled into Rotator (that's good ;)
  * Score: 4
* Notes:

### Whitney Hiemstra

* Project GitHub URL: https://github.com/whiemstra/enigma.git
* Fundamental Ruby:
* TDD:
* File I/O:
* Components:
* Notes:

### Justin Holmes

* Project GitHub URL:https://github.com/Justin-Holmes/enigma
* Fundamental Ruby:
* TDD:
* File I/O:
* Components:
* Notes:

### Eugene Khanutin

* Project GitHub URL:
* Fundamental Ruby:
* TDD:
* File I/O:
* Components:
* Notes:

### Lev Kravinsky

* Project GitHub URL: https://github.com/kravinskylev/enigmafinal
* Rubric: http://tutorials.jumpstartlab.com/projects/enigma.html
* Fundamental Ruby & Style
  * probably name files with `snake_case` instead of `CamelCase`
  * name the file after the constant it contains, e.g. rubix.rb would contain Rubix, encrypt.rb would contain Encrypt
  * Files that are empty
  * Don't put messages inside of lib
  * Score: 3
* Test-Driven Development
  * Testing "lip service"
  * Score: 1
* File I/O
  * Doesn't prompt on overwriting file
  * Encryption doesn't print the key
  * Decryption doesn't accept a date
  * Score: 2
* Breaking Logic into Components
  * I like that "difficult dependencies" ie working with `ARGV` and reading/writing files, printing/prompting is pulled out to the highest level of the library and reading/writing files is pulled out to the highest level of the library
  * Find the commonality between encrypt and decrypt, figure out how to join those together to reduce the duplication. Partly this is already done, but you can take it further.
  * Score: 4
* Notes:

### Margarett Ly

* Project GitHub URL:
* Fundamental Ruby:
* TDD:
* File I/O:
* Components:
* Notes:

### Sally MacNicholas

* Project GitHub URL: https://github.com/sallymacnicholas/enigma.git
* Fundamental Ruby:
* TDD:
* File I/O:
* Components:
* Notes:

### Dave Maurer

* Project GitHub URL:
* Fundamental Ruby:
* TDD:
* File I/O:
* Components:
* Notes:

### Michael Merrill

* Project GitHub URL:
* Fundamental Ruby:
* TDD:
* File I/O:
* Components:
* Notes:

### Morgan Miller

* Project GitHub URL: https://github.com/morganmiller/enigma
* Fundamental Ruby:
* TDD:
* File I/O:
* Components:
* Notes:

### Drew Reynolds

* Project GitHub URL: https://github.com/NYDrewReynolds/my_enigma
* Rubric: http://tutorials.jumpstartlab.com/projects/enigma.html
* Fundamental Ruby & Style
  * Watch indentation
  * Score: 3
* Test-Driven Development
  * Score: 3
* File I/O
  * Score: 4
* Breaking Logic into Components
  * Score: 3.5

### Max Tedford

* Project GitHub URL: https://github.com/maxtedford/enigma
* Fundamental Ruby:
* TDD:
* File I/O:
* Components:
* Notes:

### Dmitry Vizersky

* Project GitHub URL: https://github.com/Dmitry1007/enigma_reloaded
* Fundamental Ruby:
* TDD:
* File I/O:
* Components:
* Notes:

### Chelsea Worrel

* Project GitHub URL:https://github.com/chelseaworrel/enigma.git
* Rubric: http://tutorials.jumpstartlab.com/projects/enigma.html
* Fundamental Ruby & Style
  * Watch indentation
  * Generally nice
  * Use private methods to protect code from changes
  * Score: 3
* Test-Driven Development
  * Good keeping the hard deps up at the highest level
  * Score: 4
* File I/O
  * Doesn't prompt
  * Score: 3
* Breaking Logic into Components
  * Score: 3.5
