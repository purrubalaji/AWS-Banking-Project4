🏦 AWS Final Project – Secure Banking System


Overview: This project demonstrates a secure, scalable cloud-based banking system built using AWS services. It simulates core banking functionalities such as account creation, secure transactions, user authentication, and financial reporting—tailored for both educational and practical deployment scenarios.

🔧 Technologies & AWS Services Used:

EC2 & Load Balancer: Hosts Flask-based banking application with autoscaling and high availability.

IAM: Fine-grained access control for user and admin roles with MFA.

RDS (MariaDB): Stores account, transaction, and customer data in a secure, encrypted database.

S3: Used for hosting static content and secure backups.

VPC: Ensures network isolation with public/private subnets, NAT gateways, and routing tables.

EFS: Shared file storage for logs and uploads, mounted across multiple EC2 instances.

CloudFront & Route 53: Distribute content globally and manage secure DNS routing.

CloudWatch & SNS: Monitor system performance and send alerts on suspicious activity.

🔒 Security Highlights:

Enforced IAM best practices with least privilege and MFA.

Encrypted communication via HTTPS and secure storage in RDS and S3.

Monitored user behavior and transaction anomalies through custom CloudWatch metrics.

📊 Functional Modules:

User Registration & Login with OTP and Password policies

Account Management (creation, balance inquiry, history)

Fund Transfers (internal & inter-bank simulation)

Admin Dashboard for reporting and auditing

🌱 Future Enhancements:

Integrate Amazon Cognito for advanced user pool management

Deploy fraud detection model using SageMaker

Implement real-time notification via Amazon Pinpoint or Twilio
