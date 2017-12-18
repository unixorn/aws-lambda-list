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
  - [python-lambda](#python-lambda)
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

A serverless web framework for Node.js on AWS (CloudFormation, CloudFront, API Gateway, Lambda) [https://dawson.sh](https://dawson.sh)

### [python-lambda](https://github.com/nficano/python-lambda)

A toolkit for developing and deploying serverless Python code in AWS Lambda. The Python-Lambda library takes away the guess work of developing your Python-Lambda services by providing you a toolset to streamline the annoying parts.

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
* [binaryalert](https://github.com/airbnb/binaryalert) - Serverless, Real-time & Retroactive Malware Detection.
* [chaos-lambda](https://github.com/shoreditch-ops/chaos-lambda) - A Serverless implementation of Netflix's [Chaos Monkey](https://github.com/Netflix/SimianArmy/wiki/Chaos-Monkey) for AWS (runs on AWS Lambda).
* [chef-node-cleanup](https://github.com/awslabs/lambda-chef-node-cleanup) - Automatically Delete Terminated Instances in Chef Server with AWS Lambda when triggered by CloudWatch instance termination events.
* [ddns-function](https://github.com/awslabs/aws-lambda-ddns-function) - Dynamically create Route 53 resource records using CloudWatch Events and Lambda.
* [ecs-host-service-scale](https://github.com/miketheman/ecs-host-service-scale) - Lambda function to ensure an ECS Service is set to the correct Desired Count for a One-Task-Per-Host placement value for any cluster that runs the Service.
* [honeyλ](https://github.com/0x4D31/honeyLambda) - A simple, serverless application designed to create and monitor fake HTTP endpoints (i.e. URL honeytokens) automatically, on top of AWS Lambda and Amazon API Gateway.
* [hugo-lambda](https://github.com/ryansb/hugo-lambda) - Use AWS Lambda to run the Hugo static site generator.
* [lambda-comments](https://github.com/jimpick/lambda-comments) - Blog commenting system built with AWS Lambda, API Gateway, S3, DynamoDB streams, IAM and CloudWatch Logs.
* [lambda-packs](https://github.com/ryfeus/lambda-packs) - Precompiled packages for Lambda.
* [lambdaproxy](https://github.com/dan-v/awslambdaproxy) - Lambda powered HTTP/SOCKS web proxy.
* [LambdAuth](https://github.com/danilop/LambdAuth) - Sample authentication service implemented with a server-less architecture, using AWS Lambda to host and execute the code and Amazon DynamoDB as persistent storage. This provides a cost-efficient solution that is scalable and highly available and can be used with Amazon Cognito for Developer Authenticated Identities.
* [letsencrypt](https://github.com/ubergeek42/lambda-letsencrypt) - Use [AWS Lambda](https://aws.amazon.com/lambda/) to manage SSL certificates for any site that uses [Amazon's CloudFront CDN](https://aws.amazon.com/cloudfront/).
* [node-letsencrypt-lambda](https://github.com/ocelotconsulting/node-letsencrypt-lambda) - Use AWS Lambda to manage SSL certificates for Lets-Encrypt.
* [pricing-tools](https://github.com/concurrencylabs/aws-pricing-tools) - A Lambda function that calculates near real-time price of an account's infrastructure including EC2, ELB, EBS, RDS, Lambda, Dynamo DB and Kinesis resources.
* [reaper-lambda](https://github.com/gabinante/reaper-lambda) - Reaps any and all instances which are not tagged with an expiration date.
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
* [cljs-lambda](https://github.com/nervous-systems/cljs-lambda) - Utilities around deploying Clojurescript functions to AWS Lambda.
* [docker-lambda](https://github.com/lambci/docker-lambda) - Docker images and test runners that replicate the live AWS Lambda environment
* [iron-io/lambda](https://github.com/iron-io/lambda) - A set of tools, tests and libraries to convert Amazon AWS Lambda functions into Docker images that can run on any computer or cloud provider.
* [lambda-packages](https://github.com/Miserlou/lambda-packages) - Various popular python libraries, pre-compiled to be compatible with AWS Lambda. The best way to use these packages is with [Zappa](https://github.com/Miserlou/Zappa), which will automatically install the right packages during deployment, and do a million other useful things [https://blog.zappa.io](https://blog.zappa.io).
* [lambda-tester](https://github.com/vandium-io/lambda-tester) - Helper for unit testing AWS Lambda functions using Node.js
* [lambdaSH](https://github.com/alestic/lambdash) - Run shell commands inside AWS Lambda environment
* [webpack-aws-lambda-upload-plugin](https://github.com/sirceljm/webpack-aws-lambda-upload-plugin) - Zip and upload your AWS Lambda function directly from webpack.
