# Billing Alerts Template
This template creates 4 billing alerts with $5, $10, $20, and $40 thresholds. You have to provide an email address that you want the alerts to be sent to and the template automatically subscribes to the SNS topic(`BillingAlerts`). A subscription confirmation email will be sent out to the email address you provided.

### Resources
- AWS::SNS::Topic
- AWS::CloudWatch::Alarm