# Proxmox by Linux Zabbix Agent
## Description
This template was created for a full monitoring of Proxmox VE hosts with the Linux Zabbix agent. It includes items for monitoring the state of Proxmox services, cluster quorum, and general system performance metrics. The template is designed to be used with Zabbix 7.4 and may require adjustments for other versions.

## Installation
```bash
sudo wget -P /etc/zabbix/zabbix_agent2.d/ https://raw.githubusercontent.com/engineer-jannik/zabbix-templates/refs/heads/main/Proxmox%20by%20Linux%20Zabbix%20Agent/proxmox.conf
sudo wget -P /etc/sudoers.d/ https://raw.githubusercontent.com/engineer-jannik/zabbix-templates/refs/heads/main/Proxmox%20by%20Linux%20Zabbix%20Agent/zabbix

sudo systemctl restart zabbix-agent2
```