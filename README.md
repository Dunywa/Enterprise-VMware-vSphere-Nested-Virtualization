<img width="1536" height="1024" alt="readme md banner" src="https://github.com/user-attachments/assets/0058a8a3-3fa9-4afb-978b-25c31c36fa6e" />

## Project Overview

This project demonstrates the design, deployment, and administration of an enterprise VMware environment hosted in Microsoft Azure using nested virtualization.

The lab was built to simulate a real-world virtualization platform and provide hands-on experience with VMware infrastructure administration, Active Directory integration, storage management, networking, High Availability (HA), Distributed Resource Scheduler (DRS), and incident troubleshooting.

## Objectives

- Deploy a VMware environment in Azure
- Implement centralized identity services using Active Directory
- Configure shared storage using iSCSI
- Deploy VMware ESXi hosts
- Deploy VMware vCenter Server
- Configure a VMware cluster
- Enable High Availability (HA)
- Enable Distributed Resource Scheduler (DRS)
- Deploy workload virtual machines
- Simulate and resolve enterprise VMware incidents

## Technologies Used

- Microsoft Azure
- VMware ESXi
- VMware vCenter Server
- Windows Server 2022
- Active Directory Domain Services
- DNS
- iSCSI Storage
- VMware HA
- VMware DRS

## Architecture

The environment consists of:

- Azure Resource Group
- Virtual Network
- Domain Controller
- Shared Storage Server
- Two VMware ESXi Hosts
- VMware vCenter Server
- Multiple workload virtual machines

## Documentation

| Document | Description |
| --- | --- |
| 01-Design.md | Solution architecture and planning |
| 02-Azure.md | Azure infrastructure deployment |
| 03-AD.md | Active Directory deployment |
| 04-Storage.md | Shared storage configuration |
| 05-ESXi.md | ESXi host deployment |
| 06-vCenter.md | vCenter deployment |
| 07-Cluster.md | Cluster configuration |
| 08-Networking.md | VMware networking |
| 09-Workloads.md | Virtual machine deployment |
| 10-Incidents.md | Enterprise troubleshooting scenarios |

## Skills Demonstrated

- Infrastructure Design
- VMware Administration
- Azure Administration
- Active Directory
- DNS Administration
- Storage Administration
- Virtualization
- Incident Response
- Root Cause Analysis

## Author

This project was created as part of my Infrastructure Engineering and VMware Administration portfolio.
