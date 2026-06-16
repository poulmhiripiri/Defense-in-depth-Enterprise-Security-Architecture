# Implementation Roadmap

## Phase 1: Stabilise and document

- Confirm asset inventory
- Document network zones and data flows
- Review firewall rules and VPN access
- Confirm backup schedules and restore capability
- Establish risk register and ownership

## Phase 2: Reduce attack surface

- Remove unused firewall rules
- Enforce MFA for remote and privileged access
- Harden network devices and endpoints
- Restrict management access
- Patch high-risk vulnerabilities

## Phase 3: Improve detection

- Centralise logs from firewall, VPN, endpoint, identity, and servers
- Build SIEM use cases for brute force, malware, lateral movement, and privilege escalation
- Define alert triage procedures
- Test escalation paths

## Phase 4: Strengthen resilience

- Implement immutable or offline backup copies
- Test restore of critical systems
- Define RTO/RPO expectations
- Conduct tabletop exercises

## Phase 5: Mature governance

- Schedule quarterly access reviews
- Report risks and remediation progress to leadership
- Track exceptions and compensating controls
- Align control improvements with NIST CSF and CIS Controls
