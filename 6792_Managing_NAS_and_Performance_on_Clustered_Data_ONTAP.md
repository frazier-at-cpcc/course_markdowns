# Managing NAS and Performance on Clustered Data ONTAP

**Product ID**: 6792
**Category ID**: nan
**Modality**: 1
**Active**: True
**Language**: en
**Product Code**: NASPAD
**Vendor Code**: nan
**Vendor Name**: NetApp
**URL**: [Course Link](https://www.fastlaneus.com/course/netapp-naspad)

## Objective
- Define and describe NFS protocol versions
- Configure clustered ONTAP 9 for NFSv3,NFSv4,and NFSv4.1 with parallel NFS (pNFS)
- Configure Kerberos in a Linux and NetApp ONTAP 9 environment using Windows Active Directory authentication
- Discuss performance management and troubleshooting for NetApp storage systems and clients
- Explain the CIFS and SMB protocol
- Demonstrate the Windows PowerShell CLI
- Configure SMB features using ONTAP 9 software
- Create and manage SMB shares and sessions
- Secure SMB sessions
- Configure ONTAP for multiprotocol data access
- Discuss SMB advanced topics, such as opportunistic locks (oplocks), BranchCache, auditing, group policy, automatic home shares, symbolic links (symlinks), and widelinks
- Understand how a storage system running ONTAP 9 functions
- Identify the commands and tools to use to collect and monitor storage system performance
- Interpret performance data and identify hindrances to storage system performance
- Use system commands and features to enhance storage system performance and efficiency

## Essentials
- ONTAP Cluster Administration and Data Protection Bundle (CDOTDP9)
- Familiarity with Microsoft Windows Server 2012
- Familiarity with Microsoft Active Directory
- Familiarity with UNIX and Linux operating systems

## Audience
Professionals who manage NetApp storage systems and need a deeper understanding of protocols and performance in a clustered Data ONTAP environment.

## Outline
Module 1: NFS Overview 


- Data fabric layers
- NFS
- NFS protocol versions 
- NFSv2 and NFSv3
- Ancillary protocols
- NFSv4
- ONTAP 9 NFS enhancements
- ONTAP 9 configuration
- SVM with Infinite Volume
Module 2: NFS Version 3 


- Capabilities
- Features
- Client support
- NFSv3 implementation
- NFSv3 export policy
- Export policies and volumes
- Access cache
- Mounts
- User authentication
- Accounts
- Auxiliary GIDs
- ANON setting
- UNIX permissions
Module 3: NFS Version 4 


- Features
- NFSv4 connection
- Mount process
- Referrals
- Delegation and usage
- NFSv4 Implementation
- Security 
- RPCSEC_GSS
- Key distribution center
- Kerberos authentication
- Access control lists
- ACE permissions
- NFSv4 infrastructure
- UID and GID
- Snapshot directories
Module 4: NFS Version 4.1 


- Connection
- Reliable callbacks
- Sessions
- Layouts
- pNFS
- pNFS vs. referrals
- ONTAP 9 support
- NFSv4.1 implementation
- pNFS status
Module 5: Performance and Basic Troubleshooting 


- Performance management
- Performance issues
- Factors that affect NFS performance
- RAID factors
- NFS data collection
- Performance and statistic collector (Perfstat)
- Recommended statistics
- The SIO utility
- Multiprotocol
- Security style interaction
- UNIX user access
- Storage system configuration
- Linux client troubleshooting
- NFS troubleshooting
- Network troubleshooting
- Check access command
Module 6: SMB Overview


- Data fabric
- Data fabric layers
- CIFS and SMB protocols
- NT LAN manager
- Kerberos authentication
- Active Directory
- Workgroup environments
- NetApp PowerShell toolkit
Module 7: SMB Setup


- SMB implementation
- Licensing CIFS
- SVM for SMB access
- FlexVol volumes
- DNS entries for the SVM
- SMB share access
Module 8: SMB Shares and Sessions


- SMB share
- Creating a share
- Client access
- SMB automatic referrals
- SMB sessions
- Session administration
- SMB encryption
- Offline folders
- Offloaded data transfer
Module 9: Access Control


- Share permission administration
- Access-based enumeration
- Dynamic access control
- File blocking policies
- Local users
- Workgroup authentication
- Multiprotocol access
Module 10: Advanced Topics


- Microsoft opportunistic Lock (oplock) features
- Automatic home share
- Group policy object (GPO)
- Symlinks
- Widelinks
Module 11: BranchCache


- Versions
- BranchCache environment configurations
- ONTAP 9 BranchCache
- BranchCache installation on Windows Servers
- BranchCache configuration  on Windows clients
Module 12: Auditing


- Auditing concepts
- Terminology
- ONTAP 9 auditing process
- Implement auditing
- Output file format
Module 13: How a NetApp Storage System Works


- NetApp FAS system architecture
- ONTAP architecture layers
- Data access
- NVRAM
Module 14: Performance Analysis Tools


- Performance terminology
- Performance guidelines and methodologies
- Analysis tools and commands
- Output commands
- Tools for performance measurement
- AutoSupport tools
- Perfstat
- OnCommand Insight
Module 15: OnCommand Performance Manager


- Features
- Dashboard
- Performance troubleshooting
- Events
- User defined thresholds
Module 16: CPU and Memory Performance


- CPU performance bottlenecks
- Resolving bottlenecks
- Memory performance bottlenecks
- Resolving bottlenecks
Module 17: WAFL Performance


- WAFL functions
- Inodes
- WAFL readahead
- Resolving WAFL issues
- Best practices
Module 18: Disk I/O Performance


- Disk subsystem hardware and software
- Subsystem bottlenecks
- Analyzing bottlenecks with Statit
- Resolving bottlenecks
- RAID-DP technology
Module 19: Flash Cache and Flash Pool Performance


- Virtual Storage tier
- Flash pool
- Flash cache
- Automatic workload analyzer
- Cache performance issues
Module 20: Cluster Interconnect Performance


- Cluster interconnect uses
- Switchless and switched configurations
- Cluster interconnect bottlenecks
- Bottleneck resolutions

Module 21: Storage QoS



- Managing system performance with QoS
- QoS policies
- Reactive storage QoS
- Proactive storage QoS
- Monitoring commands
Module 22: NAS Performance


- NAS functions
- Bottlenecks
- NAS protocol traffic
- Monitoring NFS usage commands
- Monitoring SMB usage commands
- Bottleneck resolutions
Module 23: SAN Performance


- SAN overview
- Protocols
- FCoE
- iSCSI
- SAN LIFs
- SAN performance issues
- SAN multipathing
- SAN load balancing
- I/O misalignment
- Queue depth
Module 24: Using What You Learned


- Performance overview
- Performance tools
- Windows monitoring and analysis
- Linux monitoring and analysis
- VMware monitoring and analysis
- Slow application performance
- Using performance manager
- Best practices

Labs


- Adding a cluster
- Configuring a storage virtual machine for NFSv3
- Configuring a storage virtual machine for NFSv4
- Configuring a storage virtual machine for NFSv4.1
- Configure clustered ONTAP for NFS active directory authentication
- Configuring Windows for NFS active directory authentication
- Configuring Linux for NFS active directory authentication
- Installing NetApp PowerShell Toolkit and configure for use
- Creating a Storage Virtual Machine (SVM) and configure it for SMB access
- Creating an SMB share, connect to the share from your Windows client, and manage SMB sessions
- Creating a domain user, restrict share-level permissions
- Creating a local user group and give share-level permissions
- Creating a multiprotocol configuration and enable a root Linux user to be mapped to the Windows domain administrator
- Configuring home directories and symbolic links on the SVM
- Identifying cluster components
- Analyzing performance statistics
- OnCommand performance manager thresholds, events and alerts
- Identifying and resolving storage controller performance issues
- WAFL performance monitoring and analysis
- Identifying and resolving disk I/O bottlenecks
- Exploring cache performance
- Cluster interconnect performance
- Workload management with storage QoS
- NAS performance
- SAN protocol performance

## Summary
NOTE: This course combines the 1 day ONTAP NFS Administration (NFSAD), a 1 day version of ONTAP SMB Administration (CIFSAD) and the 3 day ONTAP Performance Administration (PERFCDOT) courses. By signing up for this package, you have the flexibility to take all 3 courses in the same week or take each individual course when it fits into your schedule.


Attend this Fast Lane course and experience a 1:1 student to lab ratio

Note: ONTAP SMB Administration (CIFSAD) may be delivered as a 2 day class by other NetApp partners, however Fast Lane is currently offering as a 1 day class.

## Course Duration
5 days

## Last Changed
2024-09-13T10:49:40.000Z
