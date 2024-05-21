#AWS-Lambda-SQS-Project
![image](https://github.com/kaivalya-tolbande/AWS-Lambda-SQS-Project/assets/110324856/c7a38f78-912b-45c3-8a7c-1b57f897b5be)


In this project, I will be creating an S3 bucket, Queue, and Lambda function. Whenever an object is uploaded in the S3 bucket, an S3 event will trigger the queue and the lambda function will run which will check if the object name contains the word "sensitive" If so it will send an email notification to the team saying some sensitive file is added in the bucket.

Prerequisite:

AWS account and familiarity with AWS services
