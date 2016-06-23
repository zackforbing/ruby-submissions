## Evaluation Process

Evaluator:

Notes:

* App crashes when trying to send email message. Fix error before final grade.

* Query in partial to locate orders by status. Already had passed through collection by status from controller. Do queries in controller or pass logic to other poro

* Think about class methods (Order.complete  Order.paid) in models to refactor from controllers. Then you can have instance variable in your views that reflect the query. The benefit is clarity and you declare what you want instead of asking for it.

* No inline styling. Bring that to you css file.

For the evaluation we'll work through the expectations above and look at the
following criteria:

### 1. Feature Completeness

* 4: All features are correctly implemented along with two extensions
* 3: All features defined in the assignment are correctly implemented

### 2. Views

* 3: Views make use of layout(s), partials and helpers, but some logic leaks through

### 3. Controllers

* 4: Controllers show significant effort to push logic down the stack

### 4. Models

* 3: Models show an effort to push logic down the stack, but need more internal refactoring

### 5. Testing

* 4: Project has a running test suite that exercises the application at multiple levels

### 6. Usability

* 3: Project is highly usable, but needs more polish before it'd be customer-ready

### 7. Workflow

* 3: Good use of branches, pull requests, and a project-management tool.
