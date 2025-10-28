# Policies and Standards
Policy:
- All systems must send logs to the central SIEM.
- Logs protected against tampering; retained ≥ 1 year.
Standards:
- Sources: OS, network, security, cloud, apps.
- Time sync via NTP.
- Log fields: timestamp, user, source, event, result.
- Normalize to common schema; tag severity.
Compliance: NIST DE.CM-1, ISO A.8.15.
