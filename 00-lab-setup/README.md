# 00 - Lab Setup

This folder contains everything required to build and maintain the SOC-XDR-Advanced-Lab environment.

## Current Topology (as of 2026-11-01)

| Host       | IP                | Role                              | Status |
|------------|-------------------|-----------------------------------|--------|
| fedora     | 192.168.122.1     | Hypervisor (libvirt)              | OK     |
| my-server  | 192.168.122.178   | Wazuh Manager 4.9.2 + Suricata 7.0.3 | OK  |
| my-agent   | 192.168.122.208   | Wazuh Agent + Auditd              | OK     |
| kali       | 192.168.122.112   | Attacker                          | OK     |

## Currently Working Components

- Wazuh Manager + Indexer + Dashboard (4.9.2)
- Suricata 7.0.3 (active)
- Wazuh Agent (active)
- Auditd (active)
