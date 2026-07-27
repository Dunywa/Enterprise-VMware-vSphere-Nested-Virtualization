# Phase 2 - ESXi Deployment

## Overview

In this phase, two VMware ESXi hosts were deployed to form the foundation of the virtual infrastructure. Each host was configured with a static management IP address and prepared for centralized management through vCenter Server.

---

# Completed Tasks

## 1. Deployed ESXi Hosts

Created the following VMware ESXi virtual machines:

- **MVIT-ESXI01**
- **MVIT-ESXI02**

---

## 2. Installed VMware ESXi

<img width="1278" height="826" alt="MVIT-ESXi1" src="https://github.com/user-attachments/assets/b60f811c-f239-445a-a6e9-2eed4aa36291" />

<img width="1271" height="833" alt="MVIT-ESXi2" src="https://github.com/user-attachments/assets/e46b9606-54cf-482d-abd2-8ed0ecc46c53" />

### Screenshot

![ESXi Installation](screenshots/esxi-installation.png)

---

## 3. Configured Management Network

Configured the ESXi management network using static IP addresses.

| Host | IP Address | Network |
|------|------------|----------|
| MVIT-ESXI01 | 192.168.100.10 | 192.168.100.0/24 |
| MVIT-ESXI02 | 192.168.100.20 | 192.168.100.0/24 |

---

## 4. Configured Root Passwords

Configured secure root passwords for both ESXi hosts to allow administrative access.

---

# Management Network

```
Network: 192.168.100.0/24

MVIT-ESXI1
192.168.100.10

MVIT-ESXI2
192.168.100.20
```

---

# Environment Diagram

```
              Hyper-V Host
                    |
        +-----------+-----------+
        |                       |
   MVIT-ESXI01             MVIT-ESXI2
  192.168.100.10           192.168.100.20
```

---

# Skills Demonstrated

- VMware ESXi Installation
- ESXi Host Configuration
- VMkernel Management Network
- Static IP Address Configuration
- VMware Host Administration
- Infrastructure Deployment

