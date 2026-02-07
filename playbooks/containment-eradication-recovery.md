# Containment, Eradication, Recovery Checklist

Structured steps for triage → containment → eradication → recovery. Relevant to: consistent triage, containment, eradication, recovery; preserve forensic integrity; reduce MTTC.

## Containment
- [ ] Isolate affected systems (network segment, host, or account) per severity.
- [ ] Preserve evidence if needed (memory, disk, logs) before reimaging.
- [ ] Document containment actions and time (for MTTC and post-incident review).
- [ ] Notify stakeholders (incident lead, exec, legal) per runbook.

## Eradication
- [ ] Remove persistence (scheduled tasks, registry, accounts).
- [ ] Evict attacker access (credential reset, access revocation).
- [ ] Validate no remaining foothold (spot-check or full sweep per playbook).

## Recovery
- [ ] Restore from known-good backup or rebuild; verify integrity.
- [ ] Re-enable access or systems in a controlled way; monitor for recurrence.
- [ ] Close or hand off to operations; schedule post-incident review.

## SOAR / playbook note
- Where possible, standardize containment actions in SOAR playbooks to reduce MTTC and keep response consistent. Preserve forensic integrity (e.g. snapshot, collect before isolate) when required by policy.
