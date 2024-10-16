# Implementing a CI/CD Pipeline

**Product ID**: 22883
**Category ID**: nan
**Modality**: 6
**Active**: True
**Language**: en
**Product Code**: DEVOPSPIPELINE3
**Vendor Code**: OT
**Vendor Name**: Other
**URL**: [Course Link](https://www.fastlaneus.com/course/ot-devopspipeline3)

## Objective
- Maintain code using Git and GitHub
- Create, test, and deploy Chef cookbooks through a Jenkins CI/CD pipeline
- Complete integration tests with Inspec and Test Kitchen
- Write CI/CD as code using Groovy Pipeline syntax in Jenkins
- Compile, test, package, and permanently store Java applications using Maven
- Store artifacts in JFrog Artifactory

## Essentials
- Writing code (of just about any flavor) in a text editor
- Working on the command line
- Basic system administration – installing packages, configuring those packages, starting a service

## Audience
- DevOps Engineers
- System Operations
- Code Developers
- Software Developers
- Quality Assurance Professionals
- Software Testers
- Product Owners
- Infrastructure Engineers
- Development Team Members
- Operations Team Members
- Project Managers
- Technical Product Managers

## Outline
Technology Overview



- Terraform – Infrastructure control (optional with 5-day delivery)
- Git - Source Control Management
- Chef - Configuration Management
- Inspec - Cookbook Testing
- Jenkins - Continuous Integration
- Docker – Containerization (optional for 4-day delivery)
Terraform – Infrastructure Automation (optional with 5-day delivery)



- Terraform use and purpose
- Getting started with Terraform
- General concepts
- Installation
- Configuration Files
- Provisioning and Building Infrastructure
- Changing Infrastructure
- Destroying Infrastructure
- Resource Dependencies
- Input Variables
- Output Variables
- Modules – Pre-defined Configurations
- Remote state management
- Terraform Enterprise
- Triggering a Plan from Version Control
- Workspaces
- Terraform Enterprise Runs
- Migration from Open Source to Enterprise
- AWS

- Managing infrastructure in AWS
- Creating IAM Policies
- Authenticating to AWS
- Launching a serverless application - Lambda
- Azure

- Managing infrastructure in Azure
- Authentication Methods for Azure
Git – Source Control Management



- Purpose and overview of Git
- Use cases for Git
- Git workflow
- Github, Bitbucket and other Git providers
- Installation and configuration
- Finding help on Git
- Creating Local Git Repositories
- Basic Git Commands
- Comparing commits
- Using a Remote Repository
- Branching and Merging
- Using SSH keys with Git private repositories
Chef – Configuration Management



- Chef Architecture and call flow
- Chef Use cases
- Idempotence
- Resources
- Recipes
- Cookbooks
- Integration Testing and Test Kitchen
- Chef Server – a central management repository
- Ohai, Attributes and the Node Object
- Chef Roles
Jenkins – Continuous Integration / Continuous Deployment



- Jenkins Overview, Use Cases and History
- Initializing a Jenkins server
- Projects & Jobs
- Freestyle versus Pipeline
- Writing a Declarative Pipeline Project - CI/CD as Code
- Distributing builds using Master and Agent Nodes
- Views and Folders
- Managing Credentials
- Integrating with Git - Source Control Management
- Triggers: Webhooks and Polling
- Notifications: Slack and SMTP Email
- Testing Chef Cookbooks with Test Kitchen in Jenkins
- Multibranch Pipelines - Reading Entire Repositories
- Using Maven to Compile, Test & Package Java Applications
- Storing artifacts in JFrog Artifactory
- Deploying Chef cookbooks with Jenkins
Docker – Containerization And Micro-Service (optional with 4-day delivery)



- Container Use cases: what problems Docker solves
- Docker Concepts and Components
- Most-used Docker Commands
- Storing Docker images
- Docker Compose
- Launching microservices using Docker
- Building a Docker Image using Jenkins
- Deploying a Docker container using Chef and Jenkins
Finally, we’ll create the end-to-end Pipeline using Git, Chef & Jenkins:

Three-day option:



- Write Chef cookbooks with Inspec tests
- Push the cookbooks to a branch within a Git repo
- This push will automatically trigger Jenkins to download the cookbooks
- Jenkins will then initiate testing the Chef cookbooks using Test Kitchen
- If any tests fail, Jenkins notifies the developer to fix and repeat the build
- Once all tests pass, Jenkins can require human approval. Once approved, Jenkins will upload the cookbooks to the Chef Server
- Jenkins will then trigger Chef-managed webservers (in AWS) to download the cookbooks from the Chef Server and deploy the cookbook code
- Jenkins will then send notifications over both Slack and email regarding any failures or the successful deployment of the cookbooks
Four-day option adds:



- Upon successful testing in Test Kitchen, create and save a Docker image
- Notify teams of successful deployment of Docker containers
Five-day option adds: 



- Write Inspec tests for Terraform configurations
- Test our Terraform Configuration in Test Kitchen
- Jenkins will use Terraform to launch Docker Hosts running Docker containers, as well as use Chef to configure those containers to run micro-services

## Summary
nan

## Course Duration
3 days

## Last Changed
2024-08-23T16:14:28.000Z
