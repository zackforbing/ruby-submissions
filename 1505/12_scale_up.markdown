## Scale Up Project Evaluations

### Template

__Instructor:__

__Repo:__

__Notes:__

1. __Production Deployment and Performance Monitoring:__ (1 - 4)
2. __Load Testing / User Scripting:__ (1 - 4)
3. __Database Load:__ (1 - 4)
4. __Performance Optimization Techniques:__ (1 - 4)
5. __Additional Features:__ (1 - 4)

### Dave Maurer

__Instructor:__ Mike

__Repo:__ http://github.com/davemaurer/keevah

__Notes:__

* 500ms at about 100 rpm
* Categories only used includes, could use pagination and caching.
* load script only really achieves sub 100 rpm.
* understanding of the various techniques on how to improve performance has been achieved,
just needs to combine them to bring performance up, or time down.


1. __Production Deployment and Performance Monitoring:__ (1 - 4): 2+
2. __Load Testing / User Scripting:__ (1 - 4): 3
3. __Database Load:__ (1 - 4) 3
4. __Performance Optimization Techniques:__ (1 - 4) 2
5. __Additional Features:__ (1 - 4) 3

### Jamie Kawahara

__Instructor:__ Mike Dao

__Repo:__ http://github.com/androidgrl/scaleup

__Notes:__

* At 375 RPM, app was running at 175ms.
* load script hits all endpoints with some extra ones.
* caching of loan_requests done in controller
* caching in rendered partial
* nice use of rescue in the load script

1. __Production Deployment and Performance Monitoring:__ (1 - 4) 3
2. __Load Testing / User Scripting:__ (1 - 4): 4
3. __Database Load:__ (1 - 4): 3
4. __Performance Optimization Techniques:__ (1 - 4): 3
5. __Additional Features:__ (1 - 4): 3


### Erik Butcher

__Instructor:__ Mike

__Repo:__ http://github.com/with-a-k/scale-up

__Notes:__

* Load script errors
* at 100 RPM, 175 ms.
* at 200 RPM, 300 ms.
* at 230, 350ms
* at 400, 400ms
* There is an implementation of pagination and one database query optimization in
related projects.
* out of base functionality, only pagination was implemented, not image URL or
Custom pages.

1. __Production Deployment and Performance Monitoring:__ (1 - 4): 1
2. __Load Testing / User Scripting:__ (1 - 4): 3
3. __Database Load:__ (1 - 4): 3
4. __Performance Optimization Techniques:__ (1 - 4): 2-
5. __Additional Features:__ (1 - 4): 1

### David Shim

__Instructor:__ Mike

__Repo:__ http://github.com/dsshim/keevah

__Notes:__

* at almost 600 rpm, 95 ms.
* load script and one extra endpoint
* Fixed related projects.
* Cached categories.
* Cached all static pages.
* There were some additional "optimizations" that actually slowed performance
and then removed.

1. __Production Deployment and Performance Monitoring:__ (1 - 4): 4
2. __Load Testing / User Scripting:__ (1 - 4): 3+
3. __Database Load:__ (1 - 4): 3
4. __Performance Optimization Techniques:__ (1 - 4): 4
5. __Additional Features:__ (1 - 4): 4


### Alex Tideman

__Instructor:__Mike

__Repo:__ http://github.com/alex-tideman/keevah

__Notes:__

* 225ms at 300 rpm
* related projects was cached
* good use of database queries
* could have cached database counts, and looked for opportunities to create
and cache static pages


1. __Production Deployment and Performance Monitoring:__ (1 - 4) 3
2. __Load Testing / User Scripting:__ (1 - 4): 3
3. __Database Load:__ (1 - 4): 3
4. __Performance Optimization Techniques:__ (1 - 4): 3
5. __Additional Features:__ (1 - 4) 4
