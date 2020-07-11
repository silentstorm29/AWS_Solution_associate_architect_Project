# AWS_Solution_associate_architect_Project
## Introduction
Scenario
You have been asked to set up a WordPress blog for your company per their defined specifications.
During business hours (9AM-6PM), the blogging team would like to use their own development copy of the WordPress instance, so that any work they are doing doesn’t impact the live copy.
You plan to achieve these goals using Amazon CloudFormation, creating a new AMI and Auto Scaling.
Goals of the project
 Use CloudFormation to create an EC2 instance to run WordPress with the following specification:
o Instance Type: T2.micro
 Create a new AMI of the WordPress instance.
 Configure Auto Scaling to launch a new WordPress instance during 9AM-6PM