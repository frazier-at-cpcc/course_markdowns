# Developing Serverless Solutions on AWS

**Product ID**: 25376
**Category ID**: nan
**Modality**: 1
**Active**: True
**Language**: en
**Product Code**: AWSDEVSS
**Vendor Code**: AW
**Vendor Name**: Amazon Web Services
**URL**: [Course Link](https://www.fastlaneus.com/course/amazon-awsdevss)

## Objective
- Apply event-driven best practices to a serverless application design using appropriate AWS services
- Identify the challenges and trade-offs of transitioning to serverless development, and make recommendations that suit your development organization and environment
- Build serverless applications using patterns that connect AWS managed services together, and account for service characteristics, including service quotas, available integrations, invocation model, error handling, and event source payload
- Compare and contrast available options for writing infrastructure as code, including AWS CloudFormation, AWS Amplify, AWS Serverless Application Model (AWS SAM), and AWS Cloud Development Kit (AWS CDK)
- And much more

## Essentials
- Familiarity with the basics of AWS Cloud architecture
- An understanding of developing applications on AWS equivalent to completing the Developing on AWS (AWSD) classroom training
- Knowledge equivalent to completing the following serverless digital trainings: AWS Lambda Foundations and Amazon API Gateway for Serverless Applications

## Audience
Developers who have some familiarity with serverless architecture and experience with development in the AWS Cloud.

## Outline
Module 0: Introduction


- Introduction to the application you will build
- Access to course resources (Student Guide, Lab Guide, and Online Course Supplement)
Module 1: Thinking Serverless


- Best practices for building modern serverless applications
- Event-driven design
- AWS services that support event-driven serverless applications
Module 2: API-Driven Development and Synchronous Event Sources


- Characteristics of standard request/response API-based web applications
- How Amazon API Gateway fits into serverless applications
- Try-it-out exercise: Set up an HTTP API endpoint integrated with a Lambda function
- High-level comparison of API types (REST/HTTP, WebSocket, GraphQL)
Module 3: Introduction to Authentication, Authorization, and Access Control


- Authentication vs. Authorization
- Options for authenticating to APIs using API Gateway
- Amazon Cognito in serverless applications
- Amazon Cognito user pools vs. federated identities
Module 4: Serverless Deployment Frameworks


- Overview of imperative vs. declarative programming for infrastructure as code
- Comparison of CloudFormation, AWS CDK, Amplify, and AWS SAM frameworks
- Features of AWS SAM and the AWS SAM CLI for local emulation and testing
Module 5: Using Amazon EventBridge and Amazon SNS to Decouple Components


- Development considerations when using asynchronous event sources
- Features and use cases of Amazon EventBridge
- Try-it-out exercise: Build a custom EventBridge bus and rule
- Comparison of use cases for Amazon Simple Notification Service (Amazon SNS) vs. EventBridge
- Try-it-out exercise: Configure an Amazon SNS topic with filtering
Module 6: Event-Driven Development Using Queues and Streams


- Development considerations when using polling event sources to trigger Lambda functions
- Distinctions between queues and streams as event sources for Lambda
- Selecting appropriate configurations when using Amazon Simple Queue Service (Amazon SQS) or Amazon Kinesis Data Streams as an event source for Lambda
- Try-it-out exercise: Configure an Amazon SQS queue with a dead-letter queue as a Lambda event source
Hands-On Labs


- Hands-On Lab 1: Deploying a Simple Serverless Application
- Hands-On Lab 2: Message Fan-Out with Amazon EventBridge
Module 7: Writing Good Lambda Functions


- How the Lambda lifecycle influences your function code
- Best practices for your Lambda functions
- Configuring a function
- Function code, versions and aliases
- Try-it-out exercise: Configure and test a Lambda function
- Lambda error handling
- Handling partial failures with queues and streams
Module 8: Step Functions for Orchestration


- AWS Step Functions in serverless architectures
- Try-it-out exercise: Step Functions states
- The callback pattern
- Standard vs. Express Workflows
- Step Functions direct integrations
- Try-it-out exercise: Troubleshooting a Standard Step Functions workflow
Module 9: Observability and Monitoring


- The three pillars of observability
- Amazon CloudWatch Logs and Logs Insights
- Writing effective log files
- Try-it-out exercise: Interpreting logs
- Using AWS X-Ray for observability
- Try-it-out exercise: Enable X-Ray and interpret X-Ray traces
- CloudWatch metrics and embedded metrics format
- Try-it-out exercise: Metrics and alarms
- Try-it-out exercise: ServiceLens
Hands-On Labs


- Hands-On Lab 3: Workflow Orchestration Using AWS Step Functions
- Hands-On Lab 4: Observability and Monitoring
Module 10: Serverless Application Security


- Security best practices for serverless applications
- Applying security at all layers
- API Gateway and application security
- Lambda and application security
- Protecting data in your serverless data stores
- Auditing and traceability
Module 11: Handling Scale in Serverless Applications


- Scaling considerations for serverless applications
- Using API Gateway to manage scale
- Lambda concurrency scaling
- How different event sources scale with Lambda
Module 12: Automating the Deployment Pipeline


- The importance of CI/CD in serverless applications
- Tools in a serverless pipeline
- AWS SAM features for serverless deployments
- Best practices for automation
- Course wrap-up
Hands-On Labs


- Hands-On Lab 5: Securing Serverless Applications
- Hands-On Lab 6: Serverless CI/CD on AWS

## Summary
This course gives developers exposure to and practice with best practices for building serverless applications using AWS Lambda and other services in the AWS serverless platform. You’ll use AWS frameworks to deploy a serverless application in hands-on labs that progress from simpler to more complex topics. You will use AWS documentation throughout the course to develop authentic methods for learning and problem-solving beyond the classroom.

## Course Duration
3 days

## Last Changed
2024-10-14T17:34:11.000Z
