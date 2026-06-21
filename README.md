## Hi there 👋

# Zach Lalime

### Network Administrator · Buffalo, NY · Cybersecurity Student

---

```zsh
┌──(zachary@zachbox)-[~]
└─$ cat about.txt
```

```txt
Before IT, I spent four years in field sales — knocking on doors,
reading rooms, explaining things fast to people who had better things
to do. Not exactly a tech origin story, but it made me better at
this job than I expected.

I'm a network administrator at Synchronet in Buffalo, working across
Microsoft 365 tenants, Entra ID, Conditional Access policy management,
and network infrastructure for MSP clients with real stakes.

On the side: B.S. in Cybersecurity in progress, and I build production
API integrations — ConnectWise, Microsoft Graph, Gmail, Vonage — that
connect the tools I use every day.
```

---

```zsh
└─$ cat highlights.txt
```

```txt
Network Administrator @ Synchronet (Jul 2025 – Present)
  ├─ Audit and administer Entra ID, Conditional Access policies, Global
  │   Admin assignments, Named Locations, and MFA settings across
  │   multi-client MSP environments
  ├─ PowerShell automation via Microsoft Graph REST API
  │   (Invoke-MgGraphRequest) for security posture reports, CSV exports,
  │   and automatic PASS / REVIEW / AT RISK compliance flagging
  ├─ Network infrastructure: routers, switches, firewalls, VLAN/DNS/DHCP
  └─ Identity lifecycle, endpoint administration, Exchange Online, Azure AD

IT Technician @ VITEC Solutions (Nov 2023 – Jun 2024)
  └─ Tier 2/3 support, patch management, firewall config, M365 deployments
```

---

```zsh
└─$ ls ./projects/
```

