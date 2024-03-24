---
title : "Clean up resources"
date : "`r Sys.Date()`"
weight : 6
chapter : false
pre : " <b> 6. </b> "
---
### Delete AWS Elastic Beanstalk Application

1. In a new browser window, open the [AWS Elastic Beanstalk Console](https://us-west-2.console.aws.amazon.com/elasticbeanstalk)
2. In the left navigation menu, click on "Applications." You should see the "DevOpsGettingStarted" application listed under "All applications."
3. Select the radio button next to "DevOpsGettingStarted."
![Clean up](/images/6-cleanup/0001-clean-up.png)


### Delete AWS Code Pipeline

1. In a new browser window, open the [AWS Code Pipelines Console](https://console.aws.amazon.com/codesuite/codepipeline/pipelines)
2. Select the radio button next to **"Pipeline-DevOpsGettingStarted."**
3. Click the white "Delete pipeline" button at the top of the page.
![Clean up](/images/6-cleanup/0002-clean-up.png)

### Delete AWS S3 Bucket

1. In a new browser window, open the [AWS S3 Bucket](https://s3.console.aws.amazon.com/s3/home)
2. You should see a bucket named **"codepipeline-us-west-2"** followed by your AWS account number. Click on this bucket. Inside this bucket, you should see a folder named **"Pipeline-DevOpsGettingStarted."**
![Clean up](/images/6-cleanup/0003-clean-up.png)
![Clean up](/images/6-cleanup/0004-clean-up.png)

### Delete AWS Code Build

1. In a new browser window, open the [AWS Code Build](https://console.aws.amazon.com/codesuite/codebuild)
2. In the left navigation, click on **"Build project**s" under **"Build."** You should see the **"Build-DevOpsGettingStarted"** build project listed under **"Build project."**
3. Select the radio button next to **"Build-DevOpsGettingStarted."**
![Clean up](/images/6-cleanup/0005-clean-up.png)
