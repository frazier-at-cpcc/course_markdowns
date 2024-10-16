# Junos MPLS Fundamentals

**Product ID**: 12712
**Category ID**: nan
**Modality**: 1
**Active**: True
**Language**: en
**Product Code**: JMF
**Vendor Code**: JP
**Vendor Name**: Juniper Networks
**URL**: [Course Link](https://www.fastlaneus.com/course/juniper-jmf)

## Objective
- Explain the reasons MPLS was originally created, and the applications offered by label-switched paths.
- Describe the structure of an MPLS label, the mechanics of the data plane, and the protocols that can advertise labels.
- Configure static LSPs, verify the routing tables they populate, and explain the label actions these LSPs perform.
- Explain the purpose and advantages of RSVP, then configure a service provider network to host RSVP LSPs.
- Configure and verify a basic RSVP label-switched path.
- Explain the purpose of the MPLS traffic engineering database, and create LSPs that use this database to calculate a path.
- Explain the purpose of RSVP bandwidth reservations, and how to configure an LSP to reserve bandwidth.
- Explain the use-cases for RSVP LSP priority levels, and configure different priority levels of a variety of LSPs.
- Explain how the Constrained Shortest-Path First algorithm can calculate trafficengineered paths.
- Explain the messages involved in tearing down, rerouting, and maintaining LSPs and RSVP sessions.
- Describe how primary and secondary paths can be used in times of link and node failure.
- Describe the advantages of RSVP local repair paths, and how to configure the
one-to-one method of local repair, otherwise known as fast reroute.
- Explain the mechanics, configuration, and verification of facility backup, otherwise known as link protection and node-link protection.
- Explain how RSVP LSPs can automatically find and signal better, more optimal paths.
- Explain how LSPs can gracefully move traffic to new paths with no downtime to the user.
- Explain the mechanics by which LDP creates a full mesh of label-switched paths.
- Configure and verify a basic LDP deployment in a service provider network.
- Describe some important LDP enhancements and best practices that increase the integrity of real-world LDP deployments.
- Explain how to configure LDP to advertise labels for more than just a router's loopback.
- Explain how segment routing differs from RSVP and LDP, and configure segment routing as a replacement for LDP.

## Essentials
- Strong general TCP/IP knowledge;
- knowledge of Junos OS to the JNCIA-Junos certification level; and
- Knowledge of routing and switching to the JNCIS-SP certification level.
- The following courses or equivalent knowledge:


Getting Started with Networking online course


Introduction to the Junos Operating System course


Junos Intermediate Routing course


Junos Enterprise Switching course, Junos Service Provider Switching course, or both

## Audience
- Individuals responsible for designing, implementing, and troubleshooting MPLS networks that make use of RSVP and LDP as the signaling method for the creation of LSPs;
- Individuals who work with, or who aspire to work with, service provider networks;
- Individuals studying for the JNCIS-SP certification exam; and
- Individuals who have already passed the JNCISSP certification exam, and want to revise these concepts before attempting the JNCIE-SP certification exam

## Outline
Day 1

Chapter 1: Course Introduction

Chapter 2: MPLS—Introduction


- Describe the BGP remote next-hop mechanic, and hop-by-hop forwarding
- Explain the original historical motivations for MPLS
- List the alternative modern use cases for MPLS
Chapter 3: MPLS—The Mechanics


- Explain how labels are built, and how they flow between routers
- Describe the end-to-end data plane of a packet across a label-switched path
- Summarize the four primary protocols that can build label-switched paths
Chapter 4: MPLS—Static LSPs and the Forwarding Plane


- Configure a service provider’s edge and core devices for MPLS
- Configure the headend router of an LSP and explain the impact this has on the router's inet.3 table
- Configure transit routers and verify their mpls.0 tables
- Lab 1: Static LSPs and the Forwarding Plane
Chapter 5: RSVP—Introduction


- Explain the purpose, features, and advantages of RSVP
- Configure a service provider network to be ready to host RSVP label-switched paths
Chapter 6: RSVP—Configuring A Basic LSP


- Configure and verify an RSVP label-switched path that follows the metrically best path
- Explain the purpose of MPLS self-ping
- Explain how an RSVP LSP is signaled and created
Chapter 7: RSVP—The Traffic Engineering Database


- Describe the purpose of the IS-IS/OSPF traffic engineering extensions
- Configure and verify an LSP that uses the traffic engineering database to calculate its path
- Explain the impact that loose and strict hops can have on an LSP
- Lab 2: RSVP LSPs

Day 2

Chapter 8: RSVP—LSP Bandwidth Reservation


- Describe the use cases for RSVP bandwidth reservations, and the Path message objects that are used
- Configure LSP bandwidth reservations, and verify how these reservations are advertised
Chapter 9: RSVP—LSP Priorities


- Describe problems that can be caused by RSVP LSP bandwidth reservations, and the solution offered by priority levels
- Describe the default RSVP LSP priority levels, and configure alternative settings
- Configure LSP soft preemption to avoid downtime
- Lab 3: RSVP—LSP Bandwidth and Priorities
Chapter 10: RSVP—Constrained Shortest Path First, and Admin Groups


- Describe the CSPF algorithm, along with its tie breakers
- Configure and verify admin groups on LSPs
Chapter 11: RSVP—LSP Failures, Errors, and Session Maintenance


- Describe the events that can tear down an LSP, and the RSVP messages that make it happen
- Describe how RSVP has changed over the years from a soft-state protocol to a reliable stateful protocol
Chapter 12: RSVP—Primary and Secondary Paths


- Explain the use cases and configuration for primary and secondary paths
- Identify the benefits and trade-offs of standby secondary paths
- Show the advantage of pre-installing backup paths to the forwarding table
Chapter 13: RSVP—Local Repair, Part 1—One-to-One Backup or Fast Reroute


- Demonstrate the downtime that can be caused by a link or node failure in an MPLS network, and how a local repair path can significantly reduce this downtime
- Explain the mechanics of the one-to-one backup method
- Explain the many different meanings of the term “fast reroute”
- Configure and verify the one-to-one backup method of local repair
Chapter 14: RSVP—Local Repair, Part 2—One-to-One Backup or Fast Reroute


- Demonstrate the downtime that can be caused by a link or node failure in an MPLS network, and how a local repair path can significantly reduce this downtime
- Explain the mechanics of the one-to-one backup method
- Explain the many different meanings of the term “fast reroute”
- Configure and verify the one-to-one backup method of local repair
- Lab 5: RSVP—One-to-One Backup and Facility Backup

Day 3


Chapter 15: RSVP—LSP Optimization


- Describe the LSP optimization algorithm and how to configure this feature
Chapter 16: RSVP—Make-Before-Break and Adaptive


- Describe the make-before-break mechanic, and list the features that use this mechanic by default
- Explain how shared explicit signaling can prevent double-counting of bandwidth, and configure this feature for all other LSPs
Chapter 17: LDP—The Label Distribution Protocol


- Describe the key features, advantages, and trade-offs of LDP
- Explain the particular methods by which LDP generates and advertises MPLS labels
Chapter 18: LDP—Configuration


- Configure a basic LDP deployment, and describe the protocol messages that this configuration generates
- Verify the interface messages, sessions, and labels that this configuration generatesLab 4: RSVP— Primary and Secondary Paths
Chapter 19: LDP—Enhancements and Best Practices


- Explain the LDP-IGP Synchronization feature that reduces dropped packets during topology changes
- Describe how the BGP next-hop resolution process can be altered in LDP
- Configure session protection to improve the integrity of LDP during network failure
Chapter 20: LDP—Egress, Import, and Export Policies


- Configure and verify LDP egress policies to advertise any FEC of your choosing
- Configure and verify LDP import and export policies to limit the distribution of FECs
- Lab 6: LDP—Label Distribution Protocol
Chapter 20: Appendix: Segment Routing

## Summary
This three-day course provides students with the knowledge required to design, implement, and troubleshoot the most crucial elements of a modern
MPLS deployment in a real-world service provider production network. This course includes extensive coverage of the RSVP and LDP protocols, and
an introductory appendix on MPLS segment routing. Technologies covered include the MPLS data plane, RSVP bandwidth and priorities, backup and
local repair paths, label-switched path (LSP) optimization, LDP enhancements and best practices, and a dedicated module on troubleshooting. The
course offers optional appendices on RSVP auto-bandwidth, and a wide variety of advanced RSVP features. Students will gain experience with all of
these protocols and features through a combination of detailed instructor training and hands-on labs. This course is based on Junos OS Release
21.4R1.12

## Course Duration
3 days

## Last Changed
2024-09-05T10:07:08.000Z
