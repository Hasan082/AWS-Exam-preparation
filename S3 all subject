## AWS S3 & CLI Practical Study Guide

# AWS S3 & CLI Practical Study Guide – For AWS Developer Role & DVA-C02 Exam

## 1. Set Up & Identity
| Task | Command |
|------|---------|
| Check AWS Identity | aws sts get-caller-identity |
| List current region | aws configure get region |
| Change default region | aws configure set region us-east-1 |

## 2. S3 Bucket Operations
### Bucket Management
aws s3api create-bucket --bucket my-unique-name --region us-east-1
aws s3 ls
aws s3api delete-bucket --bucket my-unique-name

### File Upload & Download
aws s3 cp file.txt s3://my-bucket/
aws s3 cp s3://my-bucket/file.txt ./downloaded-file.txt

### Sync folder
aws s3 sync ./local-folder s3://my-bucket/

## 3. Bucket Security
aws s3api put-bucket-policy --bucket my-bucket --policy file://policy.json

## 4. Lifecycle Rules
aws s3api put-bucket-lifecycle-configuration --bucket my-bucket --lifecycle-configuration '{ ... }'

## 5. Versioning & Encryption
aws s3api put-bucket-versioning --bucket my-bucket --versioning-configuration Status=Enabled
aws s3api put-bucket-encryption --bucket my-bucket --server-side-encryption-configuration '{ ... }'

## 6. Presigned URL
aws s3 presign s3://my-bucket/file.txt --expires-in 3600

## 7. Bash Script Sample
#!/bin/bash
BUCKET="myapp-bucket-$(date +%s)"
aws s3api create-bucket --bucket $BUCKET --region us-east-1
aws s3 cp test.txt s3://$BUCKET/

## 8. Common Exam Practice
- Lifecycle
- Security
- Presigned URLs
- Sync folders

## 9. Developer Scenarios
- Logging
- Static website
- Temporary uploads
- CI/CD

## 10. Checklist
[ ] Created bucket
[ ] Uploaded file
[ ] Enabled versioning
[ ] Encryption
[ ] Lifecycle
[ ] Presigned URL
[ ] Sync
[ ] Script
[ ] Policy
[ ] App use-case

