# AWS-High-Availability-Architecture-with-AWS-CLI

For creating this High Level Architecture we have to follow these specified steps:-

Step 1 : Webserver Configured on **EC2 instance**.

Step 2 : Goto Document root of the Webserver *(/var/www/html)*

Step 3: Made persistent by mounting on **EBS** Block Device.

Step 4: Static objects in webserver such as some files, images etc stored in **S3**.

Step 5: Setting up **CDN** using cloud front service and using the origin domain as **S3 bucket**.

Step 6: Finally put the **CloudFront URL** as the object address in the code for security and Low Latency.

These 6 steps we are going to performed in order to create this High level Architecture.

For Implementation part refer my [linkedin post] (https://www.linkedin.com/posts/anurag-vashishth-7b7bb8156_aws-awscloud-awscsa-activity-6747947352641851393-zYb2)
