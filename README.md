# aws-cloud-security-lab
AWS Cloud Security Monitoring Lab using CloudTrail, GuardDuty, and IAM

AWS Cloud Security Monitoring Lab
Overview

This project demonstrates hands-on experience with AWS cloud security tools by building a monitoring environment that detects and analyzes suspicious activity.

**Technologies Used -**

AWS EC2

AWS S3

AWS IAM

AWS CloudTrail

AWS GuardDuty


**Architecture -**

EC2 instance deployed in AWS

S3 bucket used for log storage

CloudTrail enabled for account activity tracking

GuardDuty enabled for threat detection

IAM users created to simulate access scenarios


**What I Did -**

Configured AWS CloudTrail to log all account activity

Enabled GuardDuty to detect suspicious behavior

Created IAM users and simulated unauthorized access attempts

Analyzed CloudTrail logs to investigate activity

Initially assigned administrative access for testing, then removed it and enforced least privilege controls


**Key Learnings -**

How AWS logs and monitors account activity

How to detect potential threats in a cloud environment

The importance of IAM and least privilege access

Basics of cloud-based security investigation


**Screenshots- **

CloudTrail Logs <img width="2320" height="1016" alt="Screenshot 2026-03-26 144050" src="https://github.com/user-attachments/assets/8b73e818-f5a2-4575-871f-f5cf8083655b" />

GuardDuty <img width="2255" height="1141" alt="Screenshot 2026-03-26 144131" src="https://github.com/user-attachments/assets/30428ebe-5fab-45c2-b803-7e4f967d669b" />

IAM Users <img width="2281" height="1062" alt="Screenshot 2026-03-26 144552" src="https://github.com/user-attachments/assets/d0b1762c-0a70-4eec-aad4-c4d2c12a5d30" />

EC2 Instance <img width="2314" height="570" alt="Screenshot 2026-03-26 144658" src="https://github.com/user-attachments/assets/87c4267c-9338-480f-af1c-d60f8fb63898" />

S3 Bucket <img width="2270" height="425" alt="Screenshot 2026-03-26 144733" src="https://github.com/user-attachments/assets/1e8a57e0-51be-4d7c-967d-712584baf539" />


