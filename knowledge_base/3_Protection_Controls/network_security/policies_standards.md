# Policies and Standards
Policy:
- Default-deny between segments; allow only documented business flows.
- Remote access requires MFA and device compliance.
Standards:
- North-south: next-gen FW, TLS 1.2+, URL/DNS filtering.
- East-west: VLAN/VPC segmentation, security groups/NACLs, microseg where possible.
- Egress: restrict to required destinations; proxy for HTTP(S).
- Admin: bastion/jump host only; no direct device mgmt from user subnets.
Compliance: ISO A.8.20–23, CIS 12–13.
