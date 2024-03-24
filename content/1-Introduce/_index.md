---
title : "Introduction"
date :  "`r Sys.Date()`" 
weight : 1 
chapter : false
pre : " <b> 1. </b> "
---

## Introduction to Create Continuous Delivery Pipeline

Creating a Continuous Delivery (CD) pipeline using AWS services and GitHub involves several steps to automate the process of code deployment. Here's a brief introduction to setting up such a pipeline:

1. **Source Stage**: Your code resides in a GitHub repository, which acts as the source. Any change to the code triggers the pipeline.

2. **Build Stage**: AWS CodeBuild compiles your source code, runs tests, and produces software packages that are ready to deploy.

3. **Deploy Stage**: AWS Elastic Beanstalk takes the build artifacts from CodeBuild and deploys them to an environment, handling the deployment details.

4. **Pipeline Orchestration**: AWS CodePipeline automates the workflow from code update to deployment. It connects to GitHub, triggers CodeBuild projects, and deploys using Elastic Beanstalk.

Here's a high-level overview of the steps involved:

- **Connect GitHub to CodePipeline**: Set up a webhook in GitHub to trigger your pipeline on a commit.
- **Set up CodeBuild**: Define build specifications and connect it to your pipeline.
- **Configure Elastic Beanstalk**: Prepare your environment for deployment and set it as the target for CodeBuild artifacts.
- **Create the Pipeline**: Use AWS CodePipeline to orchestrate the process, defining each stage and action based on the above services.

For detailed instructions, AWS provides comprehensive guides and documentation¹. Remember, you'll need appropriate IAM roles and permissions set up for these services to interact with each other securely.

## Contents

- [AWS Code Build](1.1-awscodebuild/)
- [AWS Code Pipeline](1.2-awscodepipeline/)
- [AWS Elastic Beanstalk](1.3-elasticbeanstalk/)