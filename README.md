# AWS S3 Event Triggering

![Black Brown Geometric Motivational Desktop Wallpaper](https://github.com/DeoreRohit4/Shell_Script_Project_1/assets/102886808/49ce1f77-ae20-457f-864b-c87676dda11e)

This project demonstrates an automated workflow on AWS, designed to enhance real-time processing and notification systems through the integration of several AWS services, including S3, Lambda, SNS, and IAM. This setup creates a responsive and automated system triggered by specific user actions, with an emphasis on security and scalability. Below is a detailed overview of the workflow, components involved, and the automation techniques employed.

## Workflow

1. Image Upload Trigger: 

Action: Users upload an image to a designated Amazon S3 bucket.
Outcome: This upload event automatically triggers an AWS Lambda function.

2. Lambda Function Execution:

Process: Triggered by the S3 upload event, the Lambda function executes its code.
Task: It initiates an Amazon SNS (Simple Notification Service) alert to notify about the image upload.

3. SNS Notification:

Notification: Triggered by the Lambda function, Amazon SNS dispatches an email notification.
Recipients: The email is sent to predefined recipients, alerting them of the new image upload in the S3 bucket.

## Security and Permissions

1. AWS Identity and Access Management (IAM):
Roles and Permissions: Utilizes IAM roles to securely manage permissions, allowing the Lambda function to be invoked by S3 and to invoke the SNS topic for notifications.
Automation Details

2. Shell Scripting:
Deployment Automation: Utilizes Shell scripts to automate the deployment and configuration of AWS resources, ensuring a seamless setup process.

3. Python for Lambda:
Function Logic: Employs Python to define the logic within the AWS Lambda function, handling the triggering of SNS notifications upon image uploads. Python's versatility and the extensive support of AWS SDK make it an ideal choice for scripting Lambda function operations.
