# Using SLES for SAP Applications 15 to Provide High Availability for S/4HANA and Netweaver

**Product ID**: 33186
**Category ID**: nan
**Modality**: 1
**Active**: True
**Language**: en
**Product Code**: SLE322V15
**Vendor Code**: SU
**Vendor Name**: SUSE
**URL**: [Course Link](https://www.fastlaneus.com/course/suse-sle322v15)

## Objective
Attendees will be taught the following concepts and skills:



- Overview of the SAP Enqueue Server
- Preparation tasks required for a successful deployment
- Configuration of the required storage for the Enqueue Server in an HA environment
- Tuning of the cluster nodes to host the Enqueue and Enqueue Replication Server
- Integration of SAP into the cluster framework using the sap_suse_cluster_connector
- Deployment of the cluster and configure the required cluster resources
- How to design and perform cluster tests
- Monitoring of the cluster and perform day 2 management tasks specific to a cluster hosting the Enqueue Server

## Essentials
Attendees should have knowledge of SLES equivalent to the SCA in SUSE Linux Enterprise Sever level along with an in-depth understanding of the SUSE Linux Enterprise High Availability Extension or general High Availability concepts. This course does not require any specific SAP product knowledge.

## Audience
Administrators tasked with administering systems running S/4HANA or SAP applications hosted on the NetWeaver ABAP platform who require a high availability solution for the Enqueue Server hosted on a SLES for SAP Applications HA cluster. The configuration of a cluster hosting ENSA1 will be compliant with the SAP NW-HA-CLU 7.40 certification and a cluster hosting ENSA2 will be compliant with the SAP S/4-HA-CLU 1.0 certification.

## Outline
Section 1: Course Introduction



- Course Objectives and Audience
- Course Lab Environment Overview
- Certification Options
- Additional SUSE Training
Section 2: Overview of the Enqueue Server



- What is the Enqueue Server?
- The Standalone Enqueue Server
- The Enqueue Replication Server
- Architectural Overview of ENSA1
- Architectural Overview of ENSA2
Section 3: Preparing to Deploy the Enqueue Server with High Availability



- Overview of the Required Software
- Access the SAP Media Sets
- Overview of the Installation Process
- SAP NetWeaver Directory Structure on Linux
- Configure Storage for the Enqueue Server in an HA Environment
- Configure Name Resolution for the ASCS and ERS Instances
- Create the Linux Users for the ASCS and ERS Instances
- Install the Enqueue and Enqueue Replication Servers
Section 4: Tuning SLES for SAP Applications to Host a SAP NetWeaver Workload



- Use saptune to Tune a Host for the SAP NetWeaver Workload
Section 5: Deploy and Configure SLES for SAP Applications to Host the Enqueue Server with High Availability



- Deploy the SLE HA Cluster
- Adapt the SAP Profiles to Match the SAP Certification
- Integrate the Cluster Framework with sap-suse-cluster-connector V3.x
- Adapt the SAP Profiles to Match the SAP Certification
- Create and Configure the Cluster Resources for ENSA2
- Overview of a Multi-SID Central Services Cluster Configuration
Section 6: Designing and Performing Cluster Tests



- Design Cluster Tests
- Understand the Tasks and Tools Used for Testing
- Plan and Perform Cluster Tests
Section 7: Monitoring and Administering the HA Solution



- Monitor the HA Components
- Monitor the SAP Enqueue Servers
- Recovery Procedures after a Fail Over
- Applying a Rolling SAP Kernel Switch
- Manage and Deploy System Updates
- Log Files
- Administering the Cluster

## Summary
This course is designed to enable you to deploy the SAP Enqueue Replication Server with High Availability using SLES for SAP Applications. The course uses SUSE best practices leading to a deployment that complies with the SAP certification NW-HA-CLU 7.40 for ENSA1 and S/4-HA-CLU 1.0 for ENSA2. First the Enqueue Server is introduced along with an architectural overview. Next the environment required for the deployment is explored including the storage requirements for deploying the enqueue server with high availability. The preparation is followed by tuning the systems for the SAP workload, creating and configuring the required cluster resources and integrating the SAP environment with the HA environment using the sap_suse_cluster_connector. Cluster tests are then planned and executed, the cluster monitored and best practice administration tips provided.





This course helps prepare students for the SCE in SLES for SAP Applications - Part 1 exam.

## Course Duration
3 days

## Last Changed
2024-09-13T19:25:52.000Z
