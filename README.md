# LambStatus

[![Launch CloudFormation Stack](https://s3.amazonaws.com/cloudformation-examples/cloudformation-launch-stack.png)](https://console.aws.amazon.com/cloudformation/home#/stacks/new?stackName=StatusPage&templateURL=https://s3-ap-northeast-1.amazonaws.com/lambstatus/cf-template/0.6.6/lamb-status.yml)
[![API Document](https://img.shields.io/badge/api-v0-blue.svg)](https://bitpesa.github.io/LambStatus-apidocs/)

LambStatus is the serverless status page system. [See our website](https://bitpesa.github.io/LambStatus-website/) for features.

## Get Started

See [the getting started page](https://bitpesa.github.io/LambStatus-website/get-started) to build your first status page with just a few clicks!

## Goals of this project

* Offers an open source and serverless status page system.
* Offers a pay-as-you-go pricing approach like AWS. We estimate the system takes just *$1 to handle 30,000 visitors* ([see details](https://bitpesa.github.io/LambStatus-website/cost-estimate)).
* Enables you to build and maintain the status page system with minimum effort.

## Why Serverless?

Status page system is great with the Serverless architecture, because:

* It eases your pain caused by the scaling / availability issues. It is terrible if your service is down AND heavy traffic from stuck users stops your status page.
* It enables you to pay only for what you use. A status page only occasionally gets huge traffic. The system takes only $1 per 30,000 visitors and almost $0 if no visitors.
