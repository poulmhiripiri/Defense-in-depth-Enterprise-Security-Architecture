# Sample Risk Register

| ID | Risk | Likelihood | Impact | Existing controls | Recommended action | Owner |
|---|---|---:|---:|---|---|---|
| R-001 | Phishing leads to credential theft | 4 | 5 | Email filtering, awareness | Enforce MFA, mailbox search playbook, phishing simulations | Security / IT |
| R-002 | Ransomware encrypts file shares | 3 | 5 | Endpoint protection, backups | Add immutable backup, restore tests, segmentation | Infrastructure |
| R-003 | Flat network allows lateral movement | 3 | 5 | VLANs, firewall | Enforce zone-based segmentation and admin network isolation | Network |
| R-004 | Vulnerabilities remain unpatched | 4 | 4 | Scanning, patching | Define patch SLAs and exception approval | Infrastructure |
| R-005 | Excessive privileged access | 3 | 5 | Admin accounts | Quarterly privileged access review and MFA | IT Management |
| R-006 | Third-party VPN compromise | 3 | 4 | VPN, firewall rules | Time-bound access, MFA, logging, access recertification | Network / Vendor Owner |
| R-007 | Backup failure discovered during incident | 2 | 5 | Scheduled backup | Monthly restore testing and backup monitoring | Infrastructure |
| R-008 | Cloud/SaaS misconfiguration exposes data | 3 | 4 | Admin portal controls | Conditional access, DLP principles, configuration review | Cloud / IT |
