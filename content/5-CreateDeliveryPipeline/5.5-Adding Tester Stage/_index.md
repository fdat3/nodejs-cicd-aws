---
title : "Adding Tester Stage"
date : "`r Sys.Date()`"
weight : 5
chapter : false
pre : " <b> 5.5 </b> "
---

## Adding Tester Stage

1. Now, go back to the [AWS CodePipeline Console](https://console.aws.amazon.com/codesuite/codepipeline/pipelines)
2. Click on your latest Pipeline, that's **Pipeline-DevOpsGettingStarted**
3. Click **Edit** button 
![Config The Deploy Stage](https://fdat3.github.io/nodejs-cicd-aws/images/5-CreateDeliveryPipeline/5.5-AddingTesterStage/0001-tester-stage.png)
4. Choose the white **Add stage** button between the **Build** and **Deploy stages**.
![Config The Deploy Stage](https://fdat3.github.io/nodejs-cicd-aws/images/5-CreateDeliveryPipeline/5.5-AddingTesterStage/0002-tester-stage.png)
5. Put **Tester** for **Stage name** and click **Add stage**
![Config The Deploy Stage](https://fdat3.github.io/nodejs-cicd-aws/images/5-CreateDeliveryPipeline/5.5-AddingTesterStage/0003-tester-stage.png)
6. Good job bro, **Tester Stage** is here !
![Config The Deploy Stage](https://fdat3.github.io/nodejs-cicd-aws/images/5-CreateDeliveryPipeline/5.5-AddingTesterStage/0004-tester-stage.png)
7. In the **Tester stage**, choose the white **Add action** group button.
8. Under **Action name**, enter **Manual_Test**.
9. From the **Action provider** dropdown, select **Manual approval**
10. Confirm that the optional fields have been left blank.
![Config The Deploy Stage](https://fdat3.github.io/nodejs-cicd-aws/images/5-CreateDeliveryPipeline/5.5-AddingTesterStage/0005-tester-stage.png)
11. Go to the **Top** and click **Save**
12. This is the **Application architecture** if you completed all the section in this workshop !
![Config The Deploy Stage](https://fdat3.github.io/nodejs-cicd-aws/images/5-CreateDeliveryPipeline/5.5-AddingTesterStage/0006-tester-stage.png)