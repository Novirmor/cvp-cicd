# Security

The maintainers take the security of the CI catalog and the platforms it
builds seriously.

## Reporting a vulnerability

Do **not** open a public issue for a security problem. Instead, use GitHub
private vulnerability reporting on the affected repository:

1. Open the repository on GitHub.
2. Go to **Security** → **Report a vulnerability**.
3. Describe the issue, the affected version, and a minimal reproduction.

Reports are acknowledged within 5 business days. Please give maintainers
time to fix and release before disclosing publicly.

## What this covers

- Vulnerabilities in the reusable workflows themselves (unpinned actions,
  credential leakage, injection through inputs).
- Design flaws in how the catalog handles GitHub App tokens and secrets.
