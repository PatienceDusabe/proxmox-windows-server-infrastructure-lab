# Zabbix monitoring

## Work carried out
- Installed Zabbix Server and web frontend on the Zabbix VM (`10.10.10.30`)
- Configured an initial dashboard with three widgets
- Added Ubuntu Server (`10.10.10.10`) as a monitoring host
- Installed and configured the Zabbix agent on Ubuntu
- Troubleshot passive agent polling, including server allow-list settings and `zabbix_get` tests

## Verification note
The initial lab report recorded inconsistent remote polling. Later troubleshooting improved connectivity, but upload recent `Monitoring → Latest data` evidence before claiming ongoing successful monitoring.

## Further work
Expand monitoring templates, triggers, alerts, dashboards and retention policies when time permits.
