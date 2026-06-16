# Incident Response Playbook

## Purpose

Provide a practical incident response structure for security events such as phishing, malware, ransomware, suspicious VPN access, firewall alerts, and data exposure.

## Severity model

| Severity | Description | Example |
|---|---|---|
| Critical | Active compromise or major business impact | Ransomware spreading, domain admin compromise |
| High | Confirmed compromise with limited scope | Malware on endpoint, suspicious privileged login |
| Medium | Suspicious activity requiring investigation | Phishing clicked, unusual VPN login |
| Low | Event requiring monitoring or awareness | Blocked malicious attachment |

## Response phases

### 1. Preparation

- Maintain asset inventory
- Define escalation contacts
- Keep backup and restore procedures current
- Ensure logs are retained and searchable
- Train users to report suspicious activity

### 2. Identification

- Review SIEM alerts
- Validate endpoint telemetry
- Check firewall/VPN logs
- Confirm affected users, devices, and data
- Determine incident severity

### 3. Containment

- Isolate affected endpoint
- Disable compromised accounts
- Block malicious IPs/domains where appropriate
- Revoke active sessions and tokens
- Preserve evidence before destructive action

### 4. Eradication

- Remove malware or rebuild system
- Patch exploited vulnerabilities
- Reset credentials
- Remove persistence mechanisms
- Validate firewall and endpoint rules

### 5. Recovery

- Restore affected services
- Monitor for recurrence
- Validate business functionality
- Confirm backup integrity where restore was required

### 6. Lessons learned

- Document root cause
- Update detection use cases
- Improve controls
- Track action owners and due dates
- Report lessons to management

## Example: Phishing incident workflow

1. User reports suspicious email
2. SOC reviews headers, links, attachments, and sender reputation
3. Search mailboxes for similar messages
4. Remove or quarantine emails
5. Check whether any user clicked or submitted credentials
6. Reset credentials and revoke sessions if needed
7. Update awareness material and email filtering rules
