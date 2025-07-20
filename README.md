# lab3-iam-role-instance-profile
Lab 3: Created and attached an IAM Role to an EC2 Instance Profile to grant secure, credential-free S3 access, following AWS best practices.
## 📝 Description

In this lab, I configured an IAM Role and attached it to an EC2 Instance Profile to securely grant my EC2 instance read-only access to Amazon S3, without using hardcoded credentials. 

This lab demonstrates AWS best practices for cloud security, including the Principle of Least Privilege (POLP) and proper use of IAM trust relationships.

I also practiced troubleshooting Security Group inbound rules, SSH access, and validated successful role-based access using `aws s3 ls` from within the instance.

