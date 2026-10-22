## Hi, I'm Zach 👋

I'm a network administrator in Buffalo, NY, working toward my B.S. in Cybersecurity.

I work in the MSP world, handling everything from Microsoft 365 and Active Directory to firewalls, virtualization, backups, and wireless networks.

Outside of work, I spend a lot of time in my homelab, building PowerShell scripts, experimenting with MCP servers, and running self-hosted services. Most of my projects start with something I wanted to fix, understand better, or stop doing manually.

---

## Things I've Built

| Project | What It Does |
| --- | --- |
| [Connectwise-MCP-Server](https://github.com/taddiemason/Connectwise-MCP-Server) | Docker-packaged MCP bridge with 18 read-only ConnectWise tools for querying tickets, assets, contacts, agreements, and financials through an AI assistant. |
| [Kali-Pentest-MCP](https://github.com/taddiemason/Kali-Pentest-MCP) | MCP bridge for controlled, AI-assisted access to penetration-testing tools on a Kali host through secure remote command execution. |
| [Vivisect](https://github.com/taddiemason/Vivisect) | Digital forensics suite for Debian that brings disk imaging, file and network analysis, memory forensics, and artifact extraction into one interface. |
| [jwt-toolkit](https://github.com/taddiemason/jwt-toolkit) | JWT security-testing toolkit for decoding and scanning tokens, testing `alg:none`, RS256-to-HS256 confusion, brute force, and `kid` injection. |
| [Microsoft-Outlook-MCP](https://github.com/taddiemason/Microsoft-Outlook-MCP) / [Gmail-MCP-Server](https://github.com/taddiemason/Gmail-MCP-Server) | Mailbox middleware that turns plain-language requests into Microsoft Graph and Gmail API calls, with OAuth 2.0, automatic token refresh, attachment parsing, and label and folder management. |
| [Exchange-shared-mailbox-check](https://github.com/taddiemason/Exchange-shared-mailbox-check) | PowerShell tool for auditing shared mailbox permissions and licensing across a tenant. |
| [sms-chatbot](https://github.com/taddiemason/sms-chatbot) | SMS chatbot using Groq and the Vonage API. Mostly built to see if I could. |
| [Hate-Bot](https://github.com/taddiemason/Hate-Bot) | Discord bot with automated roasts, target voting, an in-bot economy, and a web admin panel. |

---

## The Audit Toolkit

Most of what I write at work lives in private repos. It's a PowerShell toolkit for network assessments, with focused modules for different systems and integrations with vendor APIs.

The audit checks are read-only. I also build automation for recurring administrative tasks.

| Area | What I Check or Automate |
| --- | --- |
| **Microsoft 365 / Entra ID** | Global Admin membership, Conditional Access and MFA coverage, named locations, legacy authentication, unused licenses, and expiring app secrets. |
| **Active Directory** | Stale and disabled accounts, password and lockout policies, passwords set to never expire, admin group membership, and AD-to-365 activity correlation before disabling accounts. |
| **Networking & Wireless** | UniFi AP health through the Site Manager API, firmware-upgrade batches based on RF neighbor overlap, set-inform automation, NETGEAR SNMPv2c inventory, and Sophos Central firmware and licensing status. |
| **Hosts & Hypervisors** | HPE iLO/Redfish drive, power supply, and thermal health; VMware vSphere through PowerCLI; and Proxmox VE through REST APIs. |
| **Backups** | Cove coverage, retention compared with standards, RPO, and Microsoft 365 workload protection. |
| **Reconnaissance** | External DNS and exposed ports, SMB share exposure, email security posture, Entra app consent, and identity reconnaissance. |

---

## Homelab

I run a two-node Proxmox cluster with around 21 guests, a TrueNAS box, and a UniFi Cloud Gateway Max. It's where I test what I'm learning on real hardware.

- **Networking:** UCG Max edge, VLAN segmentation, WireGuard split tunneling with a fail-closed kill switch, a Tailscale exit node, and Suricata IDS from my OPNsense setup.
- **Services:** Self-hosted RustDesk, Uptime Kuma, Apprise, Notifiarr, speedtest tracking, a ClamAV scanner with automatic quarantine, and local ComfyUI video generation on an RTX 4070.
- **Storage:** ZFS/RAIDZ2, OpenMediaVault joined to a Samba AD domain, per-user home drive mapping, and nightly cluster backups.
- **Documentation:** I document the builds and the outages, including a full-tunnel route hijack that blackholed the LAN and a double-drive drop that suspended a ZFS pool.

---

## What I Work With

### Infrastructure & Administration

![Microsoft 365](https://img.shields.io/badge/Microsoft_365-1f6feb?style=flat-square)
![Entra ID](https://img.shields.io/badge/Entra_ID-1f6feb?style=flat-square)
![Active Directory](https://img.shields.io/badge/Active_Directory-1f6feb?style=flat-square)
![Exchange Online](https://img.shields.io/badge/Exchange_Online-1f6feb?style=flat-square)
![Conditional Access](https://img.shields.io/badge/Conditional_Access-1f6feb?style=flat-square)
![VMware vSphere](https://img.shields.io/badge/VMware_vSphere-1f6feb?style=flat-square&logo=vmware&logoColor=white)
![Proxmox VE](https://img.shields.io/badge/Proxmox_VE-1f6feb?style=flat-square&logo=proxmox&logoColor=white)
![ConnectWise](https://img.shields.io/badge/ConnectWise-1f6feb?style=flat-square)

### Networking

![LAN / WAN](https://img.shields.io/badge/LAN_%2F_WAN-238636?style=flat-square)
![DHCP / DNS](https://img.shields.io/badge/DHCP_%2F_DNS-238636?style=flat-square)
![VLANs](https://img.shields.io/badge/VLANs-238636?style=flat-square)
![UniFi](https://img.shields.io/badge/UniFi-238636?style=flat-square&logo=ubiquiti&logoColor=white)
![Sophos Firewall](https://img.shields.io/badge/Sophos_Firewall-238636?style=flat-square)
![OPNsense](https://img.shields.io/badge/OPNsense-238636?style=flat-square&logo=opnsense&logoColor=white)
![VPN / WireGuard](https://img.shields.io/badge/VPN_%2F_WireGuard-238636?style=flat-square&logo=wireguard&logoColor=white)
![SNMP](https://img.shields.io/badge/SNMP-238636?style=flat-square)

### Scripting & API Integration

![PowerShell](https://img.shields.io/badge/PowerShell-9e6a03?style=flat-square)
![Python](https://img.shields.io/badge/Python-9e6a03?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-9e6a03?style=flat-square&logo=typescript&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-9e6a03?style=flat-square&logo=gnubash&logoColor=white)
![Microsoft Graph API](https://img.shields.io/badge/Microsoft_Graph_API-9e6a03?style=flat-square)
![REST APIs](https://img.shields.io/badge/REST_APIs-9e6a03?style=flat-square)
![MCP](https://img.shields.io/badge/Model_Context_Protocol-9e6a03?style=flat-square)
![OAuth 2.0](https://img.shields.io/badge/OAuth_2.0-9e6a03?style=flat-square)

### Security

![Security Audits](https://img.shields.io/badge/Security_Audits-b62324?style=flat-square)
![MFA Configuration](https://img.shields.io/badge/MFA_Configuration-b62324?style=flat-square)
![Identity Lifecycle](https://img.shields.io/badge/Identity_Lifecycle-b62324?style=flat-square)
![Penetration Testing](https://img.shields.io/badge/Penetration_Testing-b62324?style=flat-square)
![Digital Forensics](https://img.shields.io/badge/Digital_Forensics-b62324?style=flat-square)
![Cryptography](https://img.shields.io/badge/Cryptography-b62324?style=flat-square)
![NIST](https://img.shields.io/badge/NIST-b62324?style=flat-square)
![SOC 2](https://img.shields.io/badge/SOC_2-b62324?style=flat-square)

### DevOps & Self-Hosting

![Docker](https://img.shields.io/badge/Docker-388bfd?style=flat-square&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-388bfd?style=flat-square&logo=linux&logoColor=white)
![Cloudflare Workers](https://img.shields.io/badge/Cloudflare_Workers-388bfd?style=flat-square&logo=cloudflare&logoColor=white)
![ZFS / TrueNAS](https://img.shields.io/badge/ZFS_%2F_TrueNAS-388bfd?style=flat-square)
![Ansible](https://img.shields.io/badge/Ansible-388bfd?style=flat-square&logo=ansible&logoColor=white)
![Git](https://img.shields.io/badge/Git-388bfd?style=flat-square&logo=git&logoColor=white)

---

## Currently Studying

- **Cryptography:** Block ciphers, public-key cryptography, and Diffie–Hellman.
- **Network Management:** SNMP, ASN.1/BER, MIBs, and SMI.
- **Networking:** CCNA-level concepts and practical lab work.
- **Other Reading:** Linux and application security.

---

## Elsewhere

[Website](https://zacharylalime.com) · [LinkedIn](https://www.linkedin.com/in/zachary-lalime) · [Email](mailto:zacharylalime@gmail.com)
