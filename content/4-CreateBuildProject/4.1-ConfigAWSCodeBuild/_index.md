---
title : "Config AWS CodeBuild"
date : "`r Sys.Date()`"
weight : 1
chapter : false
pre : " <b> 4.1 </b> "
---

## Config AWS Code Build

1. In the Project name field, enter **Build-DevOpsGettingStarted**.
![Config AWS Code Build](/images/4-CreateBuildProject/4.1-configawscodebuild/0001-code-build.png)
2. Select GitHub from the Source provider dropdown menu.
3. Confirm that the Connect using OAuth radio button is selected.
4. Choose the white Connect to GitHub button. A new browser tab will open asking you to give AWS CodeBuild access to your GitHub repo.
5. Choose the green Authorize aws-codesuite button.
6. Enter your GitHub password.
7. Choose the orange Confirm button.
8. Select Repository in my GitHub account.
9. Enter **aws-elastic-beanstalk-express-js-sample** in the search field.
![Config AWS Code Build](/images/4-CreateBuildProject/4.1-configawscodebuild/0002-code-build.png)
10. Confirm that **Managed Image** is selected.
11. Select **Amazon Linux 2** from the **Operating system** dropdown menu.
12. Select **Standard** from the **Runtime(s)** dropdown menu.
13. Select **aws/codebuild/amazonlinux2-x86_64-standard:3.0** from the Image dropdown menu.
14. Confirm that **Always use the latest image for this runtime version is selected for Image version.**
15. Confirm that **New service role** is selected.
![Config AWS Code Build](/images/4-CreateBuildProject/4.1-configawscodebuild/0003-code-build.png)