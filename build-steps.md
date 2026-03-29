
## build-steps.md

```md
# Build Steps - AWS CloudFormation S3 + CloudFront Lab

## Lab Goal
Deploy a simple static website environment using AWS CloudFormation, Amazon S3, and Amazon CloudFront. Document the deployment process and capture screenshots for a GitHub portfolio project.

## Before You Start
Make sure you have:
- an AWS account
- access to the AWS Management Console
- a local project folder with:
  - `template.yaml`
  - `website/index.html`
  - `website/style.css`
  - a `screenshots/` folder for documentation

---

## Part 1 - Prepare the Project Files
Create a local folder for the lab.

Example folder structure:

```text
aws-cloudformation-s3-cloudfront-lab/
├── README.md
├── build-steps.md
├── template.yaml
├── website/
│   ├── index.html
│   └── style.css
└── screenshots/