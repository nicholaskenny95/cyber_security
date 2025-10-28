# Policies and Standards
Policy:
- Use approved algorithms and key sizes only.
- Centralized key management; no hard-coded secrets.
Standards:
- TLS 1.2+; prefer 1.3. Strong ciphers only.
- At-rest: AES-256 (or AES-128 if justified).
- RSA ≥ 2048, ECC P-256+; SHA-256+.
- Certs via enterprise PKI/ACME; expiry alarms ≥ 30 days.
Compliance: ISO A.8.24/28, PCI Cryptographic requirements (if applicable).
