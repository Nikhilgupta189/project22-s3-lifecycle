# Project 22: S3 Log Archive with Lifecycle

## Objective
Reduce storage costs by managing log retention using Amazon S3 lifecycle rules.

## Technologies Used
- Amazon S3
- AWS CLI
- Ubuntu Linux
- S3 Lifecycle Management

## Implementation
1. Created an S3 bucket in ap-south-1.
2. Created a sample application log file.
3. Uploaded the log file to the S3 bucket.
4. Created a lifecycle rule using lifecycle.json.
5. Configured automatic log expiration after 30 days.
6. Verified the lifecycle rule using AWS CLI.

## Lifecycle Configuration
- Rule name: project22-expire-logs
- Prefix: logs/
- Status: Enabled
- Expiration: 30 days

## Verification
Verified the uploaded log file and enabled S3 lifecycle rule.

## Conclusion
Successfully demonstrated automated log retention using Amazon S3 lifecycle management.
