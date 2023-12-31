# Scripts

## AWS Lambda Function for Monitoring SSH Attempts
#### Description
This AWS Lambda function demonstrates a use case of monitoring SSH attempts within an Amazon Web Services (AWS) environment. The function is triggered by AWS CloudTrail events and uses Amazon Simple Notification Service (SNS) to notify administrators about SSH attempts originating from specific IP addresses.

#### What is This Script?
This script is an AWS Lambda function designed to be triggered by CloudTrail events. It monitors CloudTrail logs for specific events and conditions, such as detecting SSH attempts using the 'RunInstances' event and a specific security group. When an SSH attempt is detected, the Lambda function sends a notification to an SNS topic, alerting administrators about the potential security threat.

#### Why Use This Script?
The purpose of this script is educational and informative. It showcases how to use AWS services such as Lambda, CloudTrail, and SNS to enhance security by detecting and responding to suspicious activity. This script provides insights into how to automate security monitoring in an AWS environment, helping administrators to improve incident response and safeguard their infrastructure.

## Boto3 Script for AWS EC2 Instance Information
#### Description
This Python script demonstrates the use of the Boto3 library to interact with Amazon Web Services (AWS) EC2 instances. It specifically focuses on retrieving information about EC2 instances running on an Ubuntu server using its private IP address.

#### What is This Script?
This script is a simple example that showcases how to use the Boto3 library to interact with AWS services, specifically Amazon EC2. The script connects to AWS using your provided AWS access key and secret key, and retrieves information about EC2 instances based on a specified private IP address. It is intended to illustrate basic interactions with AWS services and provide a foundation for further development.

#### Why Use This Script?
The purpose of this script is educational and informational. It is intended for those interested in learning about AWS automation, Boto3 library usage, and scripting with Python. By studying this script, you can gain insights into how to retrieve data from AWS EC2 instances programmatically.

# Disclaimer
## Important: 
This script is provided for educational and informational purposes only. It is not intended for any malicious or unauthorized activities, including but not limited to hacking, penetration testing, or any other unauthorized access to computer systems. The script should only be used legally and responsibly, in compliance with all applicable laws and regulations. It is essential to use this script to improve security measures and enhance your understanding of AWS services, without violating any terms of use or policies set by AWS or any other relevant entity.

Please ensure that you have the appropriate authorization and permissions before using this script. The authors and contributors of this script are not responsible for any misuse, damage, or legal consequences that may arise from the use of this script.

## Links for Scripts
[Boto3 Script for AWS EC2 Instance](https://github.com/SilverLine-Security/Scripts/blob/main/describeInstance.py)

[Lambda SSH SCRIPT](https://github.com/SilverLine-Security/Scripts/blob/main/Lambda-ssh-script.py)

