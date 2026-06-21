# Active Directory Home Lab

## Overview

This project demonstrates the deployment and configuration of a Windows Server 2022 Active Directory environment using VMware Workstation.

The lab includes:

- Windows Server 2022 Domain Controller
- Active Directory Domain Services (AD DS)
- DNS Server Configuration
- Windows 11 Client
- Domain Join Process
- Network Troubleshooting and DNS Validation

---

## Lab Environment

| Component | Configuration |
|------------|---------------|
| Hypervisor | VMware Workstation |
| Server OS | Windows Server 2022 |
| Client OS | Windows 11 Enterprise |
| Domain Name | alrashidi.local |
| Domain Controller | DC01 |
| Client Machine | CLIENT01 |
| DNS Server | 192.168.251.10 |

---

## Objectives

- Install Windows Server 2022
- Configure Active Directory Domain Services
- Promote the server to a Domain Controller
- Configure DNS services
- Deploy a Windows 11 client
- Configure client networking
- Join the client to the Active Directory domain
- Verify domain connectivity and authentication

---

## Deployment Steps

### 1. Windows Server Installation

Installed Windows Server 2022 and configured a static IP address.

### 2. Active Directory Installation

Installed the AD DS role and promoted the server to a Domain Controller.

### 3. DNS Configuration

Configured DNS zones and validated domain name resolution.

### 4. Windows 11 Client Deployment

Installed Windows 11 Enterprise on a separate virtual machine.

### 5. Client Network Configuration

Configured DNS settings to use the Domain Controller as the primary DNS server.

### 6. Domain Join

Successfully joined the Windows 11 client to the domain:

`alrashidi.local`

### 7. Validation

Verified:

- DNS Resolution
- Domain Controller Discovery
- Active Directory Connectivity
- Successful Domain Membership

---

## Troubleshooting Performed

During deployment, DNS resolution issues prevented the client from locating the Domain Controller.

The issue was resolved by:

- Verifying DNS records
- Restarting DNS services
- Validating SRV records
- Testing connectivity between DC01 and CLIENT01
- Flushing DNS cache
- Renewing network configuration

---

## Results

Successfully built a functional Active Directory lab environment and joined a Windows 11 client to the domain.

Final result:

> Welcome to the alrashidi.local domain.

---

## Skills Demonstrated

- Active Directory Administration
- Windows Server 2022
- DNS Management
- Domain Services
- VMware Workstation
- Windows Networking
- Troubleshooting
- System Administration

---

## Screenshots

Add screenshots demonstrating:

- Windows Server Installation
- Active Directory Configuration
- DNS Manager
- Network Configuration
- Domain Join Process
- Successful Domain Join

---

## Author

**Alrashidi Netizen**
