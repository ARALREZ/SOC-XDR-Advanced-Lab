# SOC-XDR-Advanced-Lab

Zaawansowane laboratorium Detection Engineering, Threat Hunting i Incident Response.

**Zasada główna:** W każdym scenariuszu obecna jest **Suricata** + **Wazuh**.

## Topologia laboratorium

| Rola              | Hostname     | IP                | System          |
|-------------------|--------------|-------------------|-----------------|
| Hypervisor        | fedora       | 192.168.122.1     | Fedora          |
| SIEM + NIDS       | my-server    | 192.168.122.178   | Ubuntu Server   |
| Agent / Ofiara    | my-agent     | 192.168.122.208   | Ubuntu Desktop  |
| Atakujący         | kali         | 192.168.122.112   | Kali Linux      |

## Struktura

- `00-lab-setup/` – instalacja, konfiguracja, inventory
- `01` ... `10` – scenariusze (każdy zawiera folder `suricata/`)
