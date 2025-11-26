## AWS Developer Associate mock questions

🚀 1. S3 & Storage
Q1.

Your application uploads files to an S3 bucket. Users should only have temporary access to download the files.
What should you use?

A. IAM User credentials
B. Public bucket policy
C. Generate a presigned URL
D. S3 access logs

Q2.

An S3 bucket is used for storing logs. The cost is increasing. Logs are rarely accessed after 30 days. What is the best cost optimization strategy?

A. Move data to DynamoDB
B. Create an S3 lifecycle rule to transition to Glacier after 30 days
C. Delete logs after 30 days
D. Enable S3 encryption

⚙️ 2. Lambda & Serverless
Q3.

A Lambda function fails due to running longer than allowed. What should you do?

A. Increase memory
B. Increase timeout value
C. Use EC2 instead
D. Reduce concurrency

Q4.

You want to avoid Lambda cold starts. Which approach helps?

A. Decrease memory
B. Enable Provisioned Concurrency
C. Disable VPC
D. Reduce the number of Lambda functions

🔐 3. Security & IAM
Q5.

A developer needs programmatic access only for DynamoDB and S3. You should:

A. Give AdministratorAccess
B. Give AmazonS3FullAccess only
C. Create custom IAM policy with least privilege
D. Attach PowerUserAccess

Q6.

An application deployed on EC2 needs to access S3 securely. What's the best practice?

A. Store AWS credentials in EC2 user data
B. Use IAM Role attached to EC2
C. Use access keys in config file
D. Use AWS Systems Manager Parameter Store

📡 4. API & Integration
Q7.

A REST API using API Gateway and Lambda should handle high traffic while reducing latency. What should you enable?

A. Long polling
B. API Gateway caching
C. Multi-region deployment
D. SQS integration

Q8.

To process tasks asynchronously and retry automatically after failure, you use:

A. SNS
B. Step Functions
C. SQS
D. EventBridge Scheduler

🧪 5. Development & CI/CD
Q9.

You want to automate unit tests and deployment of Lambda functions when code is pushed to Git. Which AWS service is most suitable?

A. AWS Batch
B. Elastic Beanstalk
C. AWS CodePipeline + CodeBuild
D. AWS Config

Q10.

Which tool helps detect security vulnerabilities in application code in CI/CD pipeline?

A. AWS GuardDuty
B. Amazon CodeGuru Reviewer
C. AWS Inspector
D. AWS Trusted Advisor

🔄 6. DynamoDB
Q11.

A mobile app frequently reads data but rarely writes. What DynamoDB mode is recommended?

A. On-demand
B. Provisioned with AutoScaling
C. Always on-demand and autoscaling
D. Manual scaling

Q12.

What method improves performance by caching DynamoDB reads?

A. S3 Sync
B. Elasticache with Redis
C. DynamoDB Accelerator (DAX)
D. Use SQS

🧵 7. SNS, SQS & EventBridge
Q13.

To send notifications to both email and SMS, which service should you use?

A. SQS
B. EventBridge
C. Lambda
D. SNS

Q14.

To ensure no message is lost even if the consumer fails temporarily, use:

A. SNS
B. SQS Standard Queue
C. SQS FIFO Queue
D. Lambda DLQ

🔍 8. Monitoring & Troubleshooting
Q15.

Which AWS service allows debugging distributed systems such as microservices?

A. CloudTrail
B. AWS X-Ray
C. CloudWatch Logs only
D. Config

Q16.

Which service is best for tracking API call history for audit?

A. X-Ray
B. CloudTrail
C. Kinesis
D. ALB Logs
