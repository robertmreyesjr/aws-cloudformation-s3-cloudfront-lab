# AWS CloudFormation S3 + CloudFront Lab

## Project Overview
This project demonstrates a small Infrastructure as Code (IaC) deployment using AWS CloudFormation. The stack provisions an Amazon S3 bucket and an Amazon CloudFront distribution to deliver a static website over HTTPS.

The goal of this lab was to practice deploying cloud infrastructure from code instead of building resources manually in the AWS Console. This project is relevant to Cloud Operations, Cloud Support, and Infrastructure roles because it shows repeatable deployment, basic CDN architecture, and AWS resource validation.

## What I Built
- A CloudFormation template that deploys:
  - an S3 bucket for website content
  - a CloudFront distribution for secure content delivery
- A simple static website
- Validation steps to confirm the stack deployed successfully and served content through CloudFront
- Cleanup steps to avoid unnecessary AWS charges

## Why I Built It
I built this project to strengthen my AWS portfolio after earning the AWS Certified Solutions Architect Associate (SAA-C03). I wanted a simple IaC lab that demonstrates practical cloud infrastructure skills in a low-cost way.

## AWS Services Used
- AWS CloudFormation
- Amazon S3
- Amazon CloudFront

## Architecture
- AWS CloudFormation deploys the infrastructure from a YAML template
- Amazon S3 stores the website files
- Amazon CloudFront serves the site over HTTPS and caches content closer to users

## Project Files
```text
aws-cloudformation-s3-cloudfront-lab/
├── README.md
├── build-steps.md
├── template.yaml
├── website/
│   ├── index.html
│   └── style.css
└── screenshots/
