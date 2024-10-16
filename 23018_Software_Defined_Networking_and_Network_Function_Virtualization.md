# Software Defined Networking and Network Function Virtualization

**Product ID**: 23018
**Category ID**: nan
**Modality**: 6
**Active**: True
**Language**: en
**Product Code**: SDN/NFV
**Vendor Code**: A3
**Vendor Name**: Alta3
**URL**: [Course Link](https://www.fastlaneus.com/course/23018)

## Objective
nan

## Essentials
No Prerequisites.


Follow-On Courses include: 


- (!)
- (!)
- (!)

## Audience
nan

## Outline
1. SDN Introduction 


- Southbound Interface and Northbound Interface
- Data Plane
- Control Plane
- Problems with the current distributed Control Plane design
- Problems solved by the Centralized Control Plane
- Data Plane
- Management Plane Functions
- Northbound API Abstractions
2. NFV Practical Application 


- Universal Data Center Options
- Cisco Data Center Options
- NSX VMware Data Center Options
- OpenStack Data Center Options
3. NFV 


- NFV Terminology
- NFV Architecture
- NFV Reference Points
- Service Function Chaining Architecture (RFC 7665)
4. NFV Commands 


- net-tools vs iproute2
- iproute2
- Linux Network Devices
- Bridging namespaces
- Bridging VMs
- Forwarding Logic
- mininet
- ip neigh
- ip2
- ovs vsctl
- TCPDUMP
- Troubleshooting
5. OpenFlow 


- OpenDaylight Soutbound APIs
- Active Networking
- ForCES Architecture
- Clean Slate
- Layers - API vs Control vs Infrastructure
- Switch Specification
- Linux Installation and Deployment
- Components
- Main Components the Switch and Controller
- Traditional L2
- Basic Operations and Messages
- Flow Table
- Review of OpenFlow Specification (current or 1.1.0, Wire Protocol 0x02)
- Flow Tables, Pipeline Processing
- Group Table, Matching, Instructors
- Segment Routing
6. Open vSwitch 


- Architecture and Components
- OpenvSwitch Daemon
- ovsdb-server
- Core Tables
- Linux Bridge vs. OpenvSwitch Design
- Ovs-ofctl, ovs-dpctl
- Traditional VM Ethernet Processing
- Intel DPDK intro
- Intel SR-IOV
- OVS Kernel Module
- Intel DPDK Effect
- ovs-vswitchd.conf.db(5)
7. OpenFlow Controller 


- Northbound vs. Southbound Interfaces
- RYU SDN Framework
8. NETCONF and YANG 


- Overview of Network Configuration
- Introduction to SDN with NETCONF
- Introduction to SDN with YANG
- SDN Programming with YANG
- SDN Programming with NETCONF
- VPN Scenario
- RFC 7149
9. OpFlex 


- Introduction
- Group Policy
10. Introduction to OpenDaylight 


- Fundamentals for OpenDaylight Programming
- Setup
- OSGI
- Fundamentals – Maven and Project Building
- Apache Karaf
- Fundamentals – Mininet
11. SAL 


- Controller Functionality
- Standardization
12. OpFlex 


- Big Picture Diagramming
13. SAL 


- Standardization
- Restful Interface YANG
- Model Driven Service Abstraction Layer
- Network Abstraction
- Alto Protocol
- Fabric as a Service
- Network Modeling Language NEMO
- Group Based Policy Service Example
14. Overlays and Underlays 


- Architecture for Overlay Networks (draft-ietf-nvo3-arch-04)
- Security Requirements of NVO3 (draft-ietf-nvo3-security-requirements-07)
15. OpenStack Neutron Networking 


- Bare Metal Interfaces
- OpenvSwitch
- Type Drivers – VLAN
- Neutron Network Types
- Type Drivers – VXLAN
- Neutron Network Types – Overlay Networks
- Neutron Subnets
- Neutron Subnet Pool
- Neutron Routers
- Neutron Network Types – Overlay Networks
- Neutron Ports
- Neutron Namespaces
- Architecture
- Linux Bridge
- neutron-server
- Neutron Security Group
- neutron-server – ML2Plugin
- neutron-server – L3 Agent
- neutron-server – OVS L2 Agent
16. Writing an Application Using OpenDaylight 


- Writing an Application Using OpenDaylight
- Restful Interface
17. ONOS Controller 


- East-West ONOS Cluster
- Shared Aggregate Network Topology
- Provider Clustering Diagram
- ONOS0
- ONOS1
- Ecosystem
- Control and Data Planes
- Network Slicing
- Versions
18. Securing SDN 


- Securing the Controller
- Security Challenges
- Security Principles
- Attack Model
SDN Labs 


- Lab 1: Linux iproute2 - Linux is standardly equipped with most of the NFV components, let’s learn the basics first.
- Lab 2: NFV debugging tools
- Lab 3: Virtual Interfaces
- Lab 4: Linux Bridge
- Lab 5: ADVANCED – Augmenting bash for working with Network Namespaces
- Lab 6: Open vSwitch (OVS)
- Lab 7: Wireshark set up for SDN Protocol analysis
- Lab 8: Introduction to Mininet
- Lab 9: Using MiniEdit to create custom MiniNet Topologies
- Lab 10: Mininet Namespaces – Learning About Linux Network Namespaces
- Lab 11: ADVANCED – SDN Topology Analysis Using Python
- Lab 12: Detailed Wireshark analysis of live OpenFlow Traffic
- Lab 13: OPTIONAL – Using vim
- Lab 14: Introducing the Controllers (Ryu)
- Lab 15: Writing a FlowMod to Handle a Table-Miss – Controller Application (ryu-app)
- Lab 16: PacketIn Hub Logic with an SDN (Ryu)
- Lab 17: Deploying Simple Switch Logic with an SDN (Ryu)
- Lab 18: Deploying Simple Switch Logic with an SDN (Ryu) Part 2
- Lab 19: Neutron Networking. All labs leading up to this point are mandatory to understand this lab.

## Summary
In this course, students learn Software Defined Network architecture and the important protocols related to SDN implementations. This course thoroughly explains what SDN is, how it works, and then does a deep dive into the SDN protocols themselves. SDN can both manage and control physical network elements as well as Network Function Virtualization, allowing network professionals to deploy and maintain a clean integration between cloud environments and the physical network itself.

Often we are asked by network personnel to teach them what the network looks like when it enters the cloud. This is why the study of Network Function Virtualization is a natural progression in this type of study, so we have included both SDN and NFV in one course. This course will clarify what happens at the cloud boundary and then look into the virtual network within the cloud itself. If you are already a networking professional and you take a look at what is going on inside the cloud, you will learn that there is no reason not to take all those good ideas and implement them outside the cloud. The networking control layer as you may currently understand it, will change radically with SDN. We will show you that the change is both amazing and powerful.

In this course, you will build, configure, and deploy the most popular network functions, routing, bridging, and OpenFlow switches along with requisite protocols. You will integrate these components with an emulated physical environment and perform verification testing. The cloud environment will be represented with a *very* deep dive into OpenStack Neutron and Neutron-compute.

## Course Duration
5 days

## Last Changed
2024-08-22T19:39:09.000Z
