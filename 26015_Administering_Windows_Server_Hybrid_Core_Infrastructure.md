# Administering Windows Server Hybrid Core Infrastructure

**Product ID**: 26015
**Category ID**: nan
**Modality**: 1
**Active**: True
**Language**: en
**Product Code**: AZ-800T00
**Vendor Code**: MS
**Vendor Name**: Microsoft
**URL**: [Course Link](https://www.fastlaneus.com/course/microsoft-az-800t00)

## Objective
- Use administrative techniques and tools in Windows Server.
- Identify tools used to implement hybrid solutions, including Windows Admin Center and PowerShell.
- Implement identity services in Windows Server.
- Implement identity in hybrid scenarios, including Azure AD DS on Azure IaaS and managed AD DS.
- Integrate Azure AD DS with Azure AD.
- Manage network infrastructure services.
- Deploy Azure VMs running Windows Server, and configure networking and storage.
- Administer and manage Windows Server IaaS Virtual Machine remotely.
- Manage and maintain Azure VMs running Windows Server.
- Configure file servers and storage.
- Implement File Services in hybrid scenarios, using Azure Files and Azure File Sync.

## Essentials
Before attending this course, students must have:


- Experience with managing Windows Server operating system and Windows Server workloads in on-premises scenarios, including AD DS, DNS, DFS, Hyper-V, and File and Storage Services
- Experience with common Windows Server management tools (implied in the first prerequisite).
- Basic knowledge of core Microsoft compute, storage, networking, and virtualization technologies (implied in the first prerequisite).
- Experience and an understanding of core networking technologies such as IP addressing, name resolution, and Dynamic Host Configuration Protocol (DHCP)
- Experience working with and an understanding of Microsoft Hyper-V and basic server virtualization concepts
- Basic experience with implementing and managing IaaS services in Microsoft Azure
- Basic knowledge of Azure Active Directory
- Experience working hands-on with Windows client operating systems such as Windows 10 or Windows 11
- Basic experience with Windows PowerShell

## Audience
This four-day course is intended for Windows Server Hybrid Administrators who have experience working with Windows Server and want to extend the capabilities of their on-premises environments by combining on-premises and hybrid technologies. Windows Server Hybrid Administrators implement and manage on-premises and hybrid solutions such as identity, management, compute, networking, and storage in a Windows Server hybrid environment.

## Outline
Module 1: Identity services in Windows Server

This module introduces identity services and describes Active Directory Domain Services (AD DS) in a Windows Server environment. The module describes how to deploy domain controllers in AD DS, as well as Azure Active Directory (AD) and the benefits of integrating Azure AD with AD DS. The module also covers Group Policy basics and how to configure group policy objects (GPOs) in a domain environment.

Lessons


- Introduction to AD DS
- Manage AD DS domain controllers and FSMO roles
- Implement Group Policy Objects
- Manage advanced features of AD DS
Lab: Implementing identity services and Group Policy


- Deploying a new domain controller on Server Core
- Configuring Group Policy
After completing this module, students will be able to:


- Describe AD DS in a Windows Server environment.
- Deploy domain controllers in AD DS.
- Describe Azure AD and benefits of integrating Azure AD with AD DS.
- Explain Group Policy basics and configure GPOs in a domain environment.
Module 2: Implementing identity in hybrid scenarios

This module discusses how to configure an Azure environment so that Windows IaaS workloads requiring Active Directory are supported. The module also covers integration of on-premises Active Directory Domain Services (AD DS) environment into Azure. Finally, the module explains how to extend an existing Active Directory environment into Azure by placing IaaS VMs configured as domain controllers onto a specially configured Azure virtual network (VNet) subnet.

Lessons


- Implement hybrid identity with Windows Server
- Deploy and manage Azure IaaS Active Directory domain controllers in Azure
Lab: Implementing integration between AD DS and Azure AD


- Preparing Azure AD for AD DS integration
- Preparing on-premises AD DS for Azure AD integration
- Downloading, installing, and configuring Azure AD Connect
- Verifying integration between AD DS and Azure AD
- Implementing Azure AD integration features in AD DS
After completing this module, students will be able to:


- Integrate on-premises Active Directory Domain Services (AD DS) environment into Azure.
- Install and configure directory synchronization using Azure AD Connect.
- Implement and configure Azure AD DS.
- Implement Seamless Single Sign-on (SSO).
- Implement and configure Azure AD DS.
- Install a new AD DS forest on an Azure VNet.
Module 3: Windows Server administration

This module describes how to implement the principle of least privilege through Privileged Access Workstation (PAW) and Just Enough Administration (JEA). The module also highlights several common Windows Server administration tools, such as Windows Admin Center, Server Manager, and PowerShell. This module also describes the post-installation confguration process and tools available to use for this process, such as sconfig and Desired State Configuration (DSC).

Lessons


- Perform Windows Server secure administration
- Describe Windows Server administration tools
- Perform post-installation configuration of Windows Server
- Just Enough Administration in Windows Server
Lab: Managing Windows Server


- Implementing and using remote server administration
After completing this module, students will be able to:


- Explain least privilege administrative models.
- Decide when to use privileged access workstations.
- Select the most appropriate Windows Server administration tool for a given situation.
- Apply different methods to perform post-installation configuration of Windows Server.
- Constrain privileged administrative operations by using Just Enough Administration (JEA).
Module 4: Facilitating hybrid management

This module covers tools that facilitate managing Windows IaaS VMs remotely. The module also covers how to use Azure Arc with on-premises server instances, how to deploy Azure policies with Azure Arc, and how to use role-based access control (RBAC) to restrict access to Log Analytics data.

Lessons


- Administer and manage Windows Server IaaS virtual machines remotely
- Manage hybrid workloads with Azure Arc
Lab: Using Windows Admin Center in hybrid scenarios


- Provisioning Azure VMs running Windows Server
- Implementing hybrid connectivity by using the Azure Network Adapter
- Deploying Windows Admin Center gateway in Azure
- Verifying functionality of the Windows Admin Center gateway in Azure
After completing this module, students will be able to:


- Select appropriate tools and techniques to manage Windows IaaS VMs remotely.
- Explain how to onboard on-premises Windows Server instances in Azure Arc.
- Connect hybrid machines to Azure from the Azure portal.
- Use Azure Arc to manage devices.
- Restrict access using RBAC.
Module 5: Hyper-V virtualization in Windows Server

This modules describes how to implement and configure Hyper-V VMs and containers. The module covers key features of Hyper-V in Windows Server, describes VM settings, and how to configure VMs in Hyper-V. The module also covers security technologies used with virtualization, such as shielded VMs, Host Guardian Service, admin-trusted and TPM-trusted attestation, and Key Protection Service (KPS). Finally, this module covers how to run containers and container workloads, and how to orchestrate container workloads on Windows Server using Kubernetes.

Lessons


- Configure and manage Hyper-V
- Configure and manage Hyper-V virtual machines
- Secure Hyper-V workloads
- Run containers on Windows Server
- Orchestrate containers on Windows Server using Kubernetes
Lab: Implementing and configuring virtualization in Windows Server


- Creating and configuring VMs
- Installing and configuring containers
After completing this module, students will be able to:


- Install and configure Hyper-V on Windows Server.
- Configure and manage Hyper-V virtual machines.
- Use Host Guardian Service to protect virtual machines.
- Create and deploy shielded virtual machines.
- Configure and manage container workloads.
- Orchestrate container workloads using a Kubernetes cluster.
Module 6: Deploying and configuring Azure VMs

This module describes Azure compute and storage in relation to Azure VMs, and how to deploy Azure VMs by using the Azure portal, Azure CLI, or templates. The module also explains how to create new VMs from generalized images and use Azure Image Builder templates to create and manage images in Azure. Finally, this module describes how to deploy Desired State Configuration (DSC) extensions, implement those extensions to remediate noncompliant servers, and use custom script extensions.

Lessons


- Plan and deploy Windows Server IaaS virtual machines
- Customize Windows Server IaaS virtual machine images
- Automate the configuration of Windows Server IaaS virtual machines
Lab: Deploying and configuring Windows Server on Azure VMs


- Authoring Azure Resource Manager (ARM) templates for Azure VM deployment
- Modifying ARM templates to include VM extension-based configuration
- Deploying Azure VMs running Windows Server by using ARM templates
- Configuring administrative access to Azure VMs running Windows Server
- Configuring Windows Server security in Azure VMs
After completing this module, students will be able to:


- Create a VM from the Azure portal and from Azure Cloud Shell.
- Deploy Azure VMs by using templates.
- Automate the configuration of Windows Server IaaS VMs.
- Detect and remediate noncompliant servers.
- Create new VMs from generalized images.
- Use Azure Image Builder templates to create and manage images in Azure.
Module 7: Network infrastructure services in Windows Server

This module describes how to implement core network infrastructure services in Windows Server, such as DHCP and DNS. This module also covers how to implement IP address managment and how to use Remote Access Services.

Lessons


- Deploy and manage DHCP
- Implement Windows Server DNS
- Implement IP address management
- Implement remote access
Lab: Implementing and configuring network infrastructure services in Windows Server


- Deploying and configuring DHCP
- Deploying and configuring DNS
After completing this module, students will be able to:


- Implement automatic IP configuration with DHCP in Windows Server.
- Deploy and configure name resolution with Windows Server DNS.
- Implement IPAM to manage an organization’s DHCP and DNS servers, and IP address space.
- Select, use, and manage remote access components.
- Implement Web Application Proxy (WAP) as a reverse proxy for internal web applications.
Module 8: Implementing hybrid networking infrastructure

This module describes how to connect an on-premises environment to Azure and how to configure DNS for Windows Server IaaS virtual machines. The module covers how to choose the appropriate DNS solution for your organization’s needs, and run a DNS server in a Windows Server Azure IaaS VM. Finally, this module covers how to manage manage Microsoft Azure virtual networks (VNets) and IP address configuration for Windows Server infrastructure as a service (IaaS) virtual machines.

Lessons


- Implement hybrid network infrastructure
- Implement DNS for Windows Server IaaS VMs
- Implement Windows Server IaaS VM IP addressing and routing
Lab: Implementing Windows Server IaaS VM networking


- Implementing virtual network routing in Azure
- Implementing DNS name resolution in Azure
After completing this module, students will be able to:


- Implement an Azure virtual private network (VPN).
- Configure DNS for Windows Server IaaS VMs.
- Run a DNS server in a Windows Server Azure IaaS VM.
- Create a route-based VPN gateway using the Azure portal.
- Implement Azure ExpressRoute.
- Implement an Azure wide area network (WAN).
- Manage Microsoft Azure virtual networks (VNets).
- Manage IP address configuration for Windows Server IaaS virtual machines (VMs).
Module 9: File servers and storage management in Windows Server

This module covers the core functionality and use cases of file server and storage management technologies in Windows Server. The module discusses how to configure and manage the Windows File Server role, and how to use Storage Spaces and Storage Spaces Direct. This module also covers replication of volumes between servers or clusters using Storage Replica.

Lessons


- Manage Windows Server file servers
- Implement Storage Spaces and Storage Spaces Direct
- Implement Windows Server Data Deduplication
- Implement Windows Server iSCSI
- Implement Windows Server Storage Replica
Lab: Implementing storage solutions in Windows Server


- Implementing Data Deduplication
- Configuring iSCSI storage
- Configuring redundant Storage Spaces
- Implementing Storage Spaces Direct
After completing this module, students will be able to:


- Configure and manage the Windows Server File Server role.
- Protect data from drive failures using Storage Spaces.
- Increase scalability and performance of storage management using Storage Spaces Direct.
- Optimize disk utilization using Data DeDuplication.
- Configure high availability for iSCSI.
- Enable replication of volumes between clusters using Storage Replica.
- Use Storage Replica to provide resiliency for data hosted on Windows Servers volumes.
Module 10: Implementing a hybrid file server infrastructure

This module introduces Azure file services and how to configure connectivity to Azure Files. The module also covers how to deploy and implement Azure File Sync to cache Azure file shares on an on-premises Windows Server file server. This module also describes how to manage cloud tiering and how to migrate from DFSR to Azure File Sync.

Lessons


- Overview of Azure file services
- Implementing Azure File Sync
Lab: Implementing Azure File Sync


- Implementing DFS Replication in your on-premises environment
- Creating and configuring a sync group
- Replacing DFS Replication with File Sync–based replication
- Verifying replication and enabling cloud tiering
- Troubleshooting replication issues
After completing this module, students will be able to:


- Configure Azure file services.
- Configure connectivity to Azure file services.
- Implement Azure File Sync.
- Deploy Azure File Sync
- Manage cloud tiering.
- Migrate from DFSR to Azure File Sync.

## Summary
This course teaches IT Professionals how to manage core Windows Server workloads and services using on-premises, hybrid, and cloud technologies. The course teaches IT Professionals how to implement and manage on-premises and hybrid solutions such as identity, management, compute, networking, and storage in a Windows Server hybrid environment.

## Course Duration
4 days

## Last Changed
2024-09-12T10:11:54.000Z
