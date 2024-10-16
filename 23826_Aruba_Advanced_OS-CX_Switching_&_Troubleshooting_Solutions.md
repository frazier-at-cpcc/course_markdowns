# Aruba Advanced OS-CX Switching & Troubleshooting Solutions

**Product ID**: 23826
**Category ID**: nan
**Modality**: 1
**Active**: True
**Language**: en
**Product Code**: AAXSTS
**Vendor Code**: AA
**Vendor Name**: Aruba
**URL**: [Course Link](https://www.fastlaneus.com/course/aruba-aaxsts)

## Objective
After you successfully complete this course, expect to be able to:



- Describe diagnostic principles
- Use a proven problem-solving methodology
- Describe REST API, NAE, IP SLA, SNMPv3 and NetEdit troubleshooting tools
- Configure, validate and troubleshoot Network Virtualization features
- Configure and validate PBR
- Deploy and troubleshoot multi-area OSPF
- Deploy and troubleshoot BGP
- Deploy and troubleshoot Route Redistribution
- Deploy and troubleshoot VRF and Route Leaking
- Deploy and troubleshoot Multicast
- Deploy and troubleshoot QoS
- Deploy and troubleshoot Dynamic Segmentation
- Deploy and troubleshoot Network Security
- Deploy and troubleshoot IPv6

## Essentials
The suggested prerequisites for this course are to attend the (!)  course or pass the Aruba Certified Switching Professional (ACSP) certification exam.

## Audience
The ideal candidate for this course is very familiar with Aruba wired switching solutions, including the ability to implement and optimize enterprise level Aruba Switching campus LAN solutions. Typical candidates in the AAXSTS course are preparing for the ACSX written and/or ACSX practical exams.

## Outline
Plan The Wired Network Solutions


- Gather customer requirements and network design
- Information gathering steps and questionnaire
- Create and use a Proof-of-Concept (POC) plan
- Creating and using a golden configuration

Troubleshooting


- Diagnostic Principles

- Troubleshooting Principles
- Troubleshooting Zones
- Troubleshooting Components
- Problem-solving methodology

- Identification and Analysis
- Hypothesis and Validation
- Implement and Verify
- Log files and debugging

- Assess and set desired debugging states
- Remote logging and log rotation
- Event and Account logging
- Password reset
- Diagnostic Commands

- Resource utilization
- Capacities and Environment
- Diagnostic tools and diag on-demand
- Support Files
- Traffic Analysis

- Mirroring concepts and configuration
- Mirroring validation
- Wireshark setup and usage
- Wireshark display filters

Monitoring and Automation Tools


- REST API

- Network Automation and REST API
- REST methods
- Using the REST interface
- Sending REST API Requests

- Swagger resource reference and interface
- cURL CLI tool and library
- Postman
- Network Analytic Engine

- Overview
- Scripts and agents
- Script types and sources
- NAE maximums
- Script components
- Agent functions
- Troubleshooting
- Other Monitoring

- IP SLA use and configuration
- SNMPv3 use and configuration
- NetEdit topology and logs

VSX, VSF, and Layer 2 Technologies


- VSF

- Overview
- Stack requirements
- Member roles and links
- Link failure and split detection
- Split stack link and member failures
- VSF Troubleshooting

- Status and members
- Links and topology
- Removing a VSF member
- VSX

- Overview
- Components
- Aggregation: Single routing model
- Aggegation: Multiplle VRF routing
- Virtual and System MAC guidance
- VSX Best Practices

- Nodes, bandwidth, and ISL
- Roles and synchronization
- LAG and MSTP configuration
- SVI configuration
- VSX Troubleshooting

- Status and LAG interfaces
- Configuration and VSX sync
- Debugging
- Configuration consistency
- Link/interface status
- MAC/peer consistency
- LACP interfaces
- Configuration parser
- VSX Split Brain

- Analyze down conditions and results
- Analyze failure scenarios

Layer 3 Routing and OSPF


- Static Routing

- Overview
- Default route
- Floating static routes
- Static Routes with BFD
- Routes with Tags
- Policy Based Routing

- Overview
- Configuration
- Validation
- VRF
- OSPF Single Area

- Review
- Adjacencies
- Route table vs. diagram
- Neighbor table vs. diagram
- LSDB vs diagram
- LSDB vs network types
- OSPF Multi-area

- OSPF review
- LSA types and usage
- ABRs
- Route aggregation and filtering
- Interface costs
- Passive interfaces
- Authentication
- BFD
- Best practice and troubleshooting review

BGP


- BGP Concepts and Peers

- Use case and features
- Configure BGP peers
- Sessions and states
- eBGP multihop
- iBGP full-mesh
- Validate BGP peers
- BGP Advertisement

- Three key points about BGP advertisements
- iBGP and next-hop-self
- BGP reachability requirement
- The network command
- Aggregate-address command
- BGP Metrics and Tuning

- Path selection criteria
- Prefix lists and route maps
- Weight
- Local Preference
- AS path length
- MED
- Route Control

- Reasons to control eBGP routes
- Route control implementation
- Route control validation
- Inbound route control
- Peer groups
- Route reflectors

Route Redistribution


- Intro to Redistribution

- Overview
- Redistribute static to OSPF
- Static to OSPF configuration and validation
- OSPF Type 1 vs Type 2 routes
- Using and tuning the default metric
- Compare tuning techniques
- Prefix list tuning and validation
- Redistribute OSPF to BGP

- Scenario
- Configuration
- Network statements and route maps
- Advanced Route Redistribution

- Scenario
- AS-path list
- Improve BGP convergence times
- Route tags

VRF and Route Leaking


- VRF Overview and Configuration

- Overview
- Configuration
- Verification
- VRF Route Leaking

- Methods
- Restrictions and limitations
- Static route leaking configuration and validation
- Dynamic route leaking configuration and validation

Multicast


- Multicast

- Introduction
- IP address assignments
- Network Access and L2 Multicast

- Switching multicast frames
- MAC address mapping
- IGMP – v1, v2, v3
- IGMPv3 messages – membership report, querier election,
- IGMPv3 Snooping
- IGMPv3 Configuration and verification
- VSX and IGMPv3
- IP Multicast at Layer 3

- Overview
- Tree types Shared/RP, source/SPF trees
- Group states
- RPF
- PIM

- Versions
- Messages
- PIM-SIM

- Designated Routers
- Rendezvous Point
- Build-up process
- Wireshark analysis
- RP Configuration

- Static RP
- Dynamic RP
- BSR mechanism
- Wireshark analysis
- VSX and PIM
- Multicast Deployment

- Overview
- PIM Configuration
- Multicast Troubleshooting

QoS


- Quality of Service

- Overview
- Traffic characterization
- Differentiated Services model
- AOS-CX QoS processing
- Ingress Stage

- Rate Limiting
- Configuration
- Verification
- Prioritization Stage

- Classifier and Class of service
- Marking and Trust
- Configuration and Verification
- Queuing Stage
- Configuration and verification
- Scheduler Stage

- Strict Priority
- DWRR and WFQ
- Configuration and verification
- Remark QoS

- Configuration
- Verification

Dynamic Segmentation


- Overview

- Objective and benefits
- Port-based vs user-based tunneling
- UBT components
- Understanding UBT

- Tunnel establishment
- Role assignment and redirection
- Infrastructure requirements
- Broadcast and multicast traffic
- Configuration and Wireshark analysis
- Verification commands
- Deployment Using NetEdit

- Configure dynamic segmentation using NetEdit
- Verify dynamic segmentation using NetEdit

Network Security


- Access Control Lists

- Overview
- Applying ACLs
- Object Groups
- ACL verification
- Counting and logging
- ACL resource utilization
- Classifier Policies

- Overview
- Configuration
- Application
- Verification
- Control Plane Policing

- Overview
- Configuration
- Verification
- Local User and Group Management

- Local AAA
- Built-in user groups
- User-defined user groups
- TACACS+ Management

- Remote AAA using TACACS+
- Communication with TACACS+ server
- Configure and verify AAA using TACACS+
- DHCP Snooping and ARP Inspection

- DHCP snooping configuration and verification
- Dynamic ARP operation, configuration, and verification

IPv6


- IPv6

- Features
- Headers
- Extension headers
- Address representation
- Address Types

- Unicast
- Multicast
- Anycast
- ICMPv6

- Overview
- Neighbor discovery
- Manual IPv6 Addressing

- Configuration
- Verification
- DAD
- Dynamic IPv6 Addressing

- Router Advertisements
- SLAAC
- DHCPv6
- IPv6 Routing

- Static
- OSPFv3
- IPv6 Access Control Lists

- Configuration
- Verification

## Summary
This course is structured to help the candidate gain this highest level of expertise, with Aruba wired switching solutions, including the ability  to implement and optimize enterprise level Aruba Switching campus LAN solutions. The course focuses on interpreting complex network architectures and customer requirements to implement, monitor, troubleshoot, and optimize multi-vendor network solutions. This course is approximately 30% lecture and 70% hands-on lab scenariobased exercises.
The candidate is encouraged to use critical thinking skills to resolve complex issues in the environments that are beyond the expertise of the professional level integrator. During the performance of his/her primary tasks, the candidate is encouraged to also demonstrate the highest level of strategic thinking and problem solving. This will include defining operational plans for desired outcomes for the purpose of satisfying immediate requirements as well as anticipated future growth opportunities.

## Course Duration
5 days

## Last Changed
2024-06-22T01:35:22.000Z
