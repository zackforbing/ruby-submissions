Evaluator: Andrew

Students:

Notes:

* Make sure you include the rails flag with simpleCov if running in a rails project: `SimpleCov.start "rails"`. It dropped your coverage to 93.95%
* After inspecting the coverage/index.html output from simplecov - still have really good coverage. The only files not covered don't matter
* Great controller tests. Quantity and coverage is awesome. Really impressed.
* I'd encourage you not to use abbreviation for variable names. - https://beehollander.wordpress.com/2016/07/08/the-6-month-bug-and-why-i-will-never-abbreviate-variable-names/
* You have a left over test that is empty `it 'returns the date with most sales for an item by invoice date'`. Make sure you remove it or mark it pending
* Can tell you really drove controllers with TDD and it's awesome.

* Model tests lack some coverage. Really important to fully cover all unit level code. Most important layer to cover. Work to get this to 100%
* Model tests missing: Customer methods, scope in invoice, Item methods, all merchant methods besides own revenue, two transaction scopes.
* Overall lacking model tests. I understand there is a spec harness that covers these, but often there wont be. Having model/unit level tests are the most important
* In controllers - When we have something like `Customer.find(params[:id]).transactions` to return transactions, we could also write `Transaction.where(customer_id: params[:id])` The query returns the same thing, and it's my opinion the second is just a little more clear, but it is just an opinion and not something that's wrong. I just mention it to bring a different point of view.
* Single Merchant revenue controller has a conditional that can be refactored to the model. Just make an instance method that can be called to find revenue regardless of the date - make sure you pass through params and do that control flow within the model. Something like `Merchant.find(params[:id]).revenue(params)`
* For finding random - Your solution is valid, but there is another feature Rails 5 offers that I think is work noting. The ApplicationRecord file can be used to write new queries that can me inherited in any model. If you notice, all models inherit from ApplicationRecord, so you can write query methods inside this file that will be accessible to all models. For example:

```ruby
# you can call this random method on any active record object.
def self.random
  order("RANDOM()").take(1)
end
```

* Merchant model falls to ruby instead of active record for a few methods for a few methods - `merchant_paid_invoice_items`, `paid_invoice_items_by_date(invoice_date)`, `revenue_by_date`, `revenue`




## Project Rubric

**1. Completion**

* 3: Project completes most requirements but fails 3 (5 for individual project) or fewer spec harness tests.

### Technical Quality

**1. Test-Driven Development**

Please focus on Model/Unit tests moving forward.

* 4: Project demonstrates high test coverage (>90%) and tests at the controller and unit levels.

**2. Code Quality**

* 4: Project demonstrates exceptionally well factored code.

**3. API Design**

* 4: Project exemplifies API design idioms, with consistent and coherent response structures, serializers to format JSON data, and effective request format handling.

**4. Queries**

Good use of joins and some advanced ActiveRecord queries, but some Ruby `merchant_paid_invoice_items`, `paid_invoice_items_by_date(invoice_date)`, `revenue_by_date`, `revenue`

* 3: Project makes good use of ActiveRecord, but drops to ruby enumerables for some query methods.