| Project | Stack | Description |
|---|---|---|
| [`Connectwise-MCP-Server`](https://github.com/taddiemason/Connectwise-MCP-Server) | Python · Docker · ConnectWise REST API | Docker integration bridge exposing 18 read-only ConnectWise tools (tickets, assets, contacts, agreements, financials) to AI assistants |
| `m365-entra-audit-suite` | PowerShell · Microsoft Graph REST API · Exchange Online | Audit suite for Global Admin roles, Conditional Access MFA policies, Named Locations, trusted IPs, sign-in frequency, and licensing waste across M365 tenants |
| [`Gmail-MCP-Server`](https://github.com/taddiemason/Gmail-MCP-Server) | Python · Gmail API v1 · OAuth 2.0 · Docker | Middleware translating natural language to Gmail API calls; production OAuth 2.0 with auto-refreshing tokens, attachment parsing, and label management |
| `sms-ai-chatbot` | Python · Vonage SMS API · Groq AI | Routes inbound/outbound SMS through a Groq AI natural-language layer with full API auth and message lifecycle management |

---

```zsh
└─$ cat skills.json | jq '.[]'
```

### Infrastructure & Administration

![Microsoft 365](https://img.shields.io/badge/Microsoft%20365-0d1117?style=flat-square&logo=microsoftoffice&logoColor=58a6ff&labelColor=161b22&color=1f6feb)
![Entra ID](https://img.shields.io/badge/Entra%20ID-0d1117?style=flat-square&logo=microsoftazure&logoColor=58a6ff&labelColor=161b22&color=1f6feb)
![Active Directory](https://img.shields.io/badge/Active%20Directory-0d1117?style=flat-square&logoColor=58a6ff&labelColor=161b22&color=1f6feb)
![Exchange Online](https://img.shields.io/badge/Exchange%20Online-0d1117?style=flat-square&logo=microsoftoutlook&logoColor=58a6ff&labelColor=161b22&color=1f6feb)
![Conditional Access](https://img.shields.io/badge/Conditional%20Access-0d1117?style=flat-square&logo=microsoftazure&logoColor=58a6ff&labelColor=161b22&color=1f6feb)
![ConnectWise](https://img.shields.io/badge/ConnectWise-0d1117?style=flat-square&logoColor=58a6ff&labelColor=161b22&color=1f6feb)

### Networking

![LAN/WAN](https://img.shields.io/badge/LAN%20%2F%20WAN-0d1117?style=flat-square&logoColor=3fb950&labelColor=161b22&color=238636)
![DHCP/DNS](https://img.shields.io/badge/DHCP%20%2F%20DNS-0d1117?style=flat-square&logoColor=3fb950&labelColor=161b22&color=238636)
![Firewalls](https://img.shields.io/badge/Firewalls-0d1117?style=flat-square&logoColor=3fb950&labelColor=161b22&color=238636)
![VPN](https://img.shields.io/badge/VPN-0d1117?style=flat-square&logoColor=3fb950&labelColor=161b22&color=238636)
![VLAN](https://img.shields.io/badge/VLAN-0d1117?style=flat-square&logoColor=3fb950&labelColor=161b22&color=238636)
![Network Monitoring](https://img.shields.io/badge/Network%20Monitoring-0d1117?style=flat-square&logoColor=3fb950&labelColor=161b22&color=238636)

### Scripting & API Integration

![PowerShell](https://img.shields.io/badge/PowerShell-0d1117?style=flat-square&logo=powershell&logoColor=e3b341&labelColor=161b22&color=9e6a03)
![Python](https://img.shields.io/badge/Python-0d1117?style=flat-square&logo=python&logoColor=e3b341&labelColor=161b22&color=9e6a03)
![Microsoft Graph API](https://img.shields.io/badge/Microsoft%20Graph%20API-0d1117?style=flat-square&logo=microsoftazure&logoColor=e3b341&labelColor=161b22&color=9e6a03)
![Gmail API](https://img.shields.io/badge/Gmail%20API-0d1117?style=flat-square&logo=gmail&logoColor=e3b341&labelColor=161b22&color=9e6a03)
![Vonage SMS API](https://img.shields.io/badge/Vonage%20SMS%20API-0d1117?style=flat-square&logoColor=e3b341&labelColor=161b22&color=9e6a03)
![OAuth 2.0](https://img.shields.io/badge/OAuth%202.0-0d1117?style=flat-square&logoColor=e3b341&labelColor=161b22&color=9e6a03)

### Security & Compliance

![Security Audits](https://img.shields.io/badge/Security%20Audits-0d1117?style=flat-square&logoColor=f78166&labelColor=161b22&color=b62324)
![MFA Configuration](https://img.shields.io/badge/MFA%20Configuration-0d1117?style=flat-square&logoColor=f78166&labelColor=161b22&color=b62324)
![SOC 2](https://img.shields.io/badge/SOC%202-0d1117?style=flat-square&logoColor=f78166&labelColor=161b22&color=b62324)
![NIST](https://img.shields.io/badge/NIST-0d1117?style=flat-square&logoColor=f78166&labelColor=161b22&color=b62324)
![ISO 27001](https://img.shields.io/badge/ISO%2027001-0d1117?style=flat-square&logoColor=f78166&labelColor=161b22&color=b62324)
![Identity Lifecycle](https://img.shields.io/badge/Identity%20Lifecycle-0d1117?style=flat-square&logoColor=f78166&labelColor=161b22&color=b62324)

### DevOps & Source Control

![Docker](https://img.shields.io/badge/Docker-0d1117?style=flat-square&logo=docker&logoColor=79c0ff&labelColor=161b22&color=388bfd)
![Docker Compose](https://img.shields.io/badge/Docker%20Compose-0d1117?style=flat-square&logo=docker&logoColor=79c0ff&labelColor=161b22&color=388bfd)
![GitHub](https://img.shields.io/badge/GitHub-0d1117?style=flat-square&logo=github&logoColor=79c0ff&labelColor=161b22&color=388bfd)

---

```zsh
└─$ cat connect.sh
```

```bash
echo "Website:"  https://zacharylalime.com
echo "LinkedIn:" https://www.linkedin.com/in/zachary-lalime
echo "Email:"    zacharylalime@gmail.com
```

---

```zsh
└─$ █
```
