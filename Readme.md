# aws-lambda-list

[![License](https://img.shields.io/github/license/unixorn/aws-lambda-list.svg)](https://opensource.org/licenses/Apache-2.0)
[![Build Status](https://travis-ci.org/unixorn/aws-lambda-list.svg?branch=master)](https://travis-ci.org/unixorn/aws-lambda-list)
[![GitHub stars](https://img.shields.io/github/stars/unixorn/aws-lambda-list.svg)](https://github.com/unixorn/aws-lambda-list/stargazers)
[![Code Climate](https://codeclimate.com/github/unixorn/aws-lambda-list/badges/gpa.svg)](https://codeclimate.com/github/unixorn/aws-lambda-list)
[![Issue Count](https://codeclimate.com/github/unixorn/aws-lambda-list/badges/issue_count.svg)](https://codeclimate.com/github/unixorn/aws-lambda-list)

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
## Table of Contents

- [Frameworks](#frameworks)
  - [apex](#apex)
  - [brutus](#brutus)
  - [chalice](#chalice)
  - [dawson-cli](#dawson-cli)
  - [Hexaville](#hexaville)
  - [power-jambda](#power-jambda)
  - [python-lambda](#python-lambda)
  - [python-lambdarest](#python-lambdarest)
  - [Pyverless](#pyverless)
  - [Rumbda](#rumbda)
  - [Serverless](#serverless)
  - [Serverless Golang](#serverless-golang)
  - [Up](#up)
  - [Webda](#webda)
  - [Zappa](#zappa)
- [Functions & Applications](#functions--applications)
- [Other Resources](#other-resources)
  - [Miscellaneous](#miscellaneous)
  - [Tutorials](#tutorials)
  - [Utilities](#utilities)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

A list of AWS lambdas and lambda-related resources. Hopefully some are even useful.

Please note that there are no guarantees that the functions here are safe to run - you're going to have to test them yourself.

This list is under the [Apache 2.0 license](https://github.com/unixorn/aws-lambda-list/blob/master/LICENSE).

## Frameworks

### [apex](http://apex.run/)

Apex lets you use languages that are not natively supported by AWS Lambda, such as Golang, through the use of a Node.js shim injected into the build. A variety of workflow related tooling is provided for testing functions, rolling back deploys, viewing metrics, tailing logs, hooking into the build system and more.

### [brutus](https://github.com/milesgranger/brutus)

An HTTP/TCP Distributed Computing Framework in Python using Amazon Lambda functions.

This is a working prototype, still under development. Not suitable for anything other than exploring, making suggestions/issues.

### [chalice](https://github.com/aws/chalice)

Chalice is Amazon's python serverless microframework for AWS. It allows you to quickly create and deploy applications that use Amazon API Gateway and AWS Lambda.

### [colly](https://github.com/tmaslen/colly)

Another Javascript serverless framework for AWS Lambda and API Gateway.

### [dawson-cli](https://github.com/dawson-org/dawson-cli)

A serverless web framework for Node.js on AWS (CloudFormation, CloudFront, API Gateway, Lambda). More details at [https://dawson.sh](https://dawson.sh).

### [Hexaville](https://github.com/noppoMan/Hexaville)

Hexaville is a serverless framework for Swift using AWS Lambda + ApiGateway etc as a back end. Build applications in Swift comprised of microservices that run in response to events, automatically scale to meet demand, and only be charged for time actually spent running.

### [power-jambda](https://github.com/visionarts/power-jambda)

A Java serverless microframework for RESTful API that allows you to quickly develop applications that use Amazon API Gateway and AWS Lambda.

### [python-lambda](https://github.com/nficano/python-lambda)

A toolkit for developing and deploying serverless Python code in AWS Lambda. The Python-Lambda library takes away the guess work of developing your Python-Lambda services by providing you a toolset to streamline the annoying parts.

### [python-lambdarest](https://github.com/trustpilot/python-lambdarest)

Python routing mini-framework for AWS Lambda with optional JSON-schema validation.

Features:

* lambda_handler function constructor with built-in dispatcher
* Decorator to register functions to handle HTTP methods
* Optional JSON-schema input validation using same decorator

### [Pyverless](https://github.com/QuantumBA/pyverless)

Pyverless is a mini-framework with a bunch of utilities that aims to help you create APIs using AWS Lambdas fast and in a consistent way. Pyverless provides the following:

* Authentication handling
* Class-Based Handlers
* Configuration
* Exceptions
* JWT and cryptography
* Serializers
* Warmup handling

### [Rumbda](https://github.com/kleaver/rumbda)

Rumbda does everything necessary to build a zip file for running ruby inside of an AWS Lambda. This includes downloading [traveling ruby](https://github.com/phusion/traveling-ruby), creating a bundle of the project's Gemfile dependencies, and creating a consumable .zip file for use with Lambda.

### [Serverless](https://www.serverless.com)

Build web, mobile and IoT applications with serverless architectures using AWS Lambda, Azure Functions, Google CloudFunctions & more! Here is a list of [Serverless Examples](https://github.com/serverless/examples).

### [Serverless Golang](https://github.com/yunspace/serverless-golang)

AWS Lambda Go functions using Serverless Framework and a Python shim.

### [Sparta](http://gosparta.io/)

A Go framework for transforming a Go application into an AWS Lambda powered microservice. Supports multiple event sources, compile-time IAM policies, and automatic packaging and marshaling to CloudFormation.

### [Up](https://github.com/apex/up)

Up focuses on deploying "vanilla" HTTP servers so there's nothing new to learn, just develop with your favorite existing frameworks such as Express, Koa, Django, Golang net/http or others.

Up currently supports Node.js, Golang, Python, Java, Crystal, and static sites out of the box. Up is platform-agnostic, supporting AWS Lambda and API Gateway as the first targets. You can think of Up as self-hosted Heroku style user experience for a fraction of the price, with the security, flexibility, and scalability of AWS.

### [Webda](https://github.com/loopingz/webda)

A serverless Javascript Development Framework with AWS Lambda and Docker deployment options.

### [Zappa](https://github.com/Miserlou/Zappa)

Zappa makes it super easy to build and deploy server-less, event-driven Python applications (including, but not limited to, WSGI web apps) on AWS Lambda + API Gateway.

## Functions & Applications

This section is for both single functions and applications composed of multiple interconnected AWS lambda functions.

* [aws-key-disabler](https://github.com/te-papa/aws-key-disabler) - Lambda Function that disables AWS IAM User Access Keys after a set amount of time in order to reduce the risk associated with old access keys.
* [aws-lambda-blog-platform](https://github.com/sirceljm/aws-lambda-blog) - A complete blogging solution that uses the following Amazon Web Services for operation - API Gateway, Lambda, DynamoDB, S3, Cloudfront, SES.
* [aws-maintenance-lambda (indix)](https://github.com/indix/aws-maintenance-lambda) - Send alerts (to Slack, HipChat) on AWS maintenance events.
* [aws-maintenance-lambda (traveloka)](https://github.com/traveloka/aws-maintenance-lambda) - Trigger Jira Issue Creation from AWS Health Events.
* [aws-monitor](https://github.com/zulily/aws_monitor) - Run periodically as an AWS Lambda, will detect your instances, add CloudWatch alerting for each, and create CloudWatch dashboards based on your preferences.
* [aws-ses-to-elasticsearch](https://github.com/ScheduleOnce/aws-ses-to-elasticsearch) - SES is capable of sending reports about email delivery (deliveries, bounces, rejects) to SNS. However, there's no built in way to pipe these reports into something like Elastic Search. This Lambda function bridges the gap and allows to send the reports to ES.
* [binaryalert](https://github.com/airbnb/binaryalert) - Serverless, Real-time & Retroactive Malware Detection.
* [BucketSnake](https://github.com/Netflix-Skunkworks/bucketsnake) - Provisions S3 access for IAM roles. A primary feature of Bucket Snake is to crete IAM roles that reside in the account where the S3 buckets live to facilitate proper cross-account S3 bucket access (via a role assumption).
* [chalice-transmogrify](https://github.com/uncompiled/chalice-transmogrify) - Python Microservice that transforms arbitrary XML/RSS to JSON.
* [chaos-lambda](https://github.com/shoreditch-ops/chaos-lambda) - A Serverless implementation of Netflix's [Chaos Monkey](https://github.com/Netflix/SimianArmy/wiki/Chaos-Monkey) for AWS (runs on AWS Lambda).
* [chef-node-cleanup](https://github.com/awslabs/lambda-chef-node-cleanup) - Automatically Delete Terminated Instances in Chef Server with AWS Lambda when triggered by CloudWatch instance termination events.
* [chromeless](https://github.com/lagleki/chromeless) - Chrome automation made simple. Runs locally or headless on AWS Lambda. See [https://chromeless.netlify.com](https://chromeless.netlify.com) for more details.
* [cloudwatch-logs-shipper-logzio-lambda](https://github.com/logzio/cloudwatch-logs-shipper-lambda) - Ships Cloudwatch Logs to [logz.io](logz.io).
* [cwlogs2sns](https://github.com/jakubknejzlik/cwlogs2sns) - AWS CloudWatch to SNS handler for AWS Lambda.
* [ddns-function](https://github.com/awslabs/aws-lambda-ddns-function) - Dynamically create Route 53 resource records using CloudWatch Events and AWS Lambda.
* [ebs_snapper](https://github.com/rackerlabs/ebs_snapper) - Allows you to schedule regular EBS snapshots and clean up EBS snapshots on EC2, as well as replicate snapshots to a secondary EC2 region.
* [ecs-host-service-scale](https://github.com/miketheman/ecs-host-service-scale) - Lambda function to ensure an ECS Service is set to the correct Desired Count for a One-Task-Per-Host placement value for any cluster that runs the Service.
* [felix](https://github.com/Cimpress-MCP/felix) - Automate the rotation of IAM keys used by third-party services. Felix is aimed at making it easy to manage IAM keys in third-party services like SumoLogic and GitLab. It aims to be easily extensible by both built-in providers and external plugins.
* [github-s3-deploy](https://github.com/nytlabs/github-s3-deploy) - AWS Lambda function, triggered by Github/SNS webhook, to sync new commits in an S3 bucket.
* [honeyλ](https://github.com/0x4D31/honeyLambda) - A simple, serverless application designed to create and monitor fake HTTP endpoints (i.e. URL honeytokens) automatically, on top of AWS Lambda and Amazon API Gateway.
* [houdini](https://github.com/citruspi/houdini) - Houdini runs on AWS Lambda and executes commands on remote hosts over SSH using [Paramiko](http://www.paramiko.org/). The host address, username, command, and private key name are provided by the consumer in the Lambda event, the command is executed, and the contents of stdin, stdout, and stderr are returned. The actual content of the private key used for establishing the SSH connection is encrypted with an [AWS KMS](https://aws.amazon.com/kms/) key and stored in [AWS SSM Parameter Store](https://aws.amazon.com/systems-manager/features/#Parameter_Store).
* [hugo-lambda](https://github.com/ryansb/hugo-lambda) - Use AWS Lambda to run the Hugo static site generator.
* [imprenta](https://github.com/alfredo/imprenta) - Generates PDF files from HTML using jinja, pdfkit and wkhtmltopdf.
* [invokust](https://github.com/FutureSharks/invokust) - A tool for running [Locust](http://locust.io/) load tests from within Python without the need to use the locust command line to allow running load tests in python or on AWS Lambda.
* [lambda-comments](https://github.com/jimpick/lambda-comments) - Blog commenting system built with AWS Lambda, API Gateway, S3, DynamoDB streams, IAM and CloudWatch Logs.
* [lambda-keystore](https://github.com/subdavis/lambda-keystore) - Simple key-value store with TTL for AWS Lambda using DynamoDB.
* [lambda-packs](https://github.com/ryfeus/lambda-packs) - Precompiled packages for Lambda.
* [lambdaproxy](https://github.com/dan-v/awslambdaproxy) - Lambda powered HTTP/SOCKS web proxy.
* [LambdAuth](https://github.com/danilop/LambdAuth) - Sample authentication service implemented with a server-less architecture, using AWS Lambda to host and execute the code and Amazon DynamoDB as persistent storage. This provides a cost-efficient solution that is scalable and highly available and can be used with Amazon Cognito for Developer Authenticated Identities.
* [letsencrypt](https://github.com/ubergeek42/lambda-letsencrypt) - Use [AWS Lambda](https://aws.amazon.com/lambda/) to manage SSL certificates for any site that uses [Amazon's CloudFront CDN](https://aws.amazon.com/cloudfront/).
* [MoonMail](https://github.com/microapps/MoonMail) - Sends email marketing campaigns with [Amazon SES](https://moonmail.io/amazon-ses-email-marketing/).
* [node-letsencrypt-lambda](https://github.com/ocelotconsulting/node-letsencrypt-lambda) - Use AWS Lambda to manage SSL certificates for Lets-Encrypt.
* [perf-cop](https://github.com/Quartz/perf-cop) - Profiles your site with PWMetrics and publishes the results as CloudWatch metrics.
* [pricing-tools](https://github.com/concurrencylabs/aws-pricing-tools) - A Lambda function that calculates near real-time price of an account's infrastructure including EC2, ELB, EBS, RDS, Lambda, Dynamo DB and Kinesis resources.
* [reaper-lambda](https://github.com/gabinante/reaper-lambda) - Reaps any and all instances which are not tagged with an expiration date.
* [s3-file-copier](https://github.com/roberthelmick08/aws-lambda-s3-file-copier) - Lambda function that copies files from source S3 bucket to target bucket upon upload.
* [send-ses-email](https://github.com/eleven41/aws-lambda-send-ses-email) - Send emails using Amazon SES. The primary purpose of this function is to provide a server-side back-end for sending emails from static websites.
* [serverless-ami-replicator](https://github.com/miztiik/serverless-ami-replicator) - Replicate AMIs across AWS Regions.
* [serverless-backup](https://github.com/miztiik/serverless-backup) - A simple AWS Boto3 script to trigger EBS Snapshots using Lambda Functions.
* [serverless-ephemeral](https://github.com/Accenture/serverless-ephemeral) - Serverless Ephemeral (or Serephem) is a [Serverless Framework](https://serverless.com/framework/docs/providers/aws/guide/plugins/) plugin that helps bundle any stateless library into a Lambda deployment artifact.
* [serverless-plugin-healthcheck](https://github.com/Financial-Times/serverless-plugin-healthcheck) - Creates one schedule event lambda that invokes all the service lambdas you select in a configured time interval (default: 5 minutes) or a specific time, forcing your containers to report their status. In adition, it creates a new endpoint (named __health by default) which can be called to provide a json summary of the current status of each healthcheck.
* [serverless-plugin-stackstorm](https://github.com/StackStorm/serverless-plugin-stackstorm) - Plugin for serverless framework to run ready to use actions from [StackStorm Exchange](https://exchange.stackstorm.org) as AWS Lambda functions.
* [serverless-s3-processing](https://github.com/btsuhako/serverless-s3-processing) - Uses the [Serverless](https://serverless.com/) Framework and AWS Lambda to process objects and events from S3.
* [serverless-secrets](https://github.com/marksteele/serverless-secrets) - Sample serverless AWS Lambda application that leverages the AWS SSM parameter store for managing secrets.
* [serverless-url-shortener](https://github.com/danielireson/serverless-url-shortener) - URL shortener for AWS Lambda and S3.
* [SES Email Forwarder](https://github.com/arithmetric/aws-lambda-ses-forwarder) - Node.js script for AWS Lambda that uses the inbound/outbound capabilities of AWS Simple Email Service (SES) to run a "serverless" email forwarding service. Instead of setting up an email server on an EC2 instance to handle email redirects, use SES to receive email, and the included Lambda script to process it and send it on to the chosen destination.
* [ses-forwarder](https://github.com/Technofy/ses-forwarder) - A Python 2.7 Email forwarder script for AWS Lambda, which uses the AWS SES and S3 services.
* [Shelvery](https://github.com/base2Services/shelvery) - Shelvery is a tool for creating backups in Amazon cloud (AWS). It currently supports RDS and EBS backups, and AMI support is scheduled to be released soon.
* [sns2slack](https://github.com/jakubknejzlik/sns2slack) - AWS SNS to slack notifications handler for AWS Lambda.
* [splunk-aws-serverless-apps](https://github.com/splunk/splunk-aws-serverless-apps) - Splunk AWS Serverless applications and [Lambda blueprints](https://www.splunk.com/blog/2016/11/29/announcing-new-aws-lambda-blueprints-for-splunk.html), including associated CloudFormation templates (using [SAM](https://github.com/awslabs/serverless-application-model)) for automated packaging & deployment.
* [StreamAlert](https://github.com/airbnb/streamalert) - StreamAlert is a serverless, realtime data analysis framework which empowers you to ingest, analyze, and alert on data from any environment, using datasources and alerting logic you define.
* [sumologic-aws-lambda-unzip](https://github.com/frankreno/sumologic-aws-lambda-unzip) - Java Lambda function that can uncompress a zip file, read the files inside and send them to Sumo Logic.
* [url-shortener](https://github.com/guihaojin/url-shortener) - URL Shortener service built with serverless framework on AWS, API Gateway + Lambda + DynamoDB.
* [werdino-lambda](https://github.com/dariopog/werdino-lambda) - AWS Lambda function for the [Werdino](https://github.com/dariopog/werdino-webhook) webhook.

## Other Resources

### Miscellaneous

* [aws-lambda-cheatsheet](https://github.com/srcecde/aws-lambda-cheatsheet) - A cheatsheet for AWS Lambda (focuses on Python)

### Tutorials

* [AWS IOT Button Example](https://github.com/mongoose-os-apps/aws-iot-button) - This is an Internet Button reference project: when a button on the device is pressed, a cloud backend gets a notification and performs an action. In this particular case, AWS Lambda function sends an email to the specific email address.
* [Lambda Tutorial: Lambda + Serverless = HAPPY](https://www.youtube.com/watch?v=71cd5XerKss)
* [Learning Lambda](https://blog.symphonia.io/learning-lambda-1f25af64161c) - Mike Roberts' series on learning to use Lambda
* [Nightmare-lambda-tutorial](https://github.com/dimkir/nightmare-lambda-tutorial) - A sample project and tutorial to show how to run NightmareJS on AWS Lambda.
* [AWS IOT Button Example](https://github.com/mongoose-os-apps/aws-iot-button) - This is an Internet Button reference project: when a button on the device is pressed, a cloud backend gets a notification and performs an action. In this particular case, AWS Lambda function sends an email to the specific email address.

### Utilities

* [api-gateway-sim](https://github.com/elitechance/api-gateway-sim) - API Gateway simulator for Node JS Lambda that allows you to test your Lambda function locally.
* [aws-lambda-dotnet](https://github.com/aws/aws-lambda-dotnet) - Libraries, samples and tools to help .NET Core developers develop AWS Lambda functions.
* [aws-lambda-runner](https://github.com/kevinsimard/aws-lambda-runner) - An AWS Lambda Java simulator that allows running and debugging Lambda functions authored in Java locally.
* [aws-sam-local](https://github.com/awslabs/aws-sam-local) - `sam` is the AWS CLI tool for managing Serverless applications written with [AWS Serverless Application Model (SAM)](https://github.com/awslabs/serverless-application-model). SAM Local can be used to test functions locally, start a local API Gateway from a SAM template, validate a SAM template, and generate sample payloads for various event sources.
* [claudia](https://github.com/claudiajs/claudia) - Claudia makes it easy to deploy Node.js projects to AWS Lambda and API Gateway. It automates all the error-prone deployment and configuration tasks, and sets everything up the way JavaScript developers expect out of the box. This means that you can get started with Lambda and API Gateway easily, and focus on solving important business problems instead of dealing with AWS deployment workflows.
* [cljs-lambda](https://github.com/nervous-systems/cljs-lambda) - Utilities around deploying Clojurescript functions to AWS Lambda.
* [dd-aws-lambda-functions](https://github.com/DataDog/dd-aws-lambda-functions) - Repository of lambda functions that process aws log streams and send data to datadog
* [docker-lambda-python36-rust](https://github.com/ElementAI/docker-lambda-python36-rust) - Docker image that builds Rust applications serverless for AWS Lambda.
* [docker-lambda](https://github.com/lambci/docker-lambda) - Docker images and test runners that replicate the live AWS Lambda environment
* [formplug-serverless](https://github.com/danielireson/formplug-serverless) - A form forwarding service for AWS Lambda that you can use to accept form submissions by email without server-side code.
* [goad](https://github.com/goadapp/goad) - An AWS Lambda powered, highly distributed, load testing tool built in Go.
* [iopipe-python](https://github.com/iopipe/iopipe-python) - This package provides analytics and distributed tracing for event-driven applications running on AWS Lambda.
* [iron-io/lambda](https://github.com/iron-io/lambda) - A set of tools, tests and libraries to convert Amazon AWS Lambda functions into Docker images that can run on any computer or cloud provider.
* [jiffy-route-builder](https://github.com/jiffycloud/jiffy-route-builder) - A tiny module (<5KB) to create lightweight API handlers using Node.js with AWS Lambda and API Gateway. Uses another tiny (<2KB) library called [route-recognizer](https://github.com/tildeio/route-recognizer) to match URLs against routing patterns, and forwards requests to handler functions. Written in TypeScript so you have type information available - especially useful to figure out what's available in the request that API Gateway sends to your handler.
* [lambda-deployer](https://github.com/mdevilliers/lambda-deployer) - Automate the deployment of AWS Lambda functions easily from either a developers machine or CI system.
* [lambda-packager](https://github.com/lorenzoh/lambda-packager) - Uses the amazonlinux Docker image to build Python packages for AWS Lambda.
* [lambda-packages](https://github.com/Miserlou/lambda-packages) - Various popular python libraries, pre-compiled to be compatible with AWS Lambda. The best way to use these packages is with [Zappa](https://github.com/Miserlou/Zappa), which will automatically install the right packages during deployment, and do a million other useful things [https://blog.zappa.io](https://blog.zappa.io).
* [lambda-tdd](https://github.com/simlu/lambda-tdd) - A testing framework for AWS Lambda functions. Useful for integration testing as you can examine how your lambda function executes for certain input and specific environment variables. Tries to model the cloud execution as closely as possible
* [lambda-tester](https://github.com/vandium-io/lambda-tester) - Helper for unit testing AWS Lambda functions using Node.js
* [lambda_utils](https://github.com/CloudHeads/lambda_utils) - Python helper decorator for handling different AWS Event types for AWS Lambda.
* [lambdaSH](https://github.com/alestic/lambdash) - Run shell commands inside AWS Lambda environment
* [lambdaskill](https://github.com/michaeluhl/lambdaskill) - A simple Python 3 toolkit to build Alexa Skills using AWS Lambda.
* [lambdaWrap](https://github.com/Cimpress-MCP/LambdaWrap) - Ruby gem to simplify deployment of AWS Lambda based web services.
* [python-vendor](https://github.com/joshringer/python-vendor) - Provides an AWS service API for building compiled Python packages, ready for use in your own AWS Lambda functions.
* [simple-lambda-mailer](https://github.com/hendrickson02/simple-lambda-mailer) - A simple mailer that you can use in a web blog and call via an API.
* [simple-lambda-router](https://github.com/brunomorency/simple-lambda-router) - A small router utility for lambda functions handling HTTP events from multiple resources and methods.
* [webpack-aws-lambda-upload-plugin](https://github.com/sirceljm/webpack-aws-lambda-upload-plugin) - Zip and upload your AWS Lambda function directly from webpack.
