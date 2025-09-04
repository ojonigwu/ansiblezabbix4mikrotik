# ansiblezabbix4mikrotik
Ansible Zabbix 4 MikroTik

An Ansible role for automating the deployment and monitoring of MikroTik devices in Zabbix. This role configures the MikroTik device as an SNMP target and automatically registers it as a host in your Zabbix server with a comprehensive set of pre-configured items, triggers, and graphs.

Key Features:

Fully Automated: Zero-touch deployment from Ansible to a monitored device in Zabbix.

SNMP-Based: Uses the built-in MikroTik SNMP agent for secure and efficient monitoring.

Pre-Built Templates: Includes ready-to-use Zabbix templates for monitoring interfaces, CPU, memory, disk, OSPF, BGP, and more.

Dynamic Host Groups: Automatically places MikroTik hosts into groups based on device type or role.

Idempotent & Safe: Can be run multiple times without causing unintended changes.
