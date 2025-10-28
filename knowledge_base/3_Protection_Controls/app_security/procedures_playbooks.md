# Procedures and Playbooks
Secure SDLC
1. Plan: threat model for new features.
2. Build: code review with security checklist.
3. Test: SAST/SCA on PR, DAST pre-prod.
4. Release: sign build; deploy via IaC.
5. Operate: monitor, fix vulns within SLA.

Secret Exposure
1. Revoke keys; rotate credentials.
2. Purge history if needed; add detector rule.
3. Post-mortem and training.
