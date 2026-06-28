# HomeDNSLab
# 🛡️ Active Directory DNS Home Lab

## Overview

This home lab demonstrates the installation and configuration of **DNS** in an **Active Directory** environment using **Windows Server 2022** and a **Windows 11** client in **VMware Workstation**. DNS is integrated with Active Directory to provide reliable name resolution for domain resources and client authentication.

## Lab Environment

* **Hypervisor:** VMware Workstation
* **Server OS:** Windows Server 2022
* **Client OS:** Windows 11 Pro
* **Server Roles:** Active Directory Domain Services (AD DS), DNS Server
* **Domain:** `homelab.local`

## Objectives

* Install and configure the DNS Server role.
* Create Forward and Reverse Lookup Zones.
* Configure DNS resource records (A, PTR, CNAME, SRV).
* Configure DNS Forwarders.
* Verify DNS functionality from a Windows 11 client.

## Configuration Summary

### DNS Installation

Installed the DNS Server role through **Server Manager** and integrated it with Active Directory.

### Forward & Reverse Lookup Zones

Created Active Directory-integrated Forward and Reverse Lookup Zones with secure dynamic updates enabled.

### DNS Records

Configured essential DNS records, including:

* A Records
* PTR Records
* CNAME Records
* SRV Records

Configured public DNS forwarders to enable Internet name resolution.

### Validation

Verified DNS functionality using:

```powershell
ipconfig /all
ipconfig /flushdns
nslookup
Resolve-DnsName
ping
```
Screenshots of the Project:
<img width="981" height="544" alt="Screenshot 2026-06-29 010448" src="https://github.com/user-attachments/assets/abd3d553-d8f5-443a-a0f7-6d2dc43adec3" />
<img width="896" height="538" alt="Screenshot 2026-06-29 010524" src="https://github.com/user-attachments/assets/46d90af1-418e-4225-8d0c-d71dbda9aa0c" />
<img width="896" height="538" alt="Screenshot 2026-06-29 010524" src="https://github.com/user-attachments/assets/e0429ebb-8d9c-4664-a5fe-f1f5795cece7" />
<img width="1011" height="558" alt="Screenshot 2026-06-29 011014" src="https://github.com/user-attachments/assets/b093c62d-8b0f-4e2d-a8f8-609c4a9cb77a" />
<img width="910" height="542" alt="Screenshot 2026-06-29 010610" src="https://github.com/user-attachments/assets/65832ce4-302e-4f47-9a60-f124446ad76c" />




## Skills Demonstrated

* Active Directory Administration
* DNS Administration
* Windows Server 2022
* Windows 11 Administration
* VMware Workstation
* Network Troubleshooting
* PowerShell
* Enterprise Name Resolution

## Conclusion

This home lab provided hands-on experience deploying and managing DNS in an Active Directory environment. It strengthened my understanding of enterprise name resolution, DNS troubleshooting, and Windows Server administration while reinforcing core networking concepts used in real-world IT and cybersecurity environments.
