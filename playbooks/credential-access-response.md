# Credential Access — Response Outline

**WIP.** High-level steps only; add environment-specific commands and tooling.

1. **Validate** — Confirm alert/indicator (e.g. LSASS access, credential dump tools).
2. **Scope** — Identify affected hosts and accounts; check for lateral movement.
3. **Contain** — Isolate affected systems; rotate or disable compromised credentials per policy.
4. **Preserve** — Capture artifacts (memory, disk) if needed for forensics before reimaging.
5. **Eradicate** — Remove persistence; reimage if required by policy.
6. **Recover** — Restore from known-good backup or rebuild; verify integrity.
7. **Document** — Timeline, IOCs, and lessons learned for runbook update.
