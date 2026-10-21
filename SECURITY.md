# Security Policy

This is the default security policy for repositories owned by **Prekzursil**.
A repository may override it with its own `SECURITY.md`.

## Reporting a vulnerability

- Use **GitHub's private vulnerability reporting** (Security tab →
  *Report a vulnerability*) whenever the repository has it enabled.
- Otherwise, contact the owner privately through the contact channels on the
  profile. Please do **not** open public issues for security-sensitive findings.
- Include: affected repository, component/file, reproduction steps, impact.

## Expectations

- Acknowledgement within **72 hours**.
- A fix, mitigation, or decline decision within **14 days**, workload permitting.
- Coordinated disclosure: please wait for a fix (or 90 days) before publishing.

## Out of scope (all repositories)

- Findings that require already-arbitrary code execution on the reporter's own
  machine (e.g., intentionally pasting malicious code into a local sandbox).
- volumetric concerns: rate limiting, DoS, missing "best practice" hardening
  without a demonstrable impact.
- Vulnerabilities in dependencies of a repository — report those upstream;
  mention them here only if a pinned version in this account is known-vulnerable.
