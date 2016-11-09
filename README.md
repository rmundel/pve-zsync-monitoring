[![Code Health](https://landscape.io/github/firaxis/pve-zsync-monitoring/master/landscape.svg?style=flat)](https://landscape.io/github/firaxis/pve-zsync-monitoring/master)

# PVE-Zsync monitoring

## Description

Script for PVE-Zsync(https://pve.proxmox.com/wiki/PVE-zsync) monitoring.

## Requirements

- python 3
- json

## Installing
- Put zsync-zbx.py into /etc/zabbix folder
- Put pve-zsync.conf into /etc/zabbix/zabbix_agentd.conf.d/
- Import template to zabbix - pve-zsync.xml
- Apply pve-zsync to host
