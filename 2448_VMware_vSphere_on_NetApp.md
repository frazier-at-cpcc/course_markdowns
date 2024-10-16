# VMware vSphere on NetApp

**Product ID**: 2448
**Category ID**: nan
**Modality**: 1
**Active**: True
**Language**: en
**Product Code**: VVNA
**Vendor Code**: FL
**Vendor Name**: Fast Lane
**URL**: [Course Link](https://www.fastlaneus.com/course/training-vvna)

## Objective
- Discuss ONTAP Architecture and current Hardware
- Describe vSphere Updates in 6.7 & 7.0
- Discuss and install NetApp Tools and interfaces for VMware vSphere
- Discuss NFS datastore deployment Best Practices
- Discuss VMFS datastores

- Discuss iSCSI datastore deployment Best Practices
- Describe FCP datastore deployment Best Practices
- Implement Storage Policy Based Management (SPBM)
- Discuss VVol datastore deployment Best Practices
- Implement Data Storage strategies for Guest VMs
- Discuss Security and Performance considerations in a Multi-tenant environment
- Implement High Availability and Data Protection Strategies in a virtual environment
- Maximize utilization of your storage assets using built-in efficiency features

## Essentials
- System administration experience managing either the Linux or Microsoft Windows operating system
- VMware vSphere: Install, Configure, Manage [V7] (VSICM7) or equivalent experience.
- ONTAP Cluster Administration (ONTAP9ADM) or equivalent experience.

## Audience
- Data Center Operations Professionals
- Cloud Infrastructure Architects
- Cloud Administrators
- Cloud Engineers
- Storage Administrators

## Outline
Module 1: ONTAP Review and What’s New


- New supported Hardware
- Efficiency Enhancements
- Performance Enhancements
- Networking Enhancements
- Data Protection Enhancements
- Management Tools
Module 2: VMware Review and What’s New


- New vCSA, HTML5 “complete”
- ESXi HTML5 host client
- Virtual HW improvements
- VMFS improvements
- VVol improvements
- VMware Tanzu & NetApp
- VMware Cloud on AWS & NetApp
Module 3: NetApp Tools for VMware


- Native VAAI support in ONTAP
- Native UNMAP support in ONTAP
- System Manager AppDM
- ONTAP Tools for VMware 9.11
- VASA Provider (for VVols)
- SRA for SRM
- SnapCenter Plugin
- OCI
- Active IQ Unified Manager
Module 4: NAS Datastores, Classic: Networking & NFS


- Networking Best Practices
- vSphere Networking
- NFS datastores, advantages, prerequisites and how to
- provision them
- NFS 4.1 cautions
Module 5: SAN Datastores, Classic: VMFS


- VMFS datastores, capabilities and limitations
- FC datastores, networking considerations, FCoE
- iSCSI datastores, networking considerations
Module 6: Datastores, Modern: SPBM & VVols


- Storage Policy Based Management (SPBM)
- VASA Provider
- VVol datastores, capabilities and limitations, management
Module 7: Data Storage for VM Guests


- (Mis-)Alignment
- RDMs, advantages and limitations
- NFS Exports
- SMB shares
- FC LUNs (In-Guest)
- iSCSI LUNs (In-Guest iSCSI)
- SCSI timeouts
- BP for MS-Cluster
Module 8: Data Availability, VMware


- VMware RBAC
- High Availability
- Resource Management, DRS
- VMware HA
- VMware FT
- VM Guest Cluster
- Network Contention, NIOC
- Datastore Contention, SDRS
Module 9: NetApp Data Availability


- Security, RBAC, Administration Delegation
- Networking, QoS, A-QoS
- Storage: RAID, HA-pairs, MetroCluster (FC, IP, SDS)
- vSphere Metro Storage Cluster
Labs:


- Quick Explore of the new System Manager
- Create/Check Data Aggregates on both vSims
- Create SVMs
- Quick connectivity check (vCenter Appliance, ESX hosts)
- Quick Exploration of the HTML5 client
- Check preloaded W2K3 VM
- Check preloaded Linux VM
- Set up and test vMotion Network
- Install RBAC User Creator
- Set up VSC (& VASA-P & VAAI plugin)
- Configure Hosts for BP settings
- Create VMkernel interfaces for NFS
- Create Subnets
- Provision NFS datastore through AppDM on AFF
- Install VAAI NFS plugin on ESX hosts
- Provision NFS 4.1 datastore
- Set ESX cluster up for dual subnet iSCSI design
- Create iSCSI SVM on NetApp AFF
- Provision iSCSI datastore through VSC
- Install/set up/verify working VASA provider
- Create SPBM policies for NFS and iSCSI
- Provision NFS datastore through VSC with above created
- SP
- Provision VVol datastore
- Create a NFS export and access it from the Linux VM
- Create a SMB share and access it from the W2K3 VM and
- from the W2K16 DC
- Create a RDM device, attach it to W2K16 VM and access it
- Set up and verify VMware HA
- Set up and check an SVM DR relationship

## Summary
In this course you will learn different methods to implement VMware vSphere 7.0u3 on NetApp ONTAP 9.11. The course provides a quick update on the current ONTAP and VMware versions, introduce the current tools to manage a VMware virtual infrastructure (ONTAP tools for vSphere 9.11) and describe and provide practical exercises to provision datastores and storage for guest VMs with various protocols. It also points administrators to methods to back up their virtual infrastructure according to best practices and discusses methods and tools to manage and monitor for health and performance.

## Course Duration
5 days

## Last Changed
2024-09-13T10:50:10.000Z
