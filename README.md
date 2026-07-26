# Enterprise VMware vSphere Lab on Azure Nested Virtualization

![Azure](https://img.shields.io/badge/Azure-Cloud-blue)
![Windows Server](https://img.shields.io/badge/Windows%20Server-2022-blue)
![Hyper-V](https://img.shields.io/badge/Hyper--V-Nested%20Virtualization-purple)
![VMware](https://img.shields.io/badge/VMware-vSphere-orange)
![ESXi](https://img.shields.io/badge/ESXi-8.x-green)
![vCenter](https://img.shields.io/badge/vCenter-Server-red)
![Networking](https://img.shields.io/badge/Networking-TCP%2FIP-orange)
![Lab](https://img.shields.io/badge/Project-Home%20Lab-lightgrey)

# Enterprise VMware vSphere Infrastructure Lab

## Overview

This project demonstrates the deployment of an enterprise-style VMware vSphere environment using nested virtualization inside Microsoft Azure.

The goal of this lab is to simulate a real-world virtualization environment commonly found in enterprise infrastructure and MSP environments.

The environment includes two ESXi hosts managed by vCenter Server, virtual networking, storage services, and Windows/Linux workloads.

The project focuses on hands-on experience with:

- VMware ESXi administration
- vCenter Server management
- Virtual networking
- Virtual machine lifecycle management
- Storage configuration
- High availability concepts
- Infrastructure troubleshooting

---

# Architecture

<img width="1306" height="1205" alt="Topology" src="https://github.com/user-attachments/assets/b1b94825-1e7c-4537-b49e-251265f82dc9" />

---

# Project Objectives

The objectives of this project are:

- Build an enterprise VMware environment from scratch
- Deploy multiple ESXi hosts
- Configure vCenter Server
- Create and manage virtual machines
- Understand VMware networking concepts
- Configure shared storage
- Practice virtualization troubleshooting
- Document infrastructure changes

---

# Environment Details

## Azure Infrastructure

| Component | Configuration |
|---|---|
| Cloud Platform | Microsoft Azure |
| Operating System | Windows Server 2022 Datacenter |
| CPU | 4 vCPU |
| Memory | 32GB RAM |
| Hypervisor | Hyper-V |
| Virtualization Type | Nested Virtualization |

---

# Hyper-V Layer

The Azure VM acts as the physical virtualization host.

Configured components:

- Hyper-V Role
- Virtual Switches
- Nested virtualization
- Virtual networking

---

# VMware Environment

## ESXi Hosts

| Hostname | IP Address | Purpose |
|---|---|---|
| MVIT-ESXI01 | 192.168.100.10 | VMware Hypervisor |
| MVIT-ESXI02 | 192.168.100.20 | VMware Hypervisor |

---

## vCenter Server

| Component | IP Address |
|-|-|
| vCenter Server Appliance | 192.168.100.30 |

vCenter provides centralized management for:

- ESXi hosts
- Virtual machines
- Clusters
- Networking
- Storage

---

# Network Design

## Management Network
- Network: 192.168.100.0/24

- Gateway: 192.168.100.254


## IP Address Allocation

| Device | IP |
|---|---|
| ESXi01 Management | 192.168.100.10 |
| ESXi02 Management | 192.168.100.20 |
| vCenter | 192.168.100.20 |
| Domain Controller | 192.168.100.1 |
| Storage Server | 192.168.100.2 |

---

# Project Phases

## Phase 1 - Azure & VMWare Workststion Deployment

Completed tasks:

- Deployed Azure Windows Server VM
- Installed VMWare Workstation
- Enabled nested virtualization

---

## Phase 2 - ESXi Host Deployment

Tasks:

- Created ESXi virtual machines
- Installed VMware ESXi
- Configured management networking
- Assigned static IP addresses

---

## Phase 3 - vCenter Deployment

Tasks:

- Installed vCenter Server Appliance
- Added ESXi hosts
- Created datacenter
- Created cluster

---

## Phase 4 - Virtual Networking

Tasks:

- Configure standard switches
- Configure VM networks
- Configure VMkernel adapters
- Test connectivity

---

## Phase 5 - Storage Configuration

Tasks:

- Deploy storage server
- Configure iSCSI storage
- Create VMFS datastore
- Present shared storage to ESXi hosts

---

## Phase 6 - VMware Enterprise Features

Testing:

- Virtual machine migration
- Snapshots
- Templates
- Permissions
- Resource management
- High Availability concepts

---


# Author

**Mvula**

IT Support Technician | L2 Infrastructure Enthusiast

This project was created to demonstrate practical enterprise virtualization skills and infrastructure troubleshooting experience.
