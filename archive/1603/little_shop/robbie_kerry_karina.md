## Evaluation Process

Evaluator: Andrew

Notes:

* App broke on creation of new family. Looks like twillio. Will give time to fix to bring score up.

* One query in view. Nationalities.all. Refactor to controller. The use of partials and presenters cancel our the logic int he view for a score of 4. Happy to user attempts at using presenters.

* Using session hash for cart quantity - would prefer the supply to call quantity

* SupplyItem.find_family(id) should be SupplyItem.find(id).family => trying to write method that active record handle already.

* Donation controller still has iteration over supply items to crate donation items. Would like to see that refactored to an object that handles the completion of donations

* Creating supply_items within family model. We should refactor this to a poro or just somewhere other than a different model.

* Also, consider a stats object instead of pulling in data from multiple different models for statistics

* Highly suggest helper methods in test suite to make your life easier. Overall tests at multiple levels and multiple paths

### 1. Feature Completeness

* 3: All features defined in the assignment are correctly implemented

### 2. Views

* 4: Views show logical refactoring into layout(s), partials and helpers, with no logic present

### 3. Controllers

* 3: Controllers are generally well organized with three or fewer particularly ugly parts

### 4. Models

* 4: Models show excellent organization, refactoring, and appropriate use of Rails features

### 5. Testing

* 4: Project has a running test suite that exercises the application at multiple levels

### 6. Usability

* 4: Project is highly usable and ready to deploy to customers

### 7. Workflow

* 3: Good use of branches, pull requests, and a project-management tool.
