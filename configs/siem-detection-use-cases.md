# SIEM Detection Use Cases

## Firewall and VPN

| Use case | Log source | Detection logic |
|---|---|---|
| Multiple failed VPN logins | VPN / firewall | Many failures from same user or source IP within defined period |
| Successful VPN login from unusual country | VPN / identity | Geo-location differs from normal pattern |
| Denied traffic spike | Firewall | Increase in denied connections to sensitive zone |
| New inbound rule activity | Firewall | New or changed rule generating external traffic |

## Endpoint

| Use case | Log source | Detection logic |
|---|---|---|
| Malware detected | EDR/AV | High severity malware alert |
| Disabled security agent | Endpoint | Agent stopped or tamper protection event |
| Suspicious PowerShell | Endpoint | Encoded command or download cradle pattern |
| Local admin group change | Windows logs | New member added to privileged group |

## Identity

| Use case | Log source | Detection logic |
|---|---|---|
| Password spray | Identity provider / AD | Failed logins across many accounts from one source |
| Privileged account login outside hours | AD / identity | Admin account used outside baseline hours |
| Impossible travel | Cloud identity | Logins from distant locations within impossible time window |

## Data and recovery

| Use case | Log source | Detection logic |
|---|---|---|
| Mass file modification | File server / EDR | High volume rename/encrypt behaviour |
| Backup job failure | Backup platform | Failed backup for critical system |
| Backup deletion attempt | Backup platform | Deletion or retention policy change event |
