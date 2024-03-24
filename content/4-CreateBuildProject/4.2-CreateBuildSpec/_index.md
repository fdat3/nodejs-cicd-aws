---
title : "Create Build Spec"
date : "`r Sys.Date()`"
weight : 2
chapter : false
pre : " <b> 4.2 </b> "
---

## Create Build Spec

1. In **Buildspec** section
![Config AWS Code Build](https://fdat3.github.io/nodejs-cicd-aws/images/4-CreateBuildProject/4.1-configawscodebuild/0004-code-build.png)
2. Select **Insert Build Commands**
3. Copy this code:
```yaml
   version: 0.2
   phases:
      build:
         commands:
            - npm i --save
   artifacts:
   files:
         - '**/*'
```
![Config AWS Code Build](https://fdat3.github.io/nodejs-cicd-aws/images/4-CreateBuildProject/4.1-configawscodebuild/0005-code-build.png)
4. Click **Create Application** in the bottom.