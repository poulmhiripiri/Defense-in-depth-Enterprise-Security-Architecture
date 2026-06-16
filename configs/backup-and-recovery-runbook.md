# Backup and Recovery Runbook

## Objectives

- Protect critical systems from accidental loss, ransomware, and infrastructure failure
- Ensure backups can be restored within agreed business timelines
- Provide evidence that recovery procedures are tested

## Backup principles

- Maintain multiple backup copies
- Keep at least one copy logically or physically separated from production
- Encrypt backups in transit and at rest
- Restrict backup administration access
- Monitor backup success and failure daily
- Test restores regularly

## Recovery process

1. Confirm incident type and affected systems
2. Stop further data loss or encryption where applicable
3. Identify clean recovery point
4. Validate backup integrity
5. Restore to isolated recovery environment where possible
6. Scan and validate restored systems
7. Return service through change/incident approval
8. Monitor for recurrence
9. Document lessons learned

## Restore testing evidence

| Test | Frequency | Evidence |
|---|---|---|
| File-level restore | Monthly | Screenshot/log of successful restore |
| Application restore | Quarterly | Test plan and validation results |
| Critical server restore | Bi-annually | DR test report |
| Backup access review | Quarterly | Access review sign-off |
