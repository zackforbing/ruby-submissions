## Evaluation Process

Evaluator: Andrew

Notes:

* When checking out if you go back without paying, cart is empty and no other way to pay for gif. Maybe drop a payment option in the orders page.
* Some logic is leaking through in the views. Saw a formatted price, and a map for a collection dropdown box. An unnecessary variable in a path helper. Some alignment issues when items are retired. This issue is related to a conditional in the iteration of gifs.
* In controllers some room for POROS - but generally skinny and good code. Want to look into orders_controller update for the quantity variable


For the evaluation we'll work through the expectations above and look at the
following criteria:

### 1. Feature Completeness

* 3: All features defined in the assignment are correctly implemented

### 2. Views

* 3: Views make use of layout(s), partials and helpers, but some logic leaks through

### 3. Controllers

* 3: Controllers are generally well organized with three or fewer particularly ugly parts

### 4. Models

* 3: Models show an effort to push logic down the stack, but need more internal refactoring

### 5. Testing

* 3: Project has a running test suite that tests and multiple levels but fails to cover some features

### 6. Usability

* 3: Project is highly usable, but needs more polish before it'd be customer-ready

### 7. Workflow

* 4: Excellent use of branches, pull requests, and a project management tool.
