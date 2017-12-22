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
  - [chalice](#chalice)
  - [dawson-cli](#dawson-cli)
  - [Hexaville](#hexaville)
  - [python-lambda](#python-lambda)
  - [Rumbda](#rumbda)
  - [Serverless](#serverless)
  - [Serverless Golang](#serverless-golang)
  - [Up](#up)
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

### [chalice](https://github.com/aws/chalice)

Chalice is Amazon's python serverless microframework for AWS. It allows you to quickly create and deploy applications that use Amazon API Gateway and AWS Lambda.

### [dawson-cli](https://github.com/dawson-org/dawson-cli)

A serverless web framework for Node.js on AWS (CloudFormation, CloudFront, API Gateway, Lambda). More details at [https://dawson.sh](https://dawson.sh).

### [Hexaville](https://github.com/noppoMan/Hexaville)

Hexaville is a serverless framework for Swift using AWS Lambda + ApiGateway etc as a back end. Build applications in Swift comprised of microservices that run in response to events, automatically scale to meet demand, and only charge for time actually spent running.

### [power-jambda](https://github.com/visionarts/power-jambda)

A java serverless microframework for RESTful API that allows you to quickly develop applications that use Amazon API Gateway and AWS Lambda.

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

* Class-Based Handlers
* Serializers
* Authentication handling
* JWT and cryptography
* Exceptions
* Configuration
* Warmup handling

### [Rumbda](https://github.com/kleaver/rumbda)

Rumbda does everything necessary to build a zip file for running ruby inside of an AWS Lambda. This includes downloading [traveling ruby](https://github.com/phusion/traveling-ruby), creating a bundle of the project's Gemfile dependencies, and creating a consumable .zip file for use with Lambda.

### [Serverless](https://www.serverless.com)

Build web, mobile and IoT applications with serverless architectures using AWS Lambda, Azure Functions, Google CloudFunctions & more!

### [Serverless Golang](https://github.com/yunspace/serverless-golang)

AWS Lambda Go functions using Serverless Framework and a Python shim.

### [Up](https://github.com/apex/up)

Up focuses on deploying "vanilla" HTTP servers so there's nothing new to learn, just develop with your favorite existing frameworks such as Express, Koa, Django, Golang net/http or others.

Up currently supports Node.js, Golang, Python, Java, Crystal, and static sites out of the box. Up is platform-agnostic, supporting AWS Lambda and API Gateway as the first targets. You can think of Up as self-hosted Heroku style user experience for a fraction of the price, with the security, flexibility, and scalability of AWS.

### [Zappa](https://github.com/Miserlou/Zappa)

Zappa makes it super easy to build and deploy server-less, event-driven Python applications (including, but not limited to, WSGI web apps) on AWS Lambda + API Gateway.

## Functions & Applications

Both single functions and Applications composed of multiple serverless functions

* [aws-lambda-blog-platform](https://github.com/sirceljm/aws-lambda-blog) - A complete blogging solution that uses the following Amazon Web Services for operation - API Gateway, Lambda, DynamoDB, S3, Cloudfront, SES
* [aws-maintenance-lambda](https://github.com/indix/aws-maintenance-lambda) - Send alerts (to Slack, HipChat) on AWS maintenance events.
* [aws-ses-to-elasticsearch](https://github.com/ScheduleOnce/aws-ses-to-elasticsearch) - SES is capable of sending reports about email delivery (deliveries, bounces, rejects) to SNS. However, there's no built in way to pipe these reports into something like Elastic Search. This Lambda function bridges the gap and allows to send the reports to ES.
* [binaryalert](https://github.com/airbnb/binaryalert) - Serverless, Real-time & Retroactive Malware Detection.
* [chaos-lambda](https://github.com/shoreditch-ops/chaos-lambda) - A Serverless implementation of Netflix's [Chaos Monkey](https://github.com/Netflix/SimianArmy/wiki/Chaos-Monkey) for AWS (runs on AWS Lambda).
* [chef-node-cleanup](https://github.com/awslabs/lambda-chef-node-cleanup) - Automatically Delete Terminated Instances in Chef Server with AWS Lambda when triggered by CloudWatch instance termination events.
* [ddns-function](https://github.com/awslabs/aws-lambda-ddns-function) - Dynamically create Route 53 resource records using CloudWatch Events and Lambda.
* [ecs-host-service-scale](https://github.com/miketheman/ecs-host-service-scale) - Lambda function to ensure an ECS Service is set to the correct Desired Count for a One-Task-Per-Host placement value for any cluster that runs the Service.
* [honeyλ](https://github.com/0x4D31/honeyLambda) - A simple, serverless application designed to create and monitor fake HTTP endpoints (i.e. URL honeytokens) automatically, on top of AWS Lambda and Amazon API Gateway.
* [hugo-lambda](https://github.com/ryansb/hugo-lambda) - Use AWS Lambda to run the Hugo static site generator.
* [invokust](https://github.com/FutureSharks/invokust) - A tool for running [Locust](http://locust.io/) load tests from within Python without the need to use the locust command line to allow running load tests in python or on AWS Lambda.
* [lambda-comments](https://github.com/jimpick/lambda-comments) - Blog commenting system built with AWS Lambda, API Gateway, S3, DynamoDB streams, IAM and CloudWatch Logs.
* [lambda-keystore](https://github.com/subdavis/lambda-keystore) - Simple key-value store with TTL for AWS Lambda using DynamoDB.
* [lambda-packs](https://github.com/ryfeus/lambda-packs) - Precompiled packages for Lambda.
* [lambdaproxy](https://github.com/dan-v/awslambdaproxy) - Lambda powered HTTP/SOCKS web proxy.
* [LambdAuth](https://github.com/danilop/LambdAuth) - Sample authentication service implemented with a server-less architecture, using AWS Lambda to host and execute the code and Amazon DynamoDB as persistent storage. This provides a cost-efficient solution that is scalable and highly available and can be used with Amazon Cognito for Developer Authenticated Identities.
* [letsencrypt](https://github.com/ubergeek42/lambda-letsencrypt) - Use [AWS Lambda](https://aws.amazon.com/lambda/) to manage SSL certificates for any site that uses [Amazon's CloudFront CDN](https://aws.amazon.com/cloudfront/).
* [node-letsencrypt-lambda](https://github.com/ocelotconsulting/node-letsencrypt-lambda) - Use AWS Lambda to manage SSL certificates for Lets-Encrypt.
* [pricing-tools](https://github.com/concurrencylabs/aws-pricing-tools) - A Lambda function that calculates near real-time price of an account's infrastructure including EC2, ELB, EBS, RDS, Lambda, Dynamo DB and Kinesis resources.
* [reaper-lambda](https://github.com/gabinante/reaper-lambda) - Reaps any and all instances which are not tagged with an expiration date.
* [send-ses-email](https://github.com/eleven41/aws-lambda-send-ses-email) - Send emails using Amazon SES. The primary purpose of this function is to provide a server-side back-end for sending emails from static websites.
* [serverless-plugin-healthcheck](https://github.com/Financial-Times/serverless-plugin-healthcheck) - Creates one schedule event lambda that invokes all the service lambdas you select in a configured time interval (default: 5 minutes) or a specific time, forcing your containers to report their status. In adition, it creates a new endpoint (named __health by default) which can be called to provide a json summary of the current status of each healthcheck.
* [serverless-url-shortener](https://github.com/danielireson/serverless-url-shortener) - URL shortener for AWS Lambda and S3.
* [SES Email Forwarder](https://github.com/arithmetric/aws-lambda-ses-forwarder) - Node.js script for AWS Lambda that uses the inbound/outbound capabilities of AWS Simple Email Service (SES) to run a "serverless" email forwarding service. Instead of setting up an email server on an EC2 instance to handle email redirects, use SES to receive email, and the included Lambda script to process it and send it on to the chosen destination.
* [StreamAlert](https://github.com/airbnb/streamalert) - StreamAlert is a serverless, realtime data analysis framework which empowers you to ingest, analyze, and alert on data from any environment, using datasources and alerting logic you define.

## Other Resources

### Miscellaneous

* [aws-lambda-cheatsheet](https://github.com/srcecde/aws-lambda-cheatsheet) - A cheatsheet for Lambda (focuses on Python)

### Tutorials

* [Lambda Tutorial: Lambda + Serverless = HAPPY](https://www.youtube.com/watch?v=71cd5XerKss)
* [Learning Lambda](https://blog.symphonia.io/learning-lambda-1f25af64161c) - Mike Roberts' series on learning to use Lambda

### Utilities

* [aws-sam-local](https://github.com/awslabs/aws-sam-local) - `sam` is the AWS CLI tool for managing Serverless applications written with [AWS Serverless Application Model (SAM)](https://github.com/awslabs/serverless-application-model). SAM Local can be used to test functions locally, start a local API Gateway from a SAM template, validate a SAM template, and generate sample payloads for various event sources.
* [claudia](https://github.com/claudiajs/claudia) - Claudia makes it easy to deploy Node.js projects to AWS Lambda and API Gateway. It automates all the error-prone deployment and configuration tasks, and sets everything up the way JavaScript developers expect out of the box. This means that you can get started with Lambda and API Gateway easily, and focus on solving important business problems instead of dealing with AWS deployment workflows.
* [cljs-lambda](https://github.com/nervous-systems/cljs-lambda) - Utilities around deploying Clojurescript functions to AWS Lambda.
* [docker-lambda](https://github.com/lambci/docker-lambda) - Docker images and test runners that replicate the live AWS Lambda environment
* [formplug-serverless](https://github.com/danielireson/formplug-serverless) - A form forwarding service for AWS Lambda that you can use to accept form submissions by email without server-side code.
* [iopipe-python](https://github.com/iopipe/iopipe-python) - This package provides analytics and distributed tracing for event-driven applications running on AWS Lambda.
* [iron-io/lambda](https://github.com/iron-io/lambda) - A set of tools, tests and libraries to convert Amazon AWS Lambda functions into Docker images that can run on any computer or cloud provider.
* [lambda-packager](https://github.com/lorenzoh/lambda-packager) - Uses the amazonlinux Docker image to build Python packages for AWS Lambda.
* [lambda-packages](https://github.com/Miserlou/lambda-packages) - Various popular python libraries, pre-compiled to be compatible with AWS Lambda. The best way to use these packages is with [Zappa](https://github.com/Miserlou/Zappa), which will automatically install the right packages during deployment, and do a million other useful things [https://blog.zappa.io](https://blog.zappa.io).
* [lambda-tester](https://github.com/vandium-io/lambda-tester) - Helper for unit testing AWS Lambda functions using Node.js
* [lambdaSH](https://github.com/alestic/lambdash) - Run shell commands inside AWS Lambda environment
* [webpack-aws-lambda-upload-plugin](https://github.com/sirceljm/webpack-aws-lambda-upload-plugin) - Zip and upload your AWS Lambda function directly from webpack.
