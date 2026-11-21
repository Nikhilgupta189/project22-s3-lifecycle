# Project 22: S3 Log Archive with Lifecycle

## Objective
Reduce storage costs by automatically expiring old log files stored in Amazon S3.

## Technologies Used
- Amazon S3
- AWS CLI
- S3 Lifecycle Management
- Ubuntu Linux

## Implementation
1. Created a dedicated S3 bucket in the Mumbai region.
2. Created a sample application log file.
3. Uploaded the log file to the `logs/` prefix in S3.
4. Created an S3 lifecycle configuration.
5. Configured expiration of log objects after 30 days.
6. Verified that the lifecycle rule was enabled.
7. Captured screenshots of the uploaded logs and lifecycle rule.

## Lifecycle Configuration
- Rule name: `project22-expire-logs`
- Prefix: `logs/`
- Status: Enabled
- Expiration: 30 days

## Conclusion
Successfully configured Amazon S3 lifecycle management to automatically expire old log files, demonstrating automated storage management and retention control.
