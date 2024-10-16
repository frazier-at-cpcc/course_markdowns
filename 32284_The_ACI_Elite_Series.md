# The ACI Elite Series

**Product ID**: 32284
**Category ID**: nan
**Modality**: 6
**Active**: True
**Language**: en
**Product Code**: ACIES
**Vendor Code**: OT
**Vendor Name**: Other
**URL**: [Course Link](https://www.fastlaneus.com/course/ot-acies)

## Objective
- Describe ACI components and policy model
- Explain ACI packet forwarding
- Describe ACI fabric configuration
- Describe ACI logical constructs
- Explain how ACI uses contracts to allow for secure communication between endpoints
- Explain how ACI connects to other switched and routed networks
- Explain how to troubleshoot an ACI fabric
- Describe multi-site and multi-pod solutions, and how they fit in a multi-DC/multi-cloud design

## Essentials
nan

## Audience
This ACI Elite Series will provide value for anyone deploying or operating an ACI fabric. However, some topics will be more relevant to specific audience:



- Sessions 1, 7, 8, 9, 10, 12, 13, and 14 are more focused for Architects or Engineers completing design work
- Sessions 2, 3, 4, 5, 6, and 11 are more focused for operations teams

## Outline
Session 1 - ACI Overview


Lecture



- What is ACI
- ACIs benefits
- Overview of Switch and APIC models APIC Architecture Fabric
- Bring up process
- ACI Object Model
- ACI MGMT
- RBAC
- Syslog
- SNMP
- Upgrade Process
- BGP Policy
Labs



- Instructor demo GUI Overview
- Instructor demo Intro to CLI
- Creating Users and assign Permissions Software
- Upgrades
- Syslog, SNMP and config rollbacks
Session 2 - Fabric Forwarding


Lecture



- VXLAN refresher
- Understanding Bridge Domains
- Bridge Domain as a layer 2 boundary
- Difference between VLANs and Bridge Domains
- Bridge Domain configuration knobs
- Limit Learning to IP subnet
- Encapsulation and multicast group
- COOP
- Oracles and Citizens
- Endpoint tables
- Lookup process
- Layer2 and Layer3 forwarding
- ARP handling packet walk
- L2 packet walk
- L3 packet walk
- BUM traffic packet walk
- VXLAN Encapsulations
- Intro to Fd_VLANs and BD_VLANs
- VRF encapsulation
- EP move and bounce entries
- Rogue endpoint detection
- Silent hosts
- Endpoint table vs Mac and Routing Table


Labs:



- Intro to endpoint reachability troubleshooting
- Understanding show endpoint command
- Validate COOP entries (GUI and CLI)
- Using iPing, ELAM and Ftriage (App not CLI)
Session 3 - Fabric Configuration Part 1


Lecture:



- Overview of interface configurations
- Physical and VMM domains overview
- Deployment immediacy (VMM)
- Resolution immediacy (VMM)
- VLAN Pools
- Static and Dynamic Pools
- Base encap value
- AEPs
- Used as a way to tie VLANs to an Interface
- Used to define EPG membership
- Policy Groups
- Interface Profiles
- Overview of switch configurations
- VPC in ACI
- Switch Profiles
- VLANs in the ACI world
- P I, HW, Access Encap, BD and FD
- Physical Domain, AEP and VLAN Pool relationship to FD_VLAN.and VXLAN encap
Labs: 



- Create a physical Domain to connect endpoints to the ACI Fabric
- Create VLAN Pool and AEP
- Create a VMM domain to connect endpoints to the ACI fabric
- Create VLAN Pool and AEP
- Create VMM integration
- Create VPCs explicit protection groups
- Create Interface Profiles and Policy Groups
- Create Switch Profiles
- Understanding the output
- Show VLAN brief
- Show VLAN extended
- Show system internal eltmc info VLAN brief (vsh_lc shell)
Session 4 - Fabric Configuration Part 2


Lectures:



- Overview of interface configurations
- Physical and VMM domains overview
- Deployment immediacy (VMM)
- Resolution immediacy (VMM)
- VLAN Pools
- Static and Dynamic Pools
- Base encap value
- AEPs
- Used as a way to tie VLANs to an Interface
- Used to define EPG membership Policy Groups, Interface Profiles
- Overview of switch configurations
- VPC in ACI
- Switch Profiles
- VLANs in the ACI world
- P I, HW, Access Encap, BD and FD
- Physical Domain, AEP and VLAN Pool relationship to FD_VLAN and VXLAN encap
Labs:



- Create a physical Domain to connect endpoints to the ACI Fabric
- Create VLAN Pool and AEP
- Create a VMM domain to connect endpoints to the ACI fabric
- Create VLAN Pool and AEP
- Create VMM integration
- Create VPCs explicit protection groups
- Create Interface Profiles and Policy Groups
- Create SwitchProfiles
- Understanding the output
- Show VLAN brief
- Show VLAN extended
- Show system internal eltmc info VLAN brief (vsh_lc shell)
Session 5 - ACI Logical Constructs Part 1


Lecture:



- Tenants
- VRFs
- Bridge Domains
- Application Profiles
- EPGs and Endpoint Security Groups
- VMM and Physical Domains
- Intro to Contracts
Labs:



- Create a tenant
- Create an Application Profile
- Create a set of EPGs and establish L2 and L3 connectivity between endpoints
- Create required BDs, EPGs and Contracts
Session 6 - ACI Logical Constructs Part 2


Lecture:



- Tenants
- VRFs
- Bridge Domains
- Application Profiles
- EPGs and Endpoint Security Groups
- VMM and Physical Domains
- Intro to Contracts
Labs:



- Create a tenant
- Create an Application Profile
- Create a set of EPGs and establish L2 and L3 connectivity between endpoints
- Create required BDs, EPGs and Contracts
Session 7 - Contracts


Lecture:



- Contract Scope
- Subjects
- Filters
- Directives (Log and Policy Compression)
- Verifying L2 and L3 permit and denies from the GUI Subject Labels
- Apply both ways and reverse filter ports
- EPG Labels Deny
- Contracts
- Taboo Contracts
- Regular contracts with Deny Filter
- VRF Enforced and Unenforced
- Preferred Group
- VZ_ANY
- Consumed contract interfaces (Intro to leaking)
Labs:



- Enable EPG to EPG communication using Subject Labels and EPG Labels
- Enable EPG to EPG communication using Preferred Group and VZ_Any VRF options
- Block specific traffic using Taboo contracts and deny filters
Session 8 - External Connectivity Part 1


Lecture:



- Layer 2 Connectivity
- Understanding L2Outs
- Understanding VLANs on ACI
- Understanding EPG extensions
- Unicast Routing option on Bridge Domain for migration
- Dual homing Layer 2 connectivity
- Layer 3 Connectivity
- L3Out Building Blocks
- Single L3Outs with Multiple Node Profiles vs Multiple L3Outs with single Node Profile
- Traffic Shaping and traffic flow
- Layer 3 VPC
- Special configuration for HA L4-L7 Devices
- Understanding Subnet options for Ext-EPG
- Advertising routes
- Mapping L3Out to Bridge Domain
- Using Route Maps
- Shared L3Outs
- VRF Leaking overview and verification
- Shared L3Out on Common Tenant
- Shared L3Out on different tenants
- Transit Routing
Labs:



- Create a L2Out and consume a GW outside of ACI
- Replicate the config using an EPG extension
- Create a local L3Out
- Create a Shared L3Out
- Advertise routes not owned by ACI
- Configure an L3out to be preferred over other L3Outs
Session 9 - External Connectivity Part 2


Lecture:



- Layer 2 Connectivity
- Understanding L2Outs
- Understanding VLANs on ACI
- Understanding EPG extensions
- Unicast Routing option on Bridge Domain for migration
- Dual homing Layer 2 connectivity
- Layer 3 Connectivity
- L3Out Building Blocks
- Single L3Outs with Multiple Node Profiles vs Multiple L3Outs with single Node Profile
- Traffic Shaping and traffic flow
- Layer 3 VPC
- Special configuration for HA L4-L7 Devices
- Understanding Subnet options for Ext-EPG
- Advertising routes
- Mapping L3Out to Bridge Domain
- Using Route Maps
- Shared L3Outs
- VRF Leaking overview and verification
- Shared L3Out on Common Tenant
- Shared L3Out on different tenants
- Transit Routing
Labs:



- Create a L2Out and consume a GW outside of ACI
- Replicate the config using an EPG extension
- Create a local L3Out
- Create a Shared L3Out
- Advertise routes not owned by ACI
- Configure an L3out to be preferred over other L3Outs
Session 10 - Deployment Models and DevOps


Lecture:



- Naming Convention
- App Centric and Network Centric
- EPG to Bridge Domain to VLAN and Subnet relationship
- Generic VLAN/Subnet to App Driven VLAN/Subnet
- Whitelisting, Blacklisting, and Graylisting
- Benefits and Drawbacks
- Intro to Automation
- Moquery
- API inspector and postman
- Python
- Cobra SDK
Labs:



- Recreating our lab topology thru Python and Postman
Session 11 - Troubleshooting


Lecture:



- Different CLI shells
- Common troubleshooting commands Structure to
- ACI troubleshooting
- Elam and fTriage CLI
- Understanding how to use show zoning rule
- Common faults and mistakes
- L3Out debugging in the ACI world
Labs:



- Use the discussed tools to troubleshoot connectivity issues between endpoints connected to the ACI fabric and end-points connected via L3Out
Session 12 - Multi-Site and Multi-Pod Part 1


Lecture:



- Active/Active, HA, Metro, and DR
- What it means
- How to choose the correct fit based on business requirements
- Multi-pod
- Components
- Requirements
- Fabric forwarding between Pods
- Multi-site
- Components
- Requirements
- Fabric forwarding between sites
- Stretched vs non-stretched
- Understanding Schema
- Intersite L3Outs
- Azure and AWS
Labs:



- Verifying a multi-pod deployment
- Deploying Tenants using MSO
- Configure App Profile and EPGs from MSO
- Create Local and Stretched Bridge Domains
Session 13 - Multi-Site and Multi-Pod Part 2


Lecture:



- Active/Active, HA, Metro, and DR
- What it means
- How to choose the correct fit based on business requirements
- Multi-pod
- Components
- Requirements
- Fabric forwarding between Pods
- Multi-site
- Components
- Requirements
- Fabric forwarding between sites
- Stretched vs non-stretched
- Understanding Schema
- Intersite L3Outs
- Azure and AWS
Labs:



- Verifying a Multi-pod deployment
- Deploying Tenants using MSO
- Configure App Profile and EPGs from MSO
- Create Local and Stretched Bridge Domains
Session 14 - Design and Migration Considerations


Lecture:



- Integrating ACI to legacy environments Migration Steps
- Migration considerations
- FW Considerations
- Where do we place the GWs?
- Designing based on Zones
- To Service Graph or not to Service Graph
- DMZ inside of ACI vs DMZ outside
- Understanding inbound and outbound traffic flow for multi-DC solutions
- Multi-cloud considerations
- LB considerations
- Single or Multi-hop
- GSLB/GTM requirements for multi-DC solutions
Labs:



- Create a DMZ structure inside of ACI connecting to FWs and LBs
- Test Connectivity from the outside world

## Summary
The ACI Elite Series is a series of expert-led 4-hour deep-dive sessions with hands-on lab practice. We cover different topics each week, so you can choose the ones that apply to you.

The program will consist of 14 4-hour sessions, with one scheduled each week. This class is CLC eligible.

Features:



- Live Instructor-led virtual training with hands-on lab practice
- Deep-dive into ACI through 14 self-contained,4-hour sessions
- Runs weekly
- No prior ACI knowledge needed
- For people that need real-world training on ACI
- First class instructors
Benefits:



- Easy to consume 4-hour chunks allow the student to digest contents and ask questions each week
- Modular approach allows students to consume the topics more relevant to their job function and deployment
- Driven by real world scenarios and requirements
- Delivered by an expert on the topic
- After attending this class, you will have the required knowledge to deploy and operate an ACI fabric

## Course Duration
14 days

## Last Changed
2023-03-07T20:14:17.000Z
