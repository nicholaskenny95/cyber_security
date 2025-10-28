# Policies and Standards
Policy:
- Security gates in CI/CD are mandatory.
- No secrets in code; use secret manager.
Standards:
- Code scanning: SAST + SCA on PR; DAST before release.
- SBOM produced per build; sign artifacts.
- API auth via OAuth2/OIDC; input validation and output encoding; rate limiting.
Compliance: OWASP ASVS, ISO A.8.28, CIS 16.
