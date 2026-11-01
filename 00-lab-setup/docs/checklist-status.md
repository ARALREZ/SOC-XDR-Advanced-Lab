# Tools Installation Status

## Already Installed and Working

| Tool                   | Location           | Version / Status     | Notes                    |
|------------------------|--------------------|----------------------|--------------------------|
| Wazuh Manager          | my-server          | 4.9.2                | active                   |
| Wazuh Indexer          | my-server          | 4.9.2                | active                   |
| Wazuh Dashboard        | my-server          | 4.9.2                | active                   |
| Wazuh Agent            | my-agent           | 4.9.2                | active                   |
| Suricata               | my-server          | 7.0.3                | active                   |
| Auditd                 | my-agent           | active               | OK                       |

## To Be Installed / Verified (priority order)

| Priority | Tool                       | Install on           | Status | Notes                              |
|----------|----------------------------|----------------------|--------|------------------------------------|
| 1        | YARA                       | my-agent + my-server | TODO   | Required for scenarios 05 & 08     |
| 2        | Velociraptor Server        | my-server or fedora  | TODO   | Main DFIR server                   |
| 3        | Velociraptor Client        | my-agent             | TODO   | Live response agent                |
| 4        | CyberChef (local)          | fedora / browser     | TODO   | Log analysis                       |
| 5        | Docker                     | my-agent             | TODO   | Scenario 06                        |
| 6        | Zeek (optional)            | my-server            | TODO   | Together with Suricata             |
| 7        | TheHive / Shuffle (later)  | my-server            | TODO   | SOAR – scenario 10                 |
