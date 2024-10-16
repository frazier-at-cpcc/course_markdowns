# Introduction to 802.1X Operations for Cisco Security Professionals

**Product ID**: 3157
**Category ID**: nan
**Modality**: 1
**Active**: True
**Language**: en
**Product Code**: 802.1X
**Vendor Code**: CI
**Vendor Name**: Cisco
**URL**: [Course Link](https://www.fastlaneus.com/course/cisco-802.1x)

## Objective
Upon completion of this course, you will be able to:



- Describe Cisco TrustSec concepts
- Describe IEEE 802.1X concepts, architecture, and requirements for deployment
- Describe how the RADIUS authentication protocol is used for Cisco TrustSec
- Configure ISE for 802.1x operation
- Describe IEEE 802.1X supplicants for Microsoft, Apple and Cisco
- Configure IEEE 802.1X for a wired network
- Configure IEEE 802.1X for a wireless network
- Describe how to provide secure guest access in a Cisco TrustSec network
- Build a high level design of a Cisco TrustSec network using IEEE 802.1X

## Essentials
The skills and knowledge you must possess to benefit fully from the course include the following:



- Cisco Certified Network Associate (CCNA)
- Attendance of Securing Networks with Routers and Switches (SNRS) or equivalent knowledge
- Knowledge of Microsoft Windows Server 2008 Active Directory
- Knowledge of Cisco Wireless LAN Controllers and Lightweight Access Points
- Knowledge of basic command-line configuration of Cisco Catalyst switches

## Audience
This course is primarily intended for: 



- Cisco Partner Sales Engineers and Field engineers supporting customers with 802.1x solutions
- Cisco Channel Partner SEs and FEs that are seeking to meet the education requirements to attain ATP authorization to sell Cisco ISE
Others who would find this course useful include:



- Security architects, design engineers, and others seeking hands-on experience with Cisco TrustSec 802.1X deployments with Cisco ISE

## Outline
Module 0: Course Introduction


Module 1: Cisco TrustSec

Module Objective: Describe Cisco TrustSec concepts and components.

Module 1 Lesson 1: Surveying Cisco TrustSec



- Describe elements of Cisco TrustSec solutions
- Identify the role of AAA services in the context of Cisco TrustSec
- Contrast capabilities of Cisco TrustSec implementations
Module 1 Lesson 2: Surveying Cisco TrustSec Architecture Components



- Describe the function of the client supplicant software
- Describe the function of the 802.1X authenticator
- Describe the function of the 802.1X authentication server
- Describe the function of a directory server in the context of 802.1X
- Identify methods available in Cisco TrustSec to facilitate traffic isolation

Module 2: Survey Port-Based Authentication
Module Objective: Articulate the components and processes of port-based authentication.

Module 2 Lesson 1: Surveying the IEEE 802.1X Standard



- Describe the technical motivation for the creation of the IEEE 802.1X standard
- Describe important sections of the standards document
Module 2 Lesson 2: Surveying 802.1X and EAP



- Describe the reasons for the development of the EAP protocol and how it is used in IEEE 802.1X authentication and authorization
- Describe EAP types and their implementation requirements
Module 2 Lesson 3: Describing the Role of RADIUS in EAP Communications



- Describe the role of RADIUS in 802.1X communications
- Describe the role of RADIUS attribute-value pairs in 802.1X authentication and authorization

Module 3: Configure Devices for 802.1X Operation
Module Objective: Identify the 802.1X components and their interrelation at a high level.

Module 3 Lesson 1: Identifying 802.1X Components and Topologies



- Review IEEE 802.1X components
- Identify the role of authenticators in 802.1X
- Identify the role of authentication servers in 802.1X
- Identify the role of directory services in 802.1X
- Survey common Cisco TrustSec topologies


Module 3 Lesson 2: Configuring Cisco ISE for 802.1X Operation



- Bootstrap Cisco ISE on physical and virtual appliances
- Configure network devices in Cisco ISE
- Configure a Cisco ISE self-signed certificate
- Provision Cisco ISE for PEAP
- Configure simple authentication
- Configure rule-based authentication
Module 3 Lesson 3: Configuring Network Devices for 802.1X 



- Configure global AAA and 802.1X on Cisco Catalyst Switches
- Configure interface-specific 802.1X commands on Cisco Catalyst Switches
- Configure AAA and 802.1X on Cisco WLCs
Module 3 Lesson 4: Configuring Supplicants for 802.1X Operations



- Describe the function of 802.1X supplicant software
- Configure the Microsoft Windows 7 supplicant for wired and wireless operation
- Configure the Apple Macintosh supplicant for wired and wireless operation
- Configure an Ubuntu Linux supplicant for wired and wireless operation
- Configure the Cisco AnyConnect Secure Mobility Client supplicant for wired and wireless operation on Microsoft Windows 7
Lab 1-0: Access the Lab Equipment



- Connect to the Cisco Advanced Services ASA and install the Cisco AnyConnect 2.5 SSL VPN Client
- Connect to your Admin PC using an RDP client


Lab 1-1: Configuring Cisco ISE, Switch, WLC, and Clients



- Create device groups and bind them to geographic locations
- Configure Cisco ISE to support the switch as a AAA client
- Configure Cisco ISE to support the WLC as a AAA client
- Configure your 3750 access switch to communicate RADIUS with Cisco ISE
- Configure global and interface-specific commands to enable 802.1X on your 3750 access switch
- Configure the Cisco ISE endpoint database to allow MAC Authentication Bypass (MAB) of the Cisco 7965 IP phone
- Configure the WLC to use RADIUS authentication for wireless users
- Create a new WLAN on your WLC to support 802.1X authentication
- Create two local user accounts and bind them to two new groups in Cisco ISE
- Configure and validate connectivity between the Cisco ISE Server and Windows Active Directory
- Install a CA-signed certificate in Cisco ISE to validate management and EAP communications
- Create an authentication profile for PEAP 802.1X wired users to be authenticated against the Active Directory  database
- Configure global PEAP settings in Cisco ISE
- Obtain and install a CA certificate on the Windows 7 client
- Enable 802.1X on the Windows 7 client and configure it for PEAP 802.1X wired access to be authenticated against the Active Directory database using the employee account
- Verify the Windows 7 host EAP-PEAP wired connectivity
- Create a wireless profile with the Network Access Manager Profile Editor that will be used to allow the Cisco AnyConnect Secure Mobility Client to connect to the data WLAN using the mblue account
- Verify the Windows 7 host EAP-PEAP connectivity on the Wireless LAN
- Run reports to view details of successful authentications

Module 4: Configure Guest Access 
Module Objective: Identify requirements and options for non-supplicant devices.

Module 4 Lesson 1: Configuring Cisco TrustSec for Non-Supplicant Devices



- Identify non-supplicant devices
- Configure a guest VLAN
- Configure a restricted VLAN
- Configure a critical VLAN


Module 4 Lesson 2: Configuring Cisco WebAuth for Non-Supplicant Devices



- Configure global WebAuth options
- Configure interface-specific options
Lab 2-1: Configuring Authentication Using Web Authentication



- Configure AAA Authentication for WebAuth
- Configure success redirect
- Configure fail policy
- Configure authentication parameters
- Login using WebAuth
- Customize preconfigured custom proxy web pages and upload to switch, then configure switch for pages.
- Login using WebAuth
- Display WebAuth status

Module 5: Design Cisco TrustSec Networks with Cisco ISE and 802.1X 
Module Objective: Position individual components of an 802.1X network and identify compatibilities. Review design and implementation considerations. Identify design pitfalls.

Module 5 Lesson 1: Identifying Component Compatibilities with 802.1X



- Describe Cisco ISE architectural components
- Describe Cisco ISE deployment options
- Identify Cisco network devices that include Cisco TrustSec 802.1X support
- Identify external identity stores supported by Cisco ISE
Module 5 Lesson 2: Reviewing 802.1X Design Considerations That Impact Implementation



- Describe solutions to Cisco TrustSec exception topologies using NEAT
- Describe solutions to mobile hosts in a Cisco TrustSec implementation
- Describe authentication sequencing capabilities and options
- Define the operational function of MAC security and its interoperability with 802.1X
Module 5 Lesson 3: Reviewing Scalable 802.1X Architectures



- Review Cisco TrustSec components and protocols
- Review Cisco TrustSec design considerations for clients
Case Study: 3-1 – Designing an End-to-End High-Level Cisco TrustSec Network with Cisco ISE and 802.1X



- Determine the types of devices and protocols that will be permitted to access the network
- Determine traffic isolation techniques that will be employed to control access
- List the commands to allow features such as MAB, FlexAuth, and Multi-Domain Authentication as required by devices
- Generate a WLC configuration for wireless 802.1X.
- Configure Cisco ISE to support the features configured on the Cisco Catalyst switch and WLC
Appendix A: Provision Cisco ISE CA-Signed Certificates 



- Install a CA certificate in Cisco ISE
- Generate a certificate signing request in Cisco ISE
- Copy PKCS#10 formatted CSR to the CA
- Download and install an identity certificate into Cisco ISE

## Summary
nan

## Course Duration
3 days

## Last Changed
2024-09-18T17:38:14.000Z
