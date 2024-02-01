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

## Screenshots

![Screenshot from 2024-01-23 11-29-07](https://github.com/DeoreRohit4/Shell_Script_Project_1/assets/102886808/b356f373-8619-41e6-b9cb-80fab44d4eb1)

![Screenshot from 2024-01-23 11-33-22](https://github.com/DeoreRohit4/Shell_Script_Project_1/assets/102886808/f676aa49-7553-4a3d-9519-4e573d85c44b)

![Screenshot from 2024-01-23 11-22-15](https://github.com/DeoreRohit4/Shell_Script_Project_1/assets/102886808/059f05e7-b78d-4ca1-859c-ccf5e4aabb0c)

![Screenshot from 2024-01-23 12-05-01](https://github.com/DeoreRohit4/Shell_Script_Project_1/assets/102886808/136fe88f-2bb9-4725-bf2b-ca51a1ffdfb9)

![Screenshot from 2024-01-23 12-05-47](https://github.com/DeoreRohit4/Shell_Script_Project_1/assets/102886808/b82b849b-4d82-4821-95be-cb4012797b88)

![Screenshot from 2024-01-23 12-06-51](https://github.com/DeoreRohit4/Shell_Script_Project_1/assets/102886808/a4cce80e-17bc-4b27-a1e9-28ab2a2bb87f)

![Screenshot from 2024-01-23 12-07-30](https://github.com/DeoreRohit4/Shell_Script_Project_1/assets/102886808/4457eafe-a0b8-47ac-8c72-811561395683)

![Screenshot from 2024-01-23 12-09-49](https://github.com/DeoreRohit4/Shell_Script_Project_1/assets/102886808/c3cab6ce-4467-4bc4-bd94-dbdebb683e42)

![Screenshot from 2024-01-23 12-10-18](https://github.com/DeoreRohit4/Shell_Script_Project_1/assets/102886808/606a7dd2-8795-4520-9f76-435b04d4bf54)

![Screenshot from 2024-01-23 11-34-29](https://github.com/DeoreRohit4/Shell_Script_Project_1/assets/102886808/8aec9f02-76a5-4e7f-930a-8fd38bcd5a8d)

![Screenshot from 2024-01-23 11-34-14](https://github.com/DeoreRohit4/Shell_Script_Project_1/assets/102886808/ef7f9aed-726e-44b9-9297-3658b88027e4)
