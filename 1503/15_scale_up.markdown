## Template - Student Name

__Repository:__

__Instructor:__


* __Production Deployment & Performance Monitoring__ (1-4)
* __Load Testing / User Scripting__ (1-4)
* __Database Load__ (1-4)
* __Optimization Techniques__ (1-4)
* __Features - Pagination__ yes/no

## Detailed Rubric

#### 1. Production Deployment and Performance Monitoring

* 4: Average response time below 100ms with 600+ RPM
* 3: Average response time below 200ms with 400+ RPM
* 2: Average resposne time below 400ms with 300+ RPM
* 1: Average response time above 400ms, or unable to handle 300 RPM

#### 2. Load Testing / User Scripting

* 4: Load testing script exercises all required endpoints and adds 2 or more of its own
* 3: Load testing script exercises all required endpoints
* 2: Load testing script misses 1-3 endpoints
* 1: Load testing misses many endpoints

Anonymous user browses loan requests
User browses pages of loan requests
User browses categories
User browses pages of categories
User views individual loan request
New user signs up as lender
New user signs up as borrower
New borrower creates loan request
Lender makes loan

#### 3. Database Load

DB has required number of records.

* 500,000+ "Item" records
* 200,000+ "User" records
* 30,000+ "Tenant" records (whichever entity provides the items-for-purchase within your app)
* 50,000+ "Order/Purchase" records
* 15+ Tag/Category records (each Item or similar object should have at least 1 category)
* Appropriate numbers of "associated records". So if each User has an associated address,
  then those records should be present in proportional numbers.

#### 4. Performance Optimization Techniques

* 4 - Application appropriately utilizes multiple caching techniques
  along with sophisticated query optimizations and combinations.
* 3 - Application uses a proficient combination of caching, query
  optimization, and code restructuring to achieve acceptable
  performance.
* 2 - Application includes some optimizations in the form of basic
  caching or query optimization, but fails to attack the problem from
  multiple angles.
* 1 - Application lacks creativity in optimizing performance.

#### 5. Additional Features
