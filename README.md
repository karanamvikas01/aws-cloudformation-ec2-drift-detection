# AWS CloudFormation EC2 Drift Detection Project

## 📖 Overview
This project demonstrates the use of **AWS CloudFormation** to provision and manage infrastructure as code. The focus is on creating an EC2 instance with attached EBS volumes, modifying resources outside of CloudFormation, and verifying changes using **drift detection**.

## 🚀 What Was Done
- Created an **EC2 instance** using a CloudFormation template.
- Launched the instance under the **default VPC** and **default security groups**.
- Provisioned **two EBS volumes** attached to the EC2 instance via the template.
- Modified one EBS volume manually using the **AWS Management Console**.
- Ran **drift detection** to identify differences between the CloudFormation stack and the actual resources.
- Verified and viewed the drift detection results.

## 🎯 Key Learnings
- Hands-on experience with **Infrastructure as Code (IaC)** using CloudFormation.
- Learned how **default networking configurations** (VPC and security groups) work in AWS.
- Understood how **EBS volumes** can be provisioned and managed through CloudFormation.
- Explored the concept of **drift detection** and how it helps maintain infrastructure consistency.
- Reinforced the importance of monitoring and managing changes outside of CloudFormation.

## 🛠️ Technologies Used
- **AWS CloudFormation**
- **Amazon EC2**
- **Amazon EBS**
- **AWS Management Console**

## 📊 Results
- Successfully detected and verified drift when manual changes were made to an EBS volume.
- Demonstrated how CloudFormation ensures infrastructure consistency and highlights discrepancies.

