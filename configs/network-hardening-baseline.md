# Network Hardening Baseline

## Management access

- Disable unused management protocols
- Use SSH/HTTPS instead of Telnet/HTTP
- Restrict management access to a dedicated admin network
- Use named administrator accounts where possible
- Enforce strong authentication and centralised AAA where available

## Device configuration

- Disable unused interfaces
- Apply secure banners approved by the organisation
- Configure NTP to trusted sources
- Send logs to central logging/SIEM
- Back up configurations securely
- Use configuration change control

## Switching controls

- Separate user, server, voice, guest, and management VLANs
- Disable unused switch ports
- Use port security or NAC where appropriate
- Protect trunk ports
- Apply storm control where appropriate

## Routing controls

- Authenticate routing protocols where supported
- Filter routes at boundaries
- Avoid unnecessary route redistribution
- Use high availability designs for critical links

## Wireless controls

- Use enterprise authentication where appropriate
- Separate guest wireless from corporate network
- Monitor rogue access points
- Review SSIDs and access policies periodically
