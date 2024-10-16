# VMware NSX Advanced Load Balancer: Install, Configure, Manage

**Product ID**: 22599
**Category ID**: nan
**Modality**: 6
**Active**: True
**Language**: en
**Product Code**: NSXALBICM
**Vendor Code**: VM
**Vendor Name**: VMware
**URL**: [Course Link](https://www.fastlaneus.com/course/vmware-nsxalbicm)

## Objective
By the end of the course, you should be able to meet the following objectives:


- Describe the NSX Advanced Load Balancer architecture
- Describe the NSX Advanced Load Balancer components and main functions
- Explain the NSX Advanced Load Balancer key features and benefits
- Deploy and configure the NSX Advanced Load Balancer infrastructure within private or public clouds using Write and No-Access Cloud Connectors
- Explain, deploy, and configure Service Engines
- Explain and configure local load balancing constructs such as virtual services, pools, health monitors, and related components
- Explain and configure advanced virtual services and related concepts such as Subject Name Indication, Enhanced Virtual Hosting, and authentication of virtual services
- Explain and modify application behavior through profiles, policies, and DataScripts
- Describe Central licensing management using VMware NSX Advanced Load Balancer Enterprise with Cloud services (formerly Avi Pulse)
- Explain how to configure Role-Based Access Control (RBAC) in NSX Advanced Load Balancer
- Configure advanced services such as global server load balancing
- Describe how to use NSX Advanced Load Balancer REST API interfaces and related automation capabilities
- Describe and configure NSX Advanced Load Balancer application and infrastructure monitoring
- Gather relevant information and perform basic troubleshooting of applications that use built-in NSX Advanced Load Balancer tooling
- Identify the key features of VMware NSX Network Detection and Response

## Essentials
This course has no prerequisites.

## Audience
Experienced system administrators and network administrators

## Outline
1 Course Introduction


- Introduction and course logistics
- Course objectives
2 Introduction to NSX Advanced Load Balancer


- Introduce NSX Advanced Load Balancer
- Discuss NSX Advanced Load Balancer use cases and benefits
- Explain NSX Advanced Load Balancer architecture and components
- Explain the management, control, data, and consumption planes and their respective functions
3 Virtual Services Configuration Concepts


- Explain virtual service components
- Explain virtual service types
- Explain and configure basic virtual service components such as application profiles and network profiles
4 Virtual Services Configuration Advanced Concepts


- Explain the virtual service advanced components such as Wildcard VIP, Server Name Identification (SNI), and Enhanced Virtual Hosting (EVH)
- Explain the concept of virtual service VIP Sharing
- Explain different authentication mechanisms used for a virtual service such as LDAP, SAML, JSON Web Token, and OAUTH
5 Profiles and Policies


- Explain application profiles and types such as L4, DNS, Syslog, HTTP, and VMware Horizon VDI
- Explain and configure advanced application HTTP profile options
- Describe network profiles and types
- Explain and configure SSL profiles and certificates
- Explain and configure HTTP, network, and DNS policies
6 Pools Configuration Concepts


- Explain pools configuration options
- Describe the available load balancing algorithms
- Explain multiple health monitor types
- Explain multiple Persistence profiles
- Explain and configure pool groups
7 Modifying Application Behavior


- Design and apply application solutions by using application profiles
- Design and apply application solutions by using network, HTTP policies, and DataScripts
- Explain DataScript fundamentals
- Explain and use NSX Advanced Load Balancer analytics to understand application behavior
- Describe and configure client SSL certificate validation
- Describe and configure virtual service DDoS, Rate limiting, and Throttling capabilities
- Modify network profile properties such as TCP connection properties
- Design and apply application solutions by using Persistence profiles
8 NSX Advanced Load Balancer Infrastructure Architecture


- Explain management, control, data, and consumption planes and functions
- Describe control plane clustering and high availability
- Describe controller sizing and process sharing
- Describe Service Engine CPU and NIC architecture
- Explain tenants
- Configure properties of Service Engine groups
- Explain Service Engine group high availability modes
- Describe and configure active-standby high availability mode
- Explain Service Engine placement in multiple availability zones for public clouds
- Describe and configure elastic HA high availability mode (Active-Active, N+M)
- Explain Service Engine failure detection and self-healing
- Describe Service Engine as a router
- Explain virtual service scale-out options such as Layer 2 (Native), Layer 3 (BGP), and DNS-based
- Describe how to upgrade NSX Advanced Load Balancer
9 Introduction to Cloud Connector


- Explain cloud connectors
- Review cloud connector integration modes
- List cloud connector types
- Review the different Service Engine image types in different ecosystems
10 Installing, Configuring, and Managing NSX Advanced Load Balancer in No-Orchestrator Cloud


- Explain No-Access cloud concepts
- Configure No-Access cloud integration on bare metal
- Explain and configure Linux Server Cloud
- Explain and configure VMware No Orchestrator
- Describe the advanced configuration options available in bare metal (Linux Server Cloud)
11 Installing, Configuring, and Managing NSX Advanced Load Balancer in VMware Environment: Cloud Configuration


- Introduce VMware integration options
- Explain and configure VMware Write Access Cloud Connector
- Explain NSX Advanced Load Balancer integration options in a VMware NSX environment
- Explain and configure NSX Cloud Connector for Overlay and VLAN-backed segments
12 AWS Cloud Configuration


- Describe NSX Advanced Load Balancer public cloud integrations
- Explain different AWS components
- Explain and demonstrate AWS public cloud integration
- Deploy VMware NSX Advanced Load Balancer Controller, SEs, and virtual services in AWS Cloud
- Review Multi-AZ Support for virtual services in AWS cloud
13 GCP Cloud Configuration


- Explain different GCP components
- Explain and demonstrate GCP public cloud integration
- Deploy NSX Advanced Load Balancer Controller, SEs, and virtual services in GCP cloud
14 Azure Cloud Configuration


- Describe NSX Advanced Load Balancer public cloud integrations
- Explain different Microsoft Azure components
- Explain and demonstrate Azure public cloud integration
- Deploy NSX Advanced Load Balancer Controller, SEs, and virtual services in Azure Cloud
15 NSX Advanced Load Balancer Enterprise with Cloud Services (Avi Pulse)


- Describe NSX Advanced Load Balancer public cloud services
- Explain different features of NSX Advanced Load Balancer Cloud Services
- Register the controller with Cloud Services
16 DNS Foundations


- Review, discuss, and explain DNS fundamentals
- Describe NSX Advanced Load Balancer DNS and IPAM providers
17 Global Server Load Balancing (GSLB)


- Introduce Global Server load balancing concepts and benefits
- Explain and configure the NSX Advanced Load Balancer infrastructure
- Explain and configure the DNS Virtual Service components
- Explain and configure GSLB Service Engine Group
- Describe and configure GSLB sites
- Explain and configure basic GSLB services to include pools and health monitors
- Describe GSLB Server Load Balancing algorithms
- Explain and configure health monitors based on data plane and control plane
- Describe GSLB Health Monitor Proxy
- Explain GSLB Site-Cookie Persistence
- Explain the different GSLB replication methods
18 Role-Based Access Control (RBAC)


- Introduce local authentication in NSX Advanced Load Balancer
- Introduce remote authentication in NSX Advanced Load Balancer
- Review the different types of remote authentication
- Explain granular RBAC using labels
19 NSX Advanced Load Balancer: Troubleshooting


- Introduce infrastructure and application troubleshooting concepts
- Describe troubleshooting based on control plane and data plane
- Explain application analytics and logs
- Describe client logs analysis
- Explain headers troubleshooting and packet capture mechanism
- Describe how to use CLI for detailed data plane troubleshooting
- Explain Service Engine logs
- Explain health monitors troubleshooting
- Explain BGP session troubleshooting
- Describe control plane troubleshooting, clustering, and cloud connector issues
20 Events and Alerts


- Describe NSX Advanced Load Balancer events
- Describe and configure NSX Advanced Load Balancer alerts
- Describe NSX Advanced Load Balancer monitoring capabilities with SNMP, Syslog, and Email
21 Introduction to NSX Advanced Load Balancer Rest API


- Introduce the NSX Advanced Load Balancer REST API interface
- Describe REST API Object Schema
- Explain and interact with REST API interface with browser and command-line utility
- Explain Swagger-based API documentation
- Review the different types of SDKs available in NSX Advanced Load Balancer
- Explain and configure VMware Write Access Cloud Connector
- Explain NSX Advanced Load Balancer integration options in the VMware NSX environment
- Explain and configure NSX Cloud Connector for Overlay and VLAN-backed segments
- Introduce VMware integration options

## Summary
This five-day, fast-paced course provides comprehensive training to install, configure, and manage a VMware NSX Advanced Load Balancer (Avi Networks) solution. This course covers key NSX Advanced Load Balancer (Avi Networks) features and functionality offered in the NSX Advanced Load Balancer 21.x release. Features include the overall infrastructure, virtual services, application components, global server load balancing, various cloud connectors, application troubleshooting, and solution monitoring. Hands-on labs provide access to a software-defined data center environment to reinforce the skills and concepts presented in the course.

Product Alignment


- NSX Advanced Load Balancer 21.x

## Course Duration
5 days

## Last Changed
2024-09-23T18:12:26.000Z
