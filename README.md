#  Home Lab

A self-directed home lab built to develop and demonstrate junior system administrator skills, including Windows client/server administration, Active Directory, networking services, file permissions, and Linux administration.


## Lab Environment

- **Hypervisor:** VirtualBox 
- **Host machine:** *(brief specs — RAM, CPU)*
- **VMs used:**
  - Windows 11 (client)
  - Windows Server 2022 (domain controller)
  - Linux (Ubuntu Server / Rocky Linux / etc.)

## Labs

| # | Lab | Topics Covered |
|---|-----|-----------------|
| 01 | [Windows 11 Client Install & Troubleshooting](./01-windows-client-install-troubleshoot) | OS installation, driver/network troubleshooting, system file repair |
| 02 | [Windows Server & Active Directory Domain Services](./02-windows-server-adds) | Server build, AD DS role installation |
| 03 | [Users, Groups, OUs & Password Management](./03-users-groups-ous) | AD account and organizational unit management |
| 04 | [Domain-Joined Client](./04-domain-join) | Joining a client to the domain, domain login |
| 05 | [DNS and DHCP Configuration](./05-dns-dhcp) | Name resolution, IP address leasing |
| 06 | [File Sharing & NTFS Permissions](./06-file-sharing-ntfs) | Share vs. NTFS permissions, access control |
| 07 | [Linux Server Administration](./07-linux-administration) | User management, services, logs, firewall |
| 08 | [Malware Removal & Windows Optimization](./08-malware-optimization) | System cleanup, performance tuning |
| 09 | [Home Networking Lab](./09-home-networking) | Subnetting, network topology, connectivity testing |

## How Each Lab Is Documented

Every lab folder includes:
- A `README.md` describing the objective, steps taken, commands used, and any issues encountered and resolved
- A `screenshots/` folder with visual proof of each major step

## Why This Repo Exists

This lab was built to gain hands-on experience with the day-to-day responsibilities of a junior system administrator — provisioning systems, managing identities, configuring core network services, and troubleshooting real issues — in a structured, documented way that mirrors how work is tracked in a professional environment.
