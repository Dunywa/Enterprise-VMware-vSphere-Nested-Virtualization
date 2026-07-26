# Phase 1 - Azure & VMware Workstation Deployment

## Overview

This phase focused on preparing the virtualization foundation for the VMware vSphere lab.

A Windows Server 2022 Azure VM was deployed and configured to run VMware Workstation for nested virtualization.

---

# Completed Tasks

## 1. Azure VM Deployment

Deployed a Windows Server 2022 Datacenter VM in Microsoft Azure.

Configuration:

| Component | Details |
|---|---|
| OS | Windows Server 2022 Datacenter |
| CPU | 4 vCPU |
| RAM | 32GB |
| Purpose | VMware Lab Host |

### Screenshot

![Azure VM Deployment](screenshots/azure-vm.png)

---

## 2. VMware Workstation Installation

Installed VMware Workstation 17 Pro on the Azure VM.

Configured VMware Workstation to create and manage nested virtual machines.

### Screenshot

![VMware Workstation](screenshots/vmware-workstation.png)

---

## 3. Enable Nested Virtualization

Enabled virtualization extensions to allow hypervisors to run inside virtual machines.

Verification:

- systeminfo | findstr /i "Virtualization Hyper-V"


Result:

A hypervisor has been detected.


### Screenshot

![Nested Virtualization Enabled](screenshots/nested-virtualization.png)

---

# Environment Architecture



