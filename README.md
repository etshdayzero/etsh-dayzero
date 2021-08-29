## Introduction
This repository contains the source programs for the Ellipsis Tech Series Hackathon 2021 (ETSH).

## Directories
There are multiple directories:
- `ETSH-deep-learning/` for training Deep Learning models for credit score percentile prediction
- `ETSH-flask` for dynamic real-time API and model prediction
- `ETSH-react-app` for 
- `ETSH-terraform` for Terraform infrastructure as code, for deploying AWS service infrastructure onto the cloud

## Deployment Instructions
Documentation linked because instructions are necessarily complex, and require multiple steps including setting up AWS accounts, IAM policies, etc 
- React app deployed using S3 and CloudFront: aws.amazon.com/premiumsupport/knowledge-center/cloudfront-serve-static-website
- Terraform: ensure AWS IAM credentials are added, then deploy Terraform infrastructure
- Deep Learning: model training

## Team Members
Richard Ng, Min Yuan, Ryan Tan, Lee Yu Hao, Aw Khai Loong

## Attribution and Documentation
- Terraform documentation: terraform.io
- AWS documentation: docs.aws.amazon.com
- Flask documentation: flask-doc.readthedocs.io
- React component styling: github.com/timcreative
