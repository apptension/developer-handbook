Backend Developer
=================

Company best practices
----------------------

### [Security](/Technical%20Stack/Mobile%20Developer/Company%20best%20practices.md#security)

#### [Keeper Security](/Technical%20Stack/Mobile%20Developer/Company%20best%20practices.md#keeper-security)

*   [ ] You know how to share secret values with other employees. [:books:](https://docs.keeper.io/user-guides/)

#### [aws-vault](/Technical%20Stack/Mobile%20Developer/Company%20best%20practices.md#aws-vault)

*   [ ] You know how to use the command line to switch between users

#### [Onetimesecret](/Technical%20Stack/Mobile%20Developer/Company%20best%20practices.md#onetimesecret)

*   [ ] You know how to share secret values externally [:books:](https://support.painchek.com/hc/en-us/articles/360038504674-How-to-use-One-Time-Secret)

### [Git](/Technical%20Stack/Mobile%20Developer/Company%20best%20practices.md#git)

*   [ ] You create pull requests with proper name and description [:books:](https://medium.com/@hugooodias/the-anatomy-of-a-perfect-pull-request-567382bb6067)
*   [ ] You squash merge your pull requests [:books:](https://blog.pairworking.com/why-you-should-care-about-squash-and-merge-in-git-675856bf66b0)
*   [ ] You understand the pros and cons of git rebase vs git merge [:books:](https://www.atlassian.com/git/tutorials/merging-vs-rebasing)
*   [ ] You name your commits properly [:books:](https://chris.beams.io/posts/git-commit/)
*   [ ] You review PRs carefully and leave your comments [:books:](https://www.pullrequest.com/blog/what-belongs-in-an-effective-code-review-checklist/)
*   [ ] You know how to configure rules in a repository for merging to specific branches (master, develop)
*   [ ] You add proper label in pull requests
*   [ ] You create your branches under the proper folder (feature, fix, hotfix)

#### [GitHub](/Technical%20Stack/Mobile%20Developer/Company%20best%20practices.md#git-hub)

*   [ ] You know how to create and reference issues
*   [ ] You know how to verify when a build check failed
*   [ ] You know how to create GitHub Wiki pages

#### [Bitbucket](/Technical%20Stack/Mobile%20Developer/Company%20best%20practices.md#bitbucket)

*   [ ] You know how to verify when a build check failed
*   [ ] You know how to reference a Jira ticket in your commit

### [Communication](/Technical%20Stack/Mobile%20Developer/Company%20best%20practices.md#communication)

#### [Slack](/Technical%20Stack/Mobile%20Developer/Company%20best%20practices.md#slack)

*   [ ] You use Slack statuses in line with company policy (remote working, vacationing, in a meeting, etc)
*   [ ] You know how to create groups and channels

#### [Confluence](/Technical%20Stack/Mobile%20Developer/Company%20best%20practices.md#confluence)

*   [ ] You know how to create Confluence pages

#### [Small Improvements](/Technical%20Stack/Mobile%20Developer/Company%20best%20practices.md#small-improvements)

*   [ ] You know how to give praise and add talk topics to a 1:1 meeting
*   [ ] You know how to create goals and mark them as complete

#### [Jira](/Technical%20Stack/Mobile%20Developer/Company%20best%20practices.md#jira)

*   [ ] You know how to create tickets and write comments

#### [Email](/Technical%20Stack/Mobile%20Developer/Company%20best%20practices.md#email)

*   [ ] You can configure local email client
*   [ ] You can configure email signatures

Python
------

### [Frameworks](/Technical%20Stack/Backend%20Developer/Python.md#frameworks)

#### [Django](/Technical%20Stack/Backend%20Developer/Python.md#django)

##### [django-fsm](/Technical%20Stack/Backend%20Developer/Python.md#django-fsm)

*   [ ] You can create State Machine with simple transitions [:books:](https://hashedin.com/blog/a-guide-to-managing-finite-state-machine-using-django-fsm/)
*   [ ] You know how to listen for state transitions

###### [django-fsm-log](/Technical%20Stack/Backend%20Developer/Python.md#django-fsm-log)

*   [ ] You know how to use current user context in message log

##### [django-cacheops](/Technical%20Stack/Backend%20Developer/Python.md#django-cacheops)

*   [ ] You know how to configure defaults for models [:books:](https://dizballanze.com/django-project-optimization-part-3/)
*   [ ] You know how to disable caching for specific query

##### [django-notifications-hq](/Technical%20Stack/Backend%20Developer/Python.md#django-notifications-hq)

*   [ ] You know how to create a notification

##### [django-modeltranslation](/Technical%20Stack/Backend%20Developer/Python.md#django-modeltranslation)

*   [ ] Know how to translate Django models fields
*   [ ] You know how to setup fallback language

##### [django-hashid-field](/Technical%20Stack/Backend%20Developer/Python.md#django-hashid-field)

*   [ ] You have to configure salt and length of the hash
*   [ ] You know how to use it as a PK

##### [django-environ](/Technical%20Stack/Backend%20Developer/Python.md#django-environ)

*   [ ] You know how to define defaults
*   [ ] How to cast variables, including lists
*   [ ] You can use helpers like db for connection strings
*   [ ] You understand 12 factor app concept

##### [django-reversion](/Technical%20Stack/Backend%20Developer/Python.md#django-reversion)

*   [ ] How to declare a model with versioned history

##### [django-inline-actions](/Technical%20Stack/Backend%20Developer/Python.md#django-inline-actions)

*   [ ] You are able to add your own action in Django admin panel
*   [ ] You know how to set a custom name for an action
*   [ ] You can decide when it's appropriate library, contrary to your own implementation

##### [Django Enumeration types](/Technical%20Stack/Backend%20Developer/Python.md#django-enumeration-types)

*   [ ] You know how to declare a type

##### [Custom User model](/Technical%20Stack/Backend%20Developer/Python.md#custom-user-model)

*   [ ] You understand pitfalls of not doing so
*   [ ] You can define necessary manager class

#### [Flask](/Technical%20Stack/Backend%20Developer/Python.md#flask)

*   [ ] Define routes with http verbs
*   [ ] How to setup an app config
*   [ ] Use with storage, using DB of choice
*   [ ] How to response with json and use http code constants

#### [django-filter](/Technical%20Stack/Backend%20Developer/Python.md#django-filter)

*   [ ] You can create full text search query
*   [ ] You know how to use ordering query
*   [ ] You can use it with DRF Generic View
*   [ ] You know how to create custom queryset for a filter

#### [Serverless Framework](/Technical%20Stack/Backend%20Developer/Python.md#serverless-framework)

*   [ ] You can create simple HTTP endpoint using API gateway
*   [ ] You know plugins to handle local development like serverless offline
*   [ ] Configure more robust triggers like SQS events
*   [ ] You know how to use WSGI based framework

#### [Zappa](/Technical%20Stack/Backend%20Developer/Python.md#zappa)

*   [ ] You know how to scaffold a Django app

#### [FastAPI](/Technical%20Stack/Backend%20Developer/Python.md#fast-api)

*   [ ] You know how to create routing with query params
*   [ ] You can query DB using one of asynchronous libraries
*   [ ] You know how to use model in response
*   [ ] You can create server side events view
*   [ ] You know how to use <code>Depends</code>

### [Utils](/Technical%20Stack/Backend%20Developer/Python.md#utils)

#### [pydantic](/Technical%20Stack/Backend%20Developer/Python.md#pydantic)

*   [ ] You know how to declare a model
*   [ ] You can identify proper field types to model

#### [boto3](/Technical%20Stack/Backend%20Developer/Python.md#boto3)

*   [ ] You know how to use resources
*   [ ] You know how credentials are used, along with region

#### [django-whitenoise](/Technical%20Stack/Backend%20Developer/Python.md#django-whitenoise)

*   [ ] Know how to setup static files served by a middleware

#### [WeasyPrint](/Technical%20Stack/Backend%20Developer/Python.md#weasy-print)

*   [ ] You are able to render a PDF

### [ORM](/Technical%20Stack/Backend%20Developer/Python.md#orm)

#### [Django ORM](/Technical%20Stack/Backend%20Developer/Python.md#django-orm)

*   [ ] You are able to create Models
*   [ ] You used proxy model
*   [ ] You know how to chain queries using custom Manager

#### [Sequelize](/Technical%20Stack/Backend%20Developer/Python.md#sequelize)

*   [ ] You can create Model
*   [ ] You know how to create virtual fields

#### [sqlalchemy](/Technical%20Stack/Backend%20Developer/Python.md#sqlalchemy)

*   [ ] You know how to configure a connection
*   [ ] You can setup/create migrations

#### [pynamodb](/Technical%20Stack/Backend%20Developer/Python.md#pynamodb)

*   [ ] You know how to create a model
*   [ ] You know how to fetch by a hash or scan by props
*   [ ] You know how to do an upsert opearation

### [Task Queues](/Technical%20Stack/Backend%20Developer/Python.md#task-queues)

#### [Celery](/Technical%20Stack/Backend%20Developer/Python.md#celery)

*   [ ] You are able to create a task
*   [ ] You can create multiple queues
*   [ ] You can configure a broker
*   [ ] You know how to use flower
*   [ ] You can create own Task classes to extend functionality
*   [ ] You know how does sofy and hard limit works

### [Template engines](/Technical%20Stack/Backend%20Developer/Python.md#template-engines)

#### [Jinja](/Technical%20Stack/Backend%20Developer/Python.md#jinja)

*   [ ] You know how to use it to render templates

#### [pystashe](/Technical%20Stack/Backend%20Developer/Python.md#pystashe)

*   [ ] You are able to render a template

Testing
-------

### [Python](/Technical%20Stack/Backend%20Developer/Testing.md#python)

#### [pytest](/Technical%20Stack/Backend%20Developer/Testing.md#pytest)

*   [ ] Can setup a test case with multiple paths using fixtures
*   [ ] You are able to define custom fixtures
*   [ ] You know how to add plugins
*   [ ] You know fixture scopes

#### [factory_boy](/Technical%20Stack/Backend%20Developer/Testing.md#factory_boy)

*   [ ] You know how to create a factory
*   [ ] You know how to use traits
*   [ ] You know how to create related factories

#### [faker](/Technical%20Stack/Backend%20Developer/Testing.md#faker)

*   [ ] You know how to generate faked values using built-in providers

### [Node.js](/Technical%20Stack/Backend%20Developer/Testing.md#node.js)

#### [Jest](/Technical%20Stack/Backend%20Developer/Testing.md#jest)

*   [ ] You know how to configure a test env
*   [ ] You can describe a test using assertions

### [Performance Testing](/Technical%20Stack/Backend%20Developer/Testing.md#performance-testing)

#### [Artillery.io](/Technical%20Stack/Backend%20Developer/Testing.md#artillery.io)

*   [ ] You can create scenarios
*   [ ] You know how to generate fake data
*   [ ] You know how to pass variables between phases

Date & Time
-----------

### [Python](/Technical%20Stack/Backend%20Developer/Date%20&%20Time.md#python)

#### [python-dateutil](/Technical%20Stack/Backend%20Developer/Date%20&%20Time.md#python-dateutil)

*   [ ] You are able to create relative datetime objects

#### [pytz](/Technical%20Stack/Backend%20Developer/Date%20&%20Time.md#pytz)

*   [ ] You can convert timezones of datetime objects

Databases
---------

### [SQL](/Technical%20Stack/Backend%20Developer/Databases.md#sql)

#### [PostgreSQL](/Technical%20Stack/Backend%20Developer/Databases.md#postgre-sql)

*   [ ] You know how to create foreign keys
*   [ ] You know data types, including JSON
*   [ ] You know how to query data using JSON path

### [NoSQL](/Technical%20Stack/Backend%20Developer/Databases.md#no-sql)

#### [Firebase Firestore](/Technical%20Stack/Backend%20Developer/Databases.md#firebase-firestore)

*   [ ] You know how to connect and create a collection
*   [ ] You can listen for changes using live data updates

#### [Redis](/Technical%20Stack/Backend%20Developer/Databases.md#redis)

*   [ ] You know what data types are supported

#### [ElasticSearch](/Technical%20Stack/Backend%20Developer/Databases.md#elastic-search)

*   [ ] You are able to define an index
*   [ ] You are able to query index
*   [ ] You know how to update an index

#### [AWS DynamoDB](/Technical%20Stack/Backend%20Developer/Databases.md#aws-dynamo-db)

*   [ ] You know how to read from and write to a DynamoDB table
*   [ ] You know how to scan the table to search for an item and understand the performance cost of this operation

#### [MongoDB](/Technical%20Stack/Backend%20Developer/Databases.md#mongo-db)

*   [ ] You know how to structure documents

Javascript
----------

### [NodeJS](/Technical%20Stack/Backend%20Developer/Javascript.md#node-js)

#### [express](/Technical%20Stack/Backend%20Developer/Javascript.md#express)

*   [ ] You know how to create a json response
*   [ ] You know how to add a middleware
*   [ ] You know how to fetch/persist data in DB

#### \[Optional\] [mongoose](/Technical%20Stack/Backend%20Developer/Javascript.md#mongoose)

*   [ ] You know how to create Model using Schema

3rd Party
---------

### [Payment Services](/Technical%20Stack/Backend%20Developer/3rd%20Party.md#payment-services)

#### [Stripe](/Technical%20Stack/Backend%20Developer/3rd%20Party.md#stripe)

##### [Python](/Technical%20Stack/Backend%20Developer/3rd%20Party.md#python)

*   [ ] You can create a payment using django-stripe-payments
*   [ ] You know how to do a refund

### [Authentication Services](/Technical%20Stack/Backend%20Developer/3rd%20Party.md#authentication-services)

#### \[Optional\] [OAuth](/Technical%20Stack/Backend%20Developer/3rd%20Party.md#oauth)

##### \[Optional\] [Auth0](/Technical%20Stack/Backend%20Developer/3rd%20Party.md#auth0)

*   [ ] You know how to activate a provider
*   [ ] You know how to upload custom templates

#### [JWT](/Technical%20Stack/Backend%20Developer/3rd%20Party.md#jwt)

*   [ ] You how used at least one library to work with JWT
*   [ ] You can create JWT with custom payload

### [Contentful](/Technical%20Stack/Backend%20Developer/3rd%20Party.md#contentful)

*   [ ] You can manage webhooks
*   [ ] You can upload models from CLI

Documenting
-----------

### \[Optional\] [Swagger](/Technical%20Stack/Backend%20Developer/Documenting.md#swagger)

*   [ ] You know how to annotate endpoints to describe it

#### \[Optional\] [drf-yasg](/Technical%20Stack/Backend%20Developer/Documenting.md#drf-yasg)

*   [ ] You know how to configure the view

### \[Optional\] [Redoc](/Technical%20Stack/Backend%20Developer/Documenting.md#redoc)

*   [ ] You know how to initialize it

Development Tools
-----------------

### \[Optional\] [CLI](/Technical%20Stack/Backend%20Developer/Development%20Tools.md#cli)

*   [ ] You used one of

#### \[Optional\] [httpie](/Technical%20Stack/Backend%20Developer/Development%20Tools.md#httpie)

*   [ ] You can create requests with JSON payload

### [Build Tools](/Technical%20Stack/Backend%20Developer/Development%20Tools.md#build-tools)

*   [ ] You used one of the tools in a project

Code Analysis
-------------

### [Profilers](/Technical%20Stack/Backend%20Developer/Code%20Analysis.md#profilers)

#### [cProfiler](/Technical%20Stack/Backend%20Developer/Code%20Analysis.md#c-profiler)

*   [ ] You know how to read results table, including cumulative time

### [Code Linters](/Technical%20Stack/Backend%20Developer/Code%20Analysis.md#code-linters)

#### [flake8](/Technical%20Stack/Backend%20Developer/Code%20Analysis.md#flake8)

*   [ ] You know how to configure

### [Code Formatters](/Technical%20Stack/Backend%20Developer/Code%20Analysis.md#code-formatters)

#### [black](/Technical%20Stack/Backend%20Developer/Code%20Analysis.md#black)

*   [ ] You are able to adjust defaults

* * *

Contribution
------------

We are very open to contributions to extend or change the requirements based on your gut and experience. To contribute you can use a **pull request** which will be later validated by our technical team and added to the main docs.

If you will spot any issues please add them in the **Issues** section.

Credits
-------

This page is maintained by the 🔹 [Flairs.ai](http://Flairs.ai) and 🇵🇱 [Apptension](https://apptension.com) teams.

If you would like to create a dedicated Developer Handbook for your company, you can e-mail us 👉 [contact@flairs.ai](mailto:contact@flairs.ai)

License
-------

![MIT License](https://img.shields.io/badge/License-MIT-blue.svg)

© 2020 Flairs Sp. z o.o.

Built and maintained by [Flairs](https://www.flairs.ai) and [Apptension](https://apptension.com).

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.