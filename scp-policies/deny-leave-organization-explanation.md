## Deny Leave Organization SCP — Explanation

This SCP prevents AWS accounts from leaving the AWS Organization.

### Purpose

It ensures that all member accounts remain under centralized governance and control.

### Why this is important:

- Maintains **centralized billing control**
- Enforces **organization-wide security policies**
- Supports **compliance and auditing**
- Prevents bypass of governance controls

### Risk without this SCP:

Without this restriction, a user with sufficient permissions could remove an account from the organization, bypassing SCPs, security policies, and centralized monitoring.
