# Proxmox & Windows Server Enterprise Infrastructure Lab

## Overview
A hands-on infrastructure lab covering Proxmox VE virtualization, Windows Server administration, Active Directory Domain Services (AD DS), DNS, Windows client management, Linux administration, backup recovery, and introductory Zabbix monitoring.

This repository documents practical exam work and separates completed tests from configurations that still require verification.

## Infrastructure components
- **Proxmox VE:** virtual machines, virtual network connections, snapshots, backups, and restoration.
- **Windows Server:** AD DS, DNS services, user and computer administration, Organizational Units (OUs), domain authentication, initial Group Policy exploration, and security/access-control concepts.
- **Windows client:** domain membership, domain login, client administration, Remote Desktop and troubleshooting exercises (add evidence of each activity performed).
- **Ubuntu Server:** Linux administration, network configuration and Zabbix agent setup.
- **Zabbix Server:** installed server and web frontend; Ubuntu host added and an initial monitoring dashboard created. Monitoring results require evidence of recent data before being marked passed.

## Technical skills practiced
Windows Server administration · Active Directory Domain Services · DNS and network configuration · Domain authentication · User and computer management · Organizational Units · Group Policy fundamentals · Windows client administration · Remote Desktop · Network troubleshooting · Proxmox virtualization · Windows security and access control · Linux administration · Monitoring fundamentals

## Implementation summary
1. Deployed a virtual infrastructure with Proxmox VE.
2. Installed Windows Server and configured domain infrastructure.
3. Worked with Active Directory users, computers, and OUs.
4. Configured DNS and tested domain/network connectivity.
5. Performed Windows client administration and remote-access exercises.
6. Explored Group Policy administration; advanced GPO configuration was limited by exam time.
7. Tested Proxmox snapshot rollback and backup restoration.
8. Installed Zabbix components and investigated agent-to-server communication.

## Validation status
| Area | Status | Evidence to add |
|---|---|---|
| Proxmox VM deployment | Completed | VM overview and guest details |
| Proxmox snapshot rollback | Tested successfully | Before/after screenshots |
| Backup restoration | Tested successfully | Restore task log |
| Windows Server / AD DS | Lab activity completed; add specific tests | AD DS role and domain screenshot |
| DNS and domain authentication | Add verification evidence | DNS lookup and domain login |
| Users, computers and OUs | Add verification evidence | ADUC screenshots |
| Group Policy | Introductory exploration only | GPMC screenshot, if available |
| Remote Desktop / access controls | Add verification evidence | Sanitized connection/configuration screenshots |
| Zabbix deployment | Installed and configured | Frontend and dashboard screenshots |
| Zabbix agent metrics | Requires confirmation | Latest data timestamps |

## Repository guide
- [Architecture and network design](docs/architecture.md)
- [Windows Server and AD DS](docs/windows-server-ad.md)
- [DNS, clients, RDP, and security](docs/windows-clients-network-security.md)
- [Proxmox and disaster recovery](docs/proxmox-recovery.md)
- [Monitoring with Zabbix](docs/zabbix-monitoring.md)
- [Validation checklist](evidence/validation-checklist.md)

## Lessons learned
The lab brought virtualization, domain services, client administration, network connectivity and recovery into one infrastructure. Troubleshooting exposed the importance of verifying each service end to end rather than relying on successful installation alone.

## Security / publishing note
Remove passwords, tokens, internal domain names, identifiable hostnames, sensitive IP details, product keys, and user information from screenshots or shared configuration files before publishing.
