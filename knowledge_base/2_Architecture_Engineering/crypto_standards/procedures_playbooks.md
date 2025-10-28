# Procedures and Playbooks
Key Lifecycle
1. Generate in HSM/KMS.
2. Store in KMS; restrict by role.
3. Rotate on schedule or incident.
4. Revoke and destroy per policy.

Certificate Management
1. Request via PKI/ACME.
2. Validate domain/ownership.
3. Deploy; monitor expiry.
4. Renew/revoke as needed.

Incident: Key/cert compromise → rotate, revoke, inventory sweep, root-cause.
