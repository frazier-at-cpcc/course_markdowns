# Ansible Essentials 101

**Product ID**: 30028
**Category ID**: nan
**Modality**: 6
**Active**: True
**Language**: en
**Product Code**: A101E
**Vendor Code**: A3
**Vendor Name**: Alta3
**URL**: [Course Link](https://www.fastlaneus.com/course/alta3-a101e)

## Objective
- Version controlling code with Git
- Overview of Ansible modules
- Ansible collections for content delivery
- Building roles for code reuse
- YAML formatting
- Playbook construction and order of execution
- Jinja2 templating
- Static and Dynamic inventory management
- Credential Management and Encryption with Vault
- Finding solutions on Ansible Galaxy

## Essentials
Coding experience in another language serves as an adequate prerequisite

## Audience
- DevOps Engineers
- System and Cloud Administrators
- Network Engineers and Developers
- Python Developers

## Outline
Day 1 (Ansible Introduction)


Ansible Introduction


- Ansible definition
- Exploring modules
- Building a task
- Places to define Ansible vars
- hosts aka “Inventory”
- Creating a A play
- Looking at the “handler”
- Running a playbook
- Introduction to YAML
- Requirements for connecting to remote hosts
Installation


- Configuration requirements on the control machine
- Python requirements on the host
- Using ansible raw to install Python
Ansible config file and directory structure


- ansible.cfg
- Ansible Inventory
- roles
Ansible Static Inventory


- Defining Hosts and Groups
- Host and Group variables
- Groups of Groups
- Default Groups
YAML


- YAML Gotchas
- YAML Dictionary
- YAML list
- YAML list of dictionaries
- YAML Alternate format
- Relationship to JSON
Day 2 (Ansible for Server Operations)


Ansible Ad hoc commands


- Ad hoc command syntax
- Parallel Shell commands
- Managing packages
- Managing users and groups
- Gathering facts
- ad hoc cheat sheet
Writing a Simple Playbook


- Elements of a well written playbook
- A well-written Ansible play
- Using include files for tasks
- A well-written ansible variable file
- A well-written ansible inventory file
Ansible config file and directory structure


- ansible.cfg
- Best practices concerning directory structures and organization
- Host Inventory and ansible_vars
- Introduction to roles
Key Server Modules to Know


- Understanding modules documentation
- setup / gather_facts
- copy
- apt / yum / pip
- command / shell
- git
- get_url
- debug
- lineinfile
Day 3 (Ansible for Network Operations)


Ansible and Jinja


- What is Jinja2?
- jinja variables
- jinja filters
- jinja tests
- How to use ansible template
- Review of the ansible template documentation
Conditional and Looping Tasks


- Variables and Loops
- Using Complex Variables in Loops
- Variables and Templates
- Using variables in conditions
- Blocks
- Prompts
- Getting variables from the system
- Setting variables in playbooks
- registered variables
- Getting variables from the command line
- Where is the best source to derive variables values?
Ansible Network Solutions with Ansible (focus on Juniper and Cisco)


- Writing Cisco and Juniper playbooks
- Modules for Cisco (IOS, NXOS, IOSXR, etc)
- Exploring Juniper solutions
- Built in Juniper modules
- Role based Juniper modules
- Installing a module from Juniper vendor
- Securing credentials / best practices
- New additions within the latest version of Ansible (v2.9)
Day 4 (Customizing Ansible & Ansible for Cloud)


Dynamic Inventory Management


- What is Dynamic Inventory?
- A review of static Inventory Practices
- Using JSON as an Inventory Source
- Using YAML as an Inventory Source
- Pulling Inventory from an API
- AWS EC2 Example
- OpenStack Example
Ansible for OpenStack and AWS


- Overview of OpenStack
- Understanding the OpenStack client
- What is openstack-sdk (or shade)?
- clouds.yaml
- Installing openstack-sdk
- Using openstack-sdk
- OpenStack modules
- os_network
- os_subnet
- os_router
- os_server
- os_server_action
- os_security_group
- os_security_group_rule
- What is boto?
- installing boto for AWS
- AWS modules
- ec2
- aws_s3_bucket_info
- redshift
Variables and Python


- Jinja Filters for variable manipulation
- Using Python within playbooks for variable manipulation
- Best practices for Variables
- Securing credentials with Ansible Vault
- Encrypting Playbooks with Ansible Vault
Day 5 (Ansible Playbook Design & Review)


Roles and Ansible Galaxy


- Why we need Ansible Roles
- Role Directory Structure
- Using Roles
- Role default variables
- Converting a Playbook to a Role
- Exploring Ansible Galaxy
- Running a role from Ansible Galaxy
Playbook Best Practices


- Directory Layout
- Use Dynamic Inventory With Clouds
- How to Differentiate Staging vs Production
- Group and Host Variables
- Top Level Playbooks Are Separated By Server Type
Ansible Tower / AWX Essentials


- What is Ansible Tower and AWX
- Why you should consider using Jenkins as a replacement for Ansible Tower
- Pushing and pulling playbooks from GitHub

## Summary
Ansible is used to bring structure and consistency to system deployments, implementations, and changes. Students tempted to write a complex Python script to do a networking automation task will discover that the problem is already solved by an Ansible module. Lots of unnecessary Python scripts can be eliminated by using Ansible whenever possible. Ansible is used for both network and server administrators alike.

## Course Duration
5 days

## Last Changed
2024-08-23T16:58:44.000Z
