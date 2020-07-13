DevOps Developer
================

DNS
---

*   [ ] You know what a CNAME record is and when to use it
*   [ ] You know what an A and AAAA records are and when to use them
*   [ ] You know what TXT records is and when to use it
*   [ ] You know how to register a new domain with a chosen DNR
*   [ ] You know how to switch NS from default ones set by DNR to another provider
*   [ ] You know what a MX record is and when to use it

### DNS Services

#### Route 53

*   [ ] You know how to define a new hosted zone

#### Cloudflare

*   [ ] You know how to define a new DNS zone

Databases
---------

### SQL

#### AWS RDS

*   [ ] You know how to instantiate a PostgreSQL database
*   [ ] You know how to instantiate a MySQL database

### NoSQL

#### Redis

##### AWS ElastiCache

*   [ ] You know how to create a Redis instance
*   [ ] You know how to connect to Redis instance from the application code

#### ElasticSearch

##### AWS Elasticsearch Service

*   [ ] You know how to create an ElasticSearch instance
*   [ ] You know how to connect to ElasticSearch from the application code

#### AWS DynamoDB

*   [ ] You know how to manage dynamodb read/write throughput
*   [ ] You know how to configure pay per use model

Contenerization Services
------------------------

### AWS ECS

*   [ ] You know how to create a task definition
*   [ ] You know how to execute a one off task that is killed after execution and doesn't get restarted
*   [ ] You know how to define a service
*   [ ] You know how to create a target group pointing to your ECS service and add it to an Application Load Balancer listener

### Kubernetes

*   [ ] You know how to define a deployment entity

Application Servers
-------------------

### Nginx

*   [ ] You know configuration file syntax
*   [ ] You know how to serve static files
*   [ ] You know how to define a proxy pass to API server

### WSGI

*   [ ] You know how to deploy a wsgi app (django, flask) with one of the application servers
*   [ ] You know wsgi configuration file syntax

Task Queues
-----------

### Celery

*   [ ] You can choose one of the message brokers and configure Celery to use it
*   [ ] You can deploy Celery workers to at least one platform of your choice

Message Brokers
---------------

### RabbitMQ

*   [ ] You understand what a virtual host is and how to create one

### AWS SQS

*   [ ] You know how to create an SQS queue
*   [ ] You can attach Lambda function trigger to a queue

### AWS EventBridge

*   [ ] You can create an EventBus
*   [ ] You can send custom events to an EventBus
*   [ ] You know how to trigger a Lambda function from an EventBus for a specific event source

Generic AWS Services
--------------------

### VPC

*   [ ] You know how to create a VPC
*   [ ] You understand the concept of Subnets and know how to create one
*   [ ] You understand the concept of Security Groups, know how to create one and how to define its rules
*   [ ] You know what a NAT Gateway is (and how much it costs)
*   [ ] You know what a VPC Endpoint is and how to define it

### EC2

*   [ ] You know how to create an EC2 instance
*   [ ] You know how to SSH into an EC2 instance using generated key pair
*   [ ] You know how to create an Application Load Balancer
*   [ ] You know how to attach a Security Group to an instance

### IAM

*   [ ] You know how to create a new user
*   [ ] You know how to create a new role
*   [ ] You know how to create a policy documents and attach them to various IAM resources

### KMS

*   [ ] You know how to create a KMS key and assign alias to it

### SSM

*   [ ] You know how to create an SSM parameter and encrypt it with a KMS key
*   [ ] You know how to use SSM parameter in Lambda function

### AWS Client libraries

#### aws-cli

*   [ ] You know how to create a local profile using acquired key id and secret to access AWS resources

Storage
-------

### AWS S3

*   [ ] You know how to create an S3 bucket
*   [ ] You know how to make a S3 bucket public
*   [ ] You know how to host a Single Page Application in S3

Continuous Integration
----------------------

### Bitbucket Pipelines

*   [ ] You know how to turn Bitbucket pipelines on in a repository
*   [ ] You know how to run a pipeline execution after a commit or a tag push
*   [ ] You know how to define environmental variables that will be available to a build script

### Github Actions

*   [ ] You know how to define a workflow
*   [ ] You know how to run a workflow execution after a commit or a tag push
*   [ ] You know how to define environmental variables that will be available to a build script

### AWS CodePipeline

*   [ ] You know how to create a CodePipeline
*   [ ] You know how to define a build step using CodeBuild
*   [ ] You know how to connect CodePipeline to an S3 source so the execution starts when a file changes
*   [ ] You know how to connect CodePipeline to a CodeCommit repository so the execution starts when branch or tag has been pushed
*   [ ] You know how to connect CodePipeline to a custom repository (Github, Bitbucket) so the execution starts when branch or tag has been pushed
*   [ ] You know how to define environmental variables that will be available to a build script
*   [ ] You know how to assign a custom IAM role to the build executor so it can access AWS resources

CDN
---

### AWS CloudFront

*   [ ] You know how to create a CloudFront distribution
*   [ ] You know how to add a behaviour pointing to an S3 website bucket

### Netlify

*   [ ] You know how to create an app
*   [ ] You know how to create a custom domain for an app
*   [ ] You know how to define environmental variables available during build step

Docker Registry
---------------

### AWS ECR

*   [ ] You know how to create a registry
*   [ ] You know how to upload a Docker image to a registry
*   [ ] You know how to define an IAM policy of a registry to allow pull/push to a specific user or role
*   [ ] You know how to log into the ECR registry using aws-cli

VPS Services
------------

### DigitalOcean

*   [ ] You know how to create a droplet in chosen region

### AWS EC2

*   [ ] You know how to create an instance in a chosen region

Monitoring
----------

*   [ ] Work in progress

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