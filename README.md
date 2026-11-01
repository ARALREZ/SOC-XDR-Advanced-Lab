# SOC-XDR-Advanced-Lab

Advanced hands-on laboratory focused on **Detection Engineering**, **Threat Hunting**, and **Incident Response**.

**Core principle:** Every scenario includes **Suricata** + **Wazuh**.

## Lab Topology

| Role                | Hostname    | IP                | System          |
|---------------------|-------------|-------------------|-----------------|
| Hypervisor          | fedora      | 192.168.122.1     | Fedora          |
| SIEM + NIDS         | my-server   | 192.168.122.178   | Ubuntu Server   |
| Agent / Victim      | my-agent    | 192.168.122.208   | Ubuntu Desktop  |
| Attacker            | kali        | 192.168.122.112   | Kali Linux      |

## Repository Structure

- `00-lab-setup/` – Lab installation, configuration, inventory and documentation
- `01-ssh-brute-force-advanced/` ... `10-full-attack-chain-soar/` – Individual attack scenarios

Each scenario contains a mandatory `suricata/` folder.
