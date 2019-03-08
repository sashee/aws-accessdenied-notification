# aws-accessdenied-notification

Sends a notification to an SNS topic whenever an Access Denied happens in your account.

Requires CloudTrail integration with CloudWatch logs (see how).

Deploy the provided template and supply the log group where CloudTrail writes the config along with the SNS topic. You'll get notified whenever an operation is denied (with a delay of ~15 minutes).
