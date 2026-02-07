# IR Runbooks

Templates and runbook outlines for incident response. Generic structure — fill in environment-specific details locally.

**Status:** WIP — adding playbooks as I document and generalize them.

## Structure

- `templates/` — blank runbook templates; **customer-status-update.md** for keeping stakeholders informed.
- `playbooks/` — example playbook outlines (sanitized):
  - **post-incident-review.md** — Post-incident learning and continuous improvement.
  - **executive-briefing-outline.md** — Decision-ready briefings; technical → business/risk.
  - **containment-eradication-recovery.md** — Triage → containment → eradication → recovery; MTTC, forensic integrity.
  - **case-triage-and-escalation.md** — Triage meetings, knowledge sharing, readiness follow-up.
  - **troubleshooting-event-logs.md** — Using event logs and traces for resolution.
  - **credential-access-response.md** — IR response outline.

Use these as starting points; adapt to your environment and tooling.

## License

MIT
