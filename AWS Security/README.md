List of assignments:

- **Security Policies**
  - Use resource policies and IAM policies to restric access to AWS resources
  - Explain the differences and uses of resource policies and IAM policies
  - Explain the components of IAM policies


- **Identity & Access management**
  - Describe the different elements of an IAM policy document
  - Apply dynamic I am policies by using policy variables
  - Explain how IAM user groups and IAM rules can facilitate access management
  - Describe how to configure the awcli by using IIM access keys


- **Compliance enforcement**
  - Create an automation document within AWS system manager
  - Deploy AWS config and an AWS config Rule (require-tags)
  - Configure manual remediation
  - Remediate the HR app server instance
    - Create a new automation document within AWS systems manager
    - Deploy a new AWS config rule (ec2-instance-profile-attached)
    - Apply any remediation required to make the HR web server instance fully complaint


- **Incident Response**
  Concept: In this lab you will learn how to:
   - Explain the concept of infrastructure domain incidents. Configure your application systems to log events to Amazon CloudWatch.
   - Review the steps that can be taken when malicious activity is detected.
   - Demonstrate how Amazon Cloudwatch alarms, Amazon SNS topic and AWS Lambda functions can be integrated to isolate AWS resources.
   - Configure Amazon SNS notifications to notify stakeholders regarding the status of isolation actions.
   - Install and configure the Amazon CloudWatch agent
   - Create a CloudWatch logs metric filter.
   - Ceate an Amazon cloudwatch alarm and SNStopic
   - Configure an SNS Topic to trigger an AWS Lambda function


- **Application Logs**
   Concept: In this lab you will: 
  - Configure the Amazon kinesis Agent to send access log data to an Amazon Kinesis Data Firehose Delivery stream configured with an Amazon S3 bucket destination.
  - Use AWS Glue to create an AWS Glue crawler to crawl the logs from S3 and generate a data schema. Use Amazon Athena to query and analyse the log data
  - Configure the Amazon kinesis agent on an Amazon EC2 instance
  - Create an AWS glue crawler to generate a data schema
  - Amazon Athena to query an analyse the log data

- **Infrastructure as Code**
  - Learn about provisioning resources with Cloudformation
  - Review the concept of drift detection in Cloudformation
  - Examine using a lambda function to remediate drift
   In this solution, a template stored in Amazon Simple Storage Service (Amazon S3) bucket is used by AWS Cloudformation to deploy and manage a stack. A stack is a collection of AWS resources that you can manage as a single unit. Any changes made to the stack will be detected and remediated by an AWS Lambda function.
