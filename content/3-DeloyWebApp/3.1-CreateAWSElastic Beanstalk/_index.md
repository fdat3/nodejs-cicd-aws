---
title : "Create AWS Elastic Beanstalk"
date : "`r Sys.Date()`"
weight : 1
chapter : false
pre : " <b> 3.1 </b> "
---
## Create AWS Elastic Beanstalk

1. In a new browser tab, open the **AWS Elastic Beanstalk** console.
   - Click **Create Application** button

![Create Elastic Beanstalk](/images/3-Prerequiste/3.1-elastic-beanstalk/0001-elastic-beanstalk.png?featherlight=false&width=90pc)


2. In **Environment tier** section
   - Select **Web Server Enviroment**
![Create Elastic Beanstalk](/images/3-Prerequiste/3.1-elastic-beanstalk/0002-elastic-beanstalk.png?featherlight=false&width=90pc)

3. In **Application information**
   - Input your application name, enter **DevOpsGettingStarted**
![Create Elastic Beanstalk](/images/3-Prerequiste/3.1-elastic-beanstalk/0003-elastic-beanstalk.png?featherlight=false&width=90pc)

4. In **Platform**
   - Choose **Managed Platform**
   - Platform: **Nodejs**
   - Platform branch: **Node.js 20 running on 64bit Amazon Linux 2023**
   - Platform version: **6.1.1 (Recommended)**
![Create Elastic Beanstalk](/images/3-Prerequiste/3.1-elastic-beanstalk/0004-elastic-beanstalk.png?featherlight=false&width=90pc)

5. In **Application Code**:
   - Choose **Sample Application**
   - In **Preset**: Choose **Single instance**
   - Click **Next**
![Create Elastic Beanstalk](/images/3-Prerequiste/3.1-elastic-beanstalk/0005-elastic-beanstalk.png?featherlight=false&width=90pc)

6. On the **Configure service** access screen, choose Use an existing service role for Service Role
7. Choose **aws-elasticbeanstalk-ec2-role** in the Existing service role
8. In EC2 instance profile:
   - If **aws-elasticbeanstalk-ec2-role** displays in the dropdown list, select it from the EC2 instance profile dropdown list
   - If another value displays in the list, and it’s the default EC2 instance profile intended for your environments, select it from the EC2 instance profile dropdown list.
   - If the EC2 instance profile dropdown list doesn't list any values to choose from, expand the procedure that follows, [Create IAM Role](https://docs.aws.amazon.com/codedeploy/latest/userguide/getting-started-create-iam-instance-profile.html) for EC2 instance profile.
9. Choose **Skip to Review** on the Configure service access page
![Create Elastic Beanstalk](/images/3-Prerequiste/3.1-elastic-beanstalk/0006-elastic-beanstalk.png?featherlight=false&width=90pc)
10. In **Step 6: Review**, click **Submit**
![Create Elastic Beanstalk](/images/3-Prerequiste/3.1-elastic-beanstalk/0007-elastic-beanstalk.png?featherlight=false&width=90pc)