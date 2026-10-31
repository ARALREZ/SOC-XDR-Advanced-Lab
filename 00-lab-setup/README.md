# 00 - Lab Setup

Folder zawiera wszystko potrzebne do postawienia i utrzymania laboratorium.

## Aktualna topologia (stan na 2026-10-31)

| Host       | IP              | Rola                     | Status          |
|------------|-----------------|--------------------------|-----------------|
| fedora     | 192.168.122.1   | Hypervisor (libvirt)     | OK              |
| my-server  | 192.168.122.178 | Wazuh Manager 4.9.2 + Suricata 7.0.3 | OK     |
| my-agent   | 192.168.122.208 | Wazuh Agent + Auditd     | OK              |
| kali       | 192.168.122.112 | Atakujący                | OK              |

## Co już działa
- Wazuh Manager + Indexer + Dashboard (4.9.2)
- Suricata 7.0.3 (active)
- Wazuh Agent (active)
- Auditd (active)
