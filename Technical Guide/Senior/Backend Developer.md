Backend Developer
=================

Python
------

### Frameworks

#### Django

##### django-fsm

*   [ ] You can create State Machine with simple transitions [:books:](https://hashedin.com/blog/a-guide-to-managing-finite-state-machine-using-django-fsm/)
*   [ ] You know how to listen for state transitions

###### django-fsm-log

*   [ ] You know how to use current user context in message log

##### django-cacheops

*   [ ] You know how to configure defaults for models [:books:](https://dizballanze.com/django-project-optimization-part-3/)
*   [ ] You know how to disable caching for specific query

##### django-notifications-hq

*   [ ] You know how to create a notification

##### django-modeltranslation

*   [ ] Know how to translate Django models fields
*   [ ] You know how to setup fallback language

##### django-hashid-field

*   [ ] You have to configure salt and length of the hash
*   [ ] You know how to use it as a PK

##### django-environ

*   [ ] You know how to define defaults
*   [ ] How to cast variables, including lists
*   [ ] You can use helpers like db for connection strings
*   [ ] You understand 12 factor app concept

##### django-reversion

*   [ ] How to declare a model with versioned history

##### django-inline-actions

*   [ ] You are able to add your own action in Django admin panel
*   [ ] You know how to set a custom name for an action
*   [ ] You can decide when it's appropriate library, contrary to your own implementation

##### Django Enumeration types

*   [ ] You know how to declare a type

##### Custom User model

*   [ ] You understand pitfalls of not doing so
*   [ ] You can define necessary manager class

#### Flask

*   [ ] Define routes with http verbs
*   [ ] How to setup an app config
*   [ ] Use with storage, using DB of choice
*   [ ] How to response with json and use http code constants

#### django-filter

*   [ ] You can create full text search query
*   [ ] You know how to use ordering query
*   [ ] You can use it with DRF Generic View
*   [ ] You know how to create custom queryset for a filter

#### Serverless Framework

*   [ ] You can create simple HTTP endpoint using API gateway
*   [ ] You know plugins to handle local development like serverless offline
*   [ ] Configure more robust triggers like SQS events
*   [ ] You know how to use WSGI based framework

#### Zappa

*   [ ] You know how to scaffold a Django app

#### FastAPI

*   [ ] You know how to create routing with query params
*   [ ] You can query DB using one of asynchronous libraries
*   [ ] You know how to use model in response
*   [ ] You can create server side events view
*   [ ] You know how to use <code>Depends</code>

### Utils

#### pydantic

*   [ ] You know how to declare a model
*   [ ] You can identify proper field types to model

#### boto3

*   [ ] You know how to use resources
*   [ ] You know how credentials are used, along with region

#### django-whitenoise

*   [ ] Know how to setup static files served by a middleware

#### WeasyPrint

*   [ ] You are able to render a PDF

### ORM

#### Django ORM

*   [ ] You are able to create Models
*   [ ] You used proxy model
*   [ ] You know how to chain queries using custom Manager
*   [ ] You can create model inheritance

#### Sequelize

*   [ ] You can create Model
*   [ ] You know how to create virtual fields

#### sqlalchemy

*   [ ] You know how to configure a connection
*   [ ] You can setup/create migrations

#### pynamodb

*   [ ] You know how to create a model
*   [ ] You know how to fetch by a hash or scan by props
*   [ ] You know how to do an upsert opearation

### Task Queues

#### Celery

*   [ ] You are able to create a task
*   [ ] You can create multiple queues
*   [ ] You can configure a broker
*   [ ] You know how to use flower
*   [ ] You can create own Task classes to extend functionality
*   [ ] You know how does sofy and hard limit works

### Template engines

#### Jinja

*   [ ] You know how to use it to render templates

#### pystashe

*   [ ] You are able to render a template

Testing
-------

### Python

#### pytest

*   [ ] Can setup a test case with multiple paths using fixtures
*   [ ] You are able to define custom fixtures
*   [ ] You know how to add plugins
*   [ ] You know fixture scopes

#### factory_boy

*   [ ] You know how to create a factory
*   [ ] You know how to use traits
*   [ ] You know how to create related factories

#### faker

*   [ ] You know how to generate faked values using built-in providers

### Node.js

#### Jest

*   [ ] You know how to configure a test env
*   [ ] You can describe a test using assertions

### Performance Testing

#### Artillery.io

*   [ ] You can create scenarios
*   [ ] You know how to generate fake data
*   [ ] You know how to pass variables between phases

Date & Time
-----------

### Python

#### python-dateutil

*   [ ] You are able to create relative datetime objects

#### pytz

*   [ ] You can convert timezones of datetime objects

Databases
---------

### SQL

#### PostgreSQL

*   [ ] You know how to create foreign keys
*   [ ] You know data types, including JSON
*   [ ] You know how to query data using JSON path

### NoSQL

#### Firebase Firestore

*   [ ] You know how to connect and create a collection
*   [ ] You can listen for changes using live data updates

#### Redis

*   [ ] You know what data types are supported

#### ElasticSearch

*   [ ] You are able to define an index
*   [ ] You are able to query index
*   [ ] You know how to update an index

#### AWS DynamoDB

*   [ ] You know how to read from and write to a DynamoDB table
*   [ ] You know how to scan the table to search for an item and understand the performance cost of this operation
*   [ ] You know how to create a Global Secondary Index

#### MongoDB

*   [ ] You know how to structure documents

Javascript
----------

### NodeJS

#### express

*   [ ] You know how to create a json response
*   [ ] You know how to add a middleware
*   [ ] You know how to fetch/persist data in DB

3rd Party
---------

### Payment Services

#### Stripe

##### Python

*   [ ] You can create a payment using django-stripe-payments
*   [ ] You know how to do a refund

### Authentication Services

#### JWT

*   [ ] You how used at least one library to work with JWT
*   [ ] You can create JWT with custom payload

### Contentful

*   [ ] You can manage webhooks
*   [ ] You can upload models from CLI

Documenting
-----------

Development Tools
-----------------

### Build Tools

*   [ ] You used one of the tools in a project

Code Analysis
-------------

### Profilers

#### Google Cloud Profiler

*   [ ] You are able to read flame graph

#### cProfiler

*   [ ] You know how to read results table, including cumulative time

### Code Linters

#### flake8

*   [ ] You know how to configure

#### pylint

*   [ ] You know how to write custom rule

### Code Formatters

#### black

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