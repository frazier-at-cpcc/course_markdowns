# Junos Platform Automation and DevOps

**Product ID**: 3204
**Category ID**: nan
**Modality**: 6
**Active**: True
**Language**: en
**Product Code**: JAUT
**Vendor Code**: JP
**Vendor Name**: Juniper Networks
**URL**: [Course Link](https://www.fastlaneus.com/course/juniper-jaut)

## Objective
- Describe the benefits of network automation
- Explain basic principles of DevOps and NRE
- Describe different approaches and tools used for Junos Automation
- Discuss how templates are used for Junos automation
- Understand Jinja2 syntax
- Describe various methods Junos PyEZ can use to connect to a Junos device
- Execute Junos RPCs using Junos PyEZ
- Explain the functionality of various Junos PyEZ utilities
- Use Jinja2 templates with Junos PyEZ
- Use Junos PyEZ Tables and Views
- Securely connect to Junos devices using Ansible
- Use advanced Ansible playbook functionality
- Work with Ansible variables
- Manage Junos device configurations using Jinja2 templates and Ansible
- Explain the use of SLAX language with Junos
- Understand basic SLAX syntax
- Describe SLAX templates, variables, and flow control statements
- Understand the Junos function library
- Explain the difference between available SLAX versions
- Explain how to create and run Junos op scripts
- Use SLAX and Python languages to develop op scripts
- Use arguments with op scripts
- Issue RPCs from op scripts
- Change the configuration with op scripts
- Describe how commit scripts can be used to make changes to the configuration
- Describe how to use commit scripts to generate custom warnings and errors during a commit
- Explain how to use SLAX and Python languages to develop commit scripts
- Configure and enable commit scripts
- Identify Junos OS events
- Create Junos OS event policies
- Create Junos OS event scripts
- Understand the use of Junos OS SNMP scripts
- Create and configure Junos OS SNMP scripts
- Explain basic Salt architecture
- Understand how Junos devices are managed with Salt
- Use Junos execution and state modules for Salt
- Understand the SLS file format
- Describe how JSNAPy can help automate Junos
- Install and configure JSNAPy
- Use JSNAPy to create snapshots
- Use JSNAPy to perform tests
- Describe the YANG language features
- Understand the syntax of YANG
- Explain how YANG is used in Junos OS
- Describe the advantages of OpenConfig
- Modify the Junos OS configuration using OpenConfig
- Describe using OpenConfig with the Junos Telemetry Interface (JTI)
- Explain what is JET
- Understand the JET Service API
- Understand the JET Notification API
- List protocols and data formats used with JET
- Develop simple JET applications
- Understand the Junos Telemetry Interface
- Provision Junos Telemetry sensors
- Explain the difference between Native and gRPC sensors
- Understand Telemetry message formats
- Explain the advantages of Contrail HealthBot
- Explain the purpose and value of ZTP
- Describe the components and operations of ZTP
- Deploy a QFX5100 Series switch using ZTP
- Setup the JET VM
- Create JET Packages

## Essentials
- Intermediate-level networking knowledge.
- Understanding of the Open SystemsInterconnection (OSI) model and the TCP/IP protocol suite.
- Attendance of the Introduction to (!)  course prior to attending this class.

## Audience
This course benefits individuals responsible for configuring and monitoring devices running the Junos OS.

## Outline
Day 1

Course Introduction

Junos Automation Fundamentals


- Benefits of Automation
- DevOps and NRE
- Junos Automation Stack
- Junos Automation Tools
- Introduction to NITA
Jinja2


- Jinja2 Overview
- Working with Jinja2 in Python
- Jinja2 Syntax
Advanced Junos PyEZ


- Connecting to a Junos Device
- Working with RPCs
- Junos PyEZ Utilities
- Junos PyEZ and Jinja2
- Tables and Views
LAB 1: Using Junos PyEZ with Jinja2 Templates

Day 2

Ansible Intermediate


- Ansible for Junos Review
- Securing Device Connection
- Playbook Flow Control
LAB 2: Ansible Operations with Junos


- Ansible Variables and Jinja2 Templates
- Case Study
LAB 3: Using Ansible for Junos Configuration Management

SLAX


- Junos On-Box Automation Overview
- Basics of SLAX
- SLAX Variables
- Flow Control
- Junos Function Library
- SLAX Versions
Junos Op Scripts


- Junos Op Scripts Using SLAX
- Customizing Junos Command Output
- Configuration Changes with SLAX Op Scripts
- Junos Op Scripts Using Python
- Configuration Changes with Python Op Scripts
- Op Script Configuration and Debugging
LAB 4: Junos Op Scripts

Junos Commit Scripts


- Junos Commit Scripts Overview
- Junos Commit Scripts Using SLAX
- Junos Commit Scripts Using Python
- Custom Configuration Syntax
- Commit Script Configuration and Debugging
LAB 5: Junos Commit Scripts

Day 3

Junos Event Policies and Event Scripts


- Junos OS Events
- Event Policies
- Event Scripts
LAB 6: Junos Event Policies and Event Scripts

Junos SNMP Scripts


- Junos OS SNMP Scripts
- Case Study
LAB 7: Junos SNMP Scripts

Salt


- Salt Overview
- Junos and Salt
- Junos Execution Module
- Salt States and Junos State Module
- Case Studies
LAB 8: Automating Junos with Salt

Day 4

JSNAPy


- JSNAPy Overview and Installation
- Configuration Files
- JSNAPy Commands
- Test Files
- Integration with Other Tools
LAB 9: Using JSNAPy

YANG


- YANG Overview
- YANG Statements and Syntax
- Junos YANG Modules
- Custom YANG Modules for Junos
- Custom Configuration and Translation Script Example
- Custom RPC and Action Script Example
OpenConfig


- OpenConfig Overview
- OpenConfig Package
- Using OpenConfig
- OpenConfig Telemetry
LAB 10: Implementing OpenConfig

Day 5

Junos Extension Toolkit


- Overview of JET
- gRPC and JET IDL Files
- JET Service API
- JET Notification API
LAB 11: Using JET

Junos Telemetry


- Junos Telemetry Overview
- Native Sensors for JTI
- OpenConfig and gRPC Sensors for JTI
- Contrail HealthBot Overview
- Contrail HealthBot Rules and Playbooks
- Case Study
Lab 12: Using Junos Telemetry

Appendix: Zero Touch Provisioning


- Understanding Zero Touch Provisioning
- ZTP in Action: A Working Example
Appendix: Using JET Virtual Machine


- Setting Up the JET VM
- Creating Signed JET Applications

## Summary
This five-day course provides students with knowledge of how to automate Junos using DevOps automation tools, protocols, and technologies. Students receive hands-on experience with tools and languages relevant to automating the Junos OS platform in a DevOps environment. The course includes introduction to Jinja2 templates, an in-depth discussion of Junos PyEZ library, and detailed explanation of how Ansible, Salt and JSNAPy automation tools are used with Junos. The course introduces students to Junos commit, operation (op), event, and SNMP on-box scripts. Two languages for developing these scripts are discussed: SLAX and Python. The course also explains Juniper Extension Toolkit and related APIs, YANG and OpenConfig. Finally, the course discusses the use of Junos Telemetry Interface and Contrail HealthBot tool, and Junos ZTP feature. Through demonstrations and hands-on labs, students will gain experience in automating the Junos operating system and device operations.

This course uses Junos OS Release 18.3R1, Junos PyEZ 2.2, and Ansible 2.7.

## Course Duration
5 days

## Last Changed
2024-05-10T16:42:10.000Z
