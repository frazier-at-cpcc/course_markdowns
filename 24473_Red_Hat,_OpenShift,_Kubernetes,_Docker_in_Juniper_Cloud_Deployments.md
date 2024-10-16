# Red Hat, OpenShift, Kubernetes, Docker in Juniper Cloud Deployments

**Product ID**: 24473
**Category ID**: nan
**Modality**: 1
**Active**: True
**Language**: en
**Product Code**: ROKD
**Vendor Code**: JP
**Vendor Name**: Juniper Networks
**URL**: [Course Link](https://www.fastlaneus.com/course/juniper-rokd)

## Objective
- List the various open source technologies and their basic differences.
- Describe how each open source technology plays a role in a Contrail solution.
- Describe the basic architecture of Red Hat Linux and other distributions.
- Configure namespaces and virtual networking using Linux and OVS bridges.
- Describe the function of libvirt.
- Instantiate virtual machines using Virtual Machine Manager.
- Create and import and OVS bridge into libvirt.
- Instantiate a VXLAN tunnel between OVS bridges.
- Instantiate virtual machines using virsh.
- Describe the purpose of OpenStack.
- Identify the function of each of the main OpenStack projects.
- Use the OpenStack CLI.
- Describe the OpenStack networking features available to workloads.
- Describe traditional OpenStack block and object storage.
- Describe how Ceph can be integrated with OpenStack.
- Use Ceph storage to better scale an RHOSP deployment.
- Describe the usage of TripleO in a RHOSP deployment.
- Describe the functions of the undercloud.
- Describe the functions of the overcloud.
- Describe the networks used in an RHOSP deployment.
- Describe how to deploy the undercloud.
- Describe how to deploy the overcloud while using YAML files.
- Describe the benefits of containers.
- Describe the reasons to use Docker.
- Describe the basic CLI commands for Docker.
- Describe how to run a container in Docker.
- Describe the difference between attached and detached mode.
- Describe how to interact with Dockerhub.
- Describe how to network a Docker container.
- Describe how to inspect and view the logs of a Docker container.
- Describe how to build and image using a Dockerfile.
- Describe the difference between CMD and ENTRYPOINT.
- Describe how to compose a Docker container.
- Describe how to build a private registry.
- Describe the k8s architecture.
- Describe the usage of k8s pods.
- Describe the basic usage of the k8s CLI.
- Instantiate a pod using YAML.
- Describe the function replication controllers and sets.
- Describe how to create a deployment.
- Describe networking in k8s.
- Describe how to use namespaces with k8s.
- Describe the basic differences between k8s and OpenShift.
- Describe the basic CLI commands of OpenShift.
- Describe the basic functionality of the OpenShift web UI.

## Essentials
- Basic TCP/IP skills
- General understanding of data center virtualization

## Audience
Individuals responsible for working with software-defined networking solutions in data center, service provider, and enterprise network environments. It is beneficial for learning and applying the foundational knowledge of cloud technologies prior to working Contrail Networking.

## Outline
Course Introduction

Open Source Cloud Technologies


- Open Source Technologies Overview
- Juniper’s Usage of Open Source Technologies(Contrail, CSO, EVO, etc.)
Linux Architecture


- Hardware, Kernel, OS Interaction
- Namespaces
- Cgroups
- Virtual Networking
Lab 1: Linux Namespaces and Virtual Networking

Linux Virtualization


- QEMU/KVM
- Libvirt
- Virtual Machine Manager
- Virsh
- OVS Bridging with VXLAN tunneling
Lab 2: Linux Virtualization

OpenStack Fundamentals


- OpenStack Overview
- OpenStack Projects
- OpenStack CLI
Lab 3: Exploring the OpenStack CLI

OpenStack Configuration


- OpenStack Interface Options
- OpenStack Heat Templates
- OpenStack Configuration
Lab 4: OpenStack Configuration

OpenStack Networking


- Networks
- Routers
- Security Groups
- Load Balancers
- Floating IPs
- Trunks
- Network Topology
Lab 5: OpenStack Networking

OpenStack Storage


- Default OpenStack Storage
- Ceph Storage
- Ceph Integration with OpenStack
- Launch VMs using Ceph for Block and ObjectStorage
Lab 6: Ceph Storage

RHOSP


- OpenStack over OpenStack (TripleO)
- Deploying the Undercloud
- Deploying the Overcloud
- Working with YAML files and RHOSP
- Troubleshooting RHOSP after installation
Lab 7: RHOSP

Docker Basics


- Why Docker and Containers?
- What Is a Container?
- Docker Overview
- Working with Docker (dockerhub, installation, image versus container)
- Getting Started with the Docker CLI
Lab 8: Getting to Know Docker

Advanced Docker


- More Commands
- Port Mapping
- Container Details
- Passing Environment Variables
- Creating Your Own Image
- ENTRYPOINT versus CMD
- Understanding Docker Networking
- Docker Storage
- Composing Docker Containers
- Registries
- Docker Engine
Lab 9: Composing Docker Containers

Kubernetes Basics


- K8s Overview
- K8s Architecture
- Pods
- kubectl
- Using YAML to Create a Pod
Lab 10: Creating a Docker Pod

K8s Advanced Topics


- Replica Controller and ReplicaSet
- Deployments
- Networking K8s
- Services
- Working with Namespaces
Lab 11: ReplicaSets and Networking in K8s

Red Hat OpenShift


- OpenShift Overview
- OpenShift Flavors
- OpenShift CLI
- OpenShift Webconsole
- Deploying Containers with OpenShift
- Behind the Scenes App Dev
- Scaling Up New Hosts
Lab 12: OpenShift Container Orchestration

## Summary
This four-day course is designed to provide students with the background knowledge required to work with the Juniper Cloud products. Students will gain in-depth knowledge of how to use Linux Kernel-based Virtual Machines (KVM), Red Hat OpenStack Platform, Docker, Kubernetes, and Red Hat OpenShift. Through demonstrations and hands-on labs, students will gain experience with the features of each of these technologies. It should be noted that this course does not cover Contrail Networking. This course is based on Red Hat Linux version 7.8, RHOSP version 13, Docker version 3:19.03.12-3.el7, Kubernetes version 1.18.6-0, and Red Hat OpenShift version 3.11.

## Course Duration
4 days

## Last Changed
2024-05-10T16:42:10.000Z
