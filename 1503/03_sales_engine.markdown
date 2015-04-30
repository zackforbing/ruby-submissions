### Dmitry and Drew

Evaluated by Josh Cheek and Sam Alghanmi

1. Functional Expectations
  * Application fulfills all base expectations as tested by the spec harness
  * Score: 3
2. Test-Driven Development
  * Score: 3
  * Spec harness passes
  * Your tests pass, a good number of them
  * 95% coverage
  * Tests are mostly integration, would be better to expand on
    the old style of declaring the Customer that the CustomerRepository has,
    which would also improve the design.
3. Encapsulation / Breaking Logic into Components
  * Score: 3
  * I can initialize repos without having to deal with CSVS
  * The repos can't currently be used without telling it to load the data from CSVs
4. Fundamental Ruby & Style
  * Score: 3
  * Merchant revenue could be easily refactored, would improve test coverage, reduce duplication
  * On the whole, looked pretty good
5. Enumerable & Collections
  * Effective use of map, flat_map, find_all, group_by, etc..
  * Score: 4
6. Code Sanitation
  * Zero complaints
  * Score: 4







### Sally and Justin

Evaluated by Josh Cheek and Sam Alghanmi

1. Functional Expectations
  * Score: 3
  * Application fulfills all base expectations as tested by the spec harness
2. Test-Driven Development
  * Score: 3
  * Spec harness passes, 22 seconds (new record?)
  * Their test suite passes
  * Super quick! (ty!)
  * Tests don't assert information useful enough to identify several errors we found
3. Encapsulation / Breaking Logic into Components
  * Score: 3
  * No real issues, some small refactorings could lead to nice realizations,
    like we looked at (ultimately, probably leading to a Repository superclass)
4. Fundamental Ruby & Style
  * Score: 4
  * Thinks look fine to me :D
5. Enumerable & Collections
  * Score: 4
  * Effective use of select, detect, map, etc
  * Nice use of `group_by` to allow repos to key their data off of an association id,
    reducing time complexity of business intelligence algorithms
6. Code Sanitation
  * Zero complaints
  * Score: 4


### Josh Cass & Erik Butcher

Evaluated by Josh Cheek and Sam Alghanmi

1. Functional Expectations
  * Score 4
  * 3 extensions
  * Also runs delightfully fast!
2. Test-Driven Development
  * Score: 4
  * Got a new record for Spec Harness time? 4.35!
  * Spec harness passes
  * Test suite passes, 114 tests, 131 assertions
  * Unit tests are pretty good
3. Encapsulation / Breaking Logic into Components
  * Score: 3
4. Fundamental Ruby & Style
  * Score: 3
  * Mildly strange syntax here and there, try to make it clear which pieces are where (ie the `self`)
  * Make a point of considering the names you use as they dictate how you think about those objects.
    eg `id` is singular, so a collection would be `ids`, but since its a hash, might add additional context.
5. Enumerable & Collections
  * Score: 4
  * Mostly effective iterators, Nice use of hashes perform calculations once and then look up the results,
    reducing time complexity and allowing for delightful test speeds
6. Code Sanitation
  * Zero complaints
  * Score: 4
