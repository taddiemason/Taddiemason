## Hi, I'm Zach 👋

Network administrator in Buffalo, NY, working toward a B.S. in Cybersecurity.

By day I live in MSP client environments — Microsoft 365 and Entra ID tenants, Active Directory, Sophos and OPNsense firewalls, VMware/Proxmox hosts, Cove backups, and UniFi wireless. By night I turn the tedious parts of that job into PowerShell, MCP servers, and self-hosted infrastructure.

Rule of thumb: if I have to check the same thing by hand twice, it becomes a repo.

---

### Things I've built

| Project | What it does |
|---|---|
| [`Connectwise-MCP-Server`](https://github.com/taddiemason/Connectwise-MCP-Server) | Docker-packaged MCP bridge exposing 18 read-only ConnectWise tools (tickets, assets, contacts, agreements, financials) so an AI assistant can query PSA data instead of me tabbing over to check it manually |
| [`Kali-Pentest-MCP`](https://github.com/taddiemason/Kali-Pentest-MCP) | MCP bridge for controlled, AI-assisted access to pentest tooling on a Kali host over secure remote command execution |
| [`Vivisect`](https://github.com/taddiemason/Vivisect) | All-in-one digital forensics suite for Debian — disk imaging, file and network analysis, memory forensics, and artifact extraction behind one interface |
| [`jwt-toolkit`](https://github.com/taddiemason/jwt-toolkit) | JWT attack toolkit — decode, scan, and attack tokens (`alg:none`, RS256→HS256 confusion, brute force, `kid` injection) |
| [`Microsoft-Outlook-MCP`](https://github.com/taddiemason/Microsoft-Outlook-MCP) / [`Gmail-MCP-Server`](https://github.com/taddiemason/Gmail-MCP-Server) | Mailbox middleware that turns plain language into Graph and Gmail API calls — OAuth 2.0 with auto-refreshing tokens, attachment parsing, label and folder management |
| [`Exchange-shared-mailbox-check`](https://github.com/taddiemason/Exchange-shared-mailbox-check) | PowerShell audit of shared mailbox permissions and licensing across a tenant |
| [`sms-chatbot`](https://github.com/taddiemason/sms-chatbot) | Routes SMS through a Groq-powered natural-language layer via the Vonage API — mostly built to see if I could |
| [`Hate-Bot`](https://github.com/taddiemason/Hate-Bot) | Discord bot with automated roasts, target voting, an in-bot economy, and a web admin panel |

---

### The audit toolkit (work, private repos)

Most of what I write day to day is a read-only audit suite for network assessments — one focused module per system, all PowerShell against the vendor's own API, nothing that writes:

| Area | Checks |
|---|---|
| **Microsoft 365 / Entra** | Global Admin sprawl, Conditional Access and MFA coverage, named locations, legacy auth, unused licenses, expiring app secrets |
| **Active Directory** | Stale and disabled accounts, password/lockout policy, password-never-expires, admin group membership, AD-to-365 activity correlation before disabling an account |
| **Network & wireless** | UniFi WAP health via the Site Manager API, AP firmware-upgrade batching by RF neighbor overlap, set-inform automation, NETGEAR SNMPv2c inventory, Sophos Central firmware and license status |
| **Hosts & hypervisors** | HPE iLO/Redfish drive, PSU, and thermal health; VMware vSphere via PowerCLI; Proxmox VE via REST |
| **Backup** | Cove (N-able) coverage, retention vs. standard, RPO, and Microsoft 365 workload protection |
| **Recon** | External DNS/port surface, SMB share exposure, email security posture, Entra app-consent and identity recon |

---

### Homelab

A two-node Proxmox cluster (~21 guests) plus a TrueNAS box, fronted by a UniFi Cloud Gateway Max. It's where the coursework gets tested on real hardware:

- **Network** — UCG Max edge, VLAN segmentation, WireGuard split tunnel with a fail-closed kill switch, Tailscale exit node, Suricata IDS from the OPNsense era
- **Services** — self-hosted RustDesk, Uptime Kuma, Apprise, Notifiarr, speedtest tracking, a ClamAV scanner that quarantines on detection, local ComfyUI video generation on a 4070
- **Storage** — ZFS/RAIDZ2, OpenMediaVault joined to a Samba AD domain with per-user home drive mapping, nightly cluster backups
- Every build is documented, including the outages — a full-tunnel route hijack that blackholed the LAN and a double-drive drop that suspended a ZFS pool both have writeups

---

### What I'm usually elbow-deep in

**Infrastructure & Administration**
![Microsoft 365](https://img.shields.io/badge/Microsoft%20365-0d1117?style=flat-square&logo=microsoftoffice&logoColor=58a6ff&labelColor=161b22&color=1f6feb)
![Entra ID](https://img.shields.io/badge/Entra%20ID-0d1117?style=flat-square&logo=microsoftazure&logoColor=58a6ff&labelColor=161b22&color=1f6feb)
![Active Directory](https://img.shields.io/badge/Active%20Directory-0d1117?style=flat-square&logoColor=58a6ff&labelColor=161b22&color=1f6feb)
![Exchange Online](https://img.shields.io/badge/Exchange%20Online-0d1117?style=flat-square&logo=microsoftoutlook&logoColor=58a6ff&labelColor=161b22&color=1f6feb)
![Conditional Access](https://img.shields.io/badge/Conditional%20Access-0d1117?style=flat-square&logo=microsoftazure&logoColor=58a6ff&labelColor=161b22&color=1f6feb)
![VMware](https://img.shields.io/badge/VMware%20vSphere-0d1117?style=flat-square&logo=vmware&logoColor=58a6ff&labelColor=161b22&color=1f6feb)
![Proxmox](https://img.shields.io/badge/Proxmox%20VE-0d1117?style=flat-square&logo=proxmox&logoColor=58a6ff&labelColor=161b22&color=1f6feb)
![ConnectWise](https://img.shields.io/badge/ConnectWise-0d1117?style=flat-square&logoColor=58a6ff&labelColor=161b22&color=1f6feb)

**Networking**
![LAN/WAN](https://img.shields.io/badge/LAN%20%2F%20WAN-0d1117?style=flat-square&logoColor=3fb950&labelColor=161b22&color=238636)
![DHCP/DNS](https://img.shields.io/badge/DHCP%20%2F%20DNS-0d1117?style=flat-square&logoColor=3fb950&labelColor=161b22&color=238636)
![VLAN](https://img.shields.io/badge/VLAN-0d1117?style=flat-square&logoColor=3fb950&labelColor=161b22&color=238636)
![UniFi](https://img.shields.io/badge/UniFi-0d1117?style=flat-square&logo=ubiquiti&logoColor=3fb950&labelColor=161b22&color=238636)
![Sophos](https://img.shields.io/badge/Sophos%20Firewall-0d1117?style=flat-square&logoColor=3fb950&labelColor=161b22&color=238636)
![OPNsense](https://img.shields.io/badge/OPNsense-0d1117?style=flat-square&logo=opnsense&logoColor=3fb950&labelColor=161b22&color=238636)
![VPN](https://img.shields.io/badge/VPN%20%2F%20WireGuard-0d1117?style=flat-square&logo=wireguard&logoColor=3fb950&labelColor=161b22&color=238636)
![SNMP](https://img.shields.io/badge/SNMP-0d1117?style=flat-square&logoColor=3fb950&labelColor=161b22&color=238636)

**Scripting & API Integration**
![PowerShell](https://img.shields.io/badge/PowerShell-0d1117?style=flat-square&logo=powershell&logoColor=e3b341&labelColor=161b22&color=9e6a03)
![Python](https://img.shields.io/badge/Python-0d1117?style=flat-square&logo=python&logoColor=e3b341&labelColor=161b22&color=9e6a03)
![TypeScript](https://img.shields.io/badge/TypeScript-0d1117?style=flat-square&logo=typescript&logoColor=e3b341&labelColor=161b22&color=9e6a03)
![Bash](https://img.shields.io/badge/Bash-0d1117?style=flat-square&logo=gnubash&logoColor=e3b341&labelColor=161b22&color=9e6a03)
![Microsoft Graph API](https://img.shields.io/badge/Microsoft%20Graph%20API-0d1117?style=flat-square&logo=microsoftazure&logoColor=e3b341&labelColor=161b22&color=9e6a03)
![REST APIs](https://img.shields.io/badge/REST%20APIs-0d1117?style=flat-square&logoColor=e3b341&labelColor=161b22&color=9e6a03)
![MCP](https://img.shields.io/badge/Model%20Context%20Protocol-0d1117?style=flat-square&logoColor=e3b341&labelColor=161b22&color=9e6a03)
![OAuth 2.0](https://img.shields.io/badge/OAuth%202.0-0d1117?style=flat-square&logoColor=e3b341&labelColor=161b22&color=9e6a03)

**Security**
![Security Audits](https://img.shields.io/badge/Security%20Audits-0d1117?style=flat-square&logoColor=f78166&labelColor=161b22&color=b62324)
![MFA Configuration](https://img.shields.io/badge/MFA%20Configuration-0d1117?style=flat-square&logoColor=f78166&labelColor=161b22&color=b62324)
![Identity Lifecycle](https://img.shields.io/badge/Identity%20Lifecycle-0d1117?style=flat-square&logoColor=f78166&labelColor=161b22&color=b62324)
![Penetration Testing](https://img.shields.io/badge/Penetration%20Testing-0d1117?style=flat-square&logoColor=f78166&labelColor=161b22&color=b62324)
![Digital Forensics](https://img.shields.io/badge/Digital%20Forensics-0d1117?style=flat-square&logoColor=f78166&labelColor=161b22&color=b62324)
![Cryptography](https://img.shields.io/badge/Cryptography-0d1117?style=flat-square&logoColor=f78166&labelColor=161b22&color=b62324)
![NIST](https://img.shields.io/badge/NIST-0d1117?style=flat-square&logoColor=f78166&labelColor=161b22&color=b62324)
![SOC 2](https://img.shields.io/badge/SOC%202-0d1117?style=flat-square&logoColor=f78166&labelColor=161b22&color=b62324)

**DevOps & Self-Hosting**
![Docker](https://img.shields.io/badge/Docker-0d1117?style=flat-square&logo=docker&logoColor=79c0ff&labelColor=161b22&color=388bfd)
![Linux](https://img.shields.io/badge/Linux-0d1117?style=flat-square&logo=linux&logoColor=79c0ff&labelColor=161b22&color=388bfd)
![Cloudflare Workers](https://img.shields.io/badge/Cloudflare%20Workers-0d1117?style=flat-square&logo=cloudflare&logoColor=79c0ff&labelColor=161b22&color=388bfd)
![ZFS](https://img.shields.io/badge/ZFS%20%2F%20TrueNAS-0d1117?style=flat-square&logoColor=79c0ff&labelColor=161b22&color=388bfd)
![Ansible](https://img.shields.io/badge/Ansible-0d1117?style=flat-square&logo=ansible&logoColor=79c0ff&labelColor=161b22&color=388bfd)
![Git](https://img.shields.io/badge/Git-0d1117?style=flat-square&logo=git&logoColor=79c0ff&labelColor=161b22&color=388bfd)

---

### Currently studying

Cryptography (block ciphers through public-key and Diffie–Hellman), network management (SNMP, ASN.1/BER, MIBs and SMI), CCNA-level networking, and the usual pile of Linux and application-security reading. Notes go into an Obsidian vault that cross-links coursework to the homelab builds and work procedures that use it.

---

### Elsewhere

[Website](https://zacharylalime.com) · [LinkedIn](https://www.linkedin.com/in/zachary-lalime) · zacharylalime@gmail.com
