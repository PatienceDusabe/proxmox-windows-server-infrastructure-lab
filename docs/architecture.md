# Architecture and network design

## Diagram (logical)
```text
Proxmox VE hypervisor
├── Windows Server VM (AD DS / DNS)
├── Windows Client VM (domain joined, if verified)
├── Ubuntu Server VM
└── Zabbix Server VM
```

## Recorded lab addresses
- Ubuntu Server: `10.10.10.10`
- Zabbix Server: `10.10.10.30`

Update this file with the verified domain controller address, actual VM names, virtual bridges, operating system versions, and subnet design. Use redacted addresses if posting publicly.
