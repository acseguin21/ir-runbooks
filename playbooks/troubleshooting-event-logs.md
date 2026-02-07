# Troubleshooting with Event Logs and Traces

High-level workflow for using event logs and performance traces to resolve customer issues. Relevant to: utilizes troubleshooting tools (event logs, performance traces); complex product troubleshooting.

## Scope
- Use when the issue is reproducible or leaves traces in Windows Event Log, application logs, or performance data.

## Steps
1. **Reproduce** — Confirm steps; note time range and affected resource (host, app, tenant).
2. **Collect** — Pull relevant event logs (e.g. Application, System, Security) or product-specific logs; capture performance traces if needed.
3. **Correlate** — Map errors/warnings to timestamps and user actions; check for known patterns (KB, team or org docs).
4. **Resolve or escalate** — Apply fix/workaround if known; otherwise document findings and escalate to engineering with logs and impact.
5. **Document** — Update KB or runbook if the root cause is new or the fix is reusable; keep customer informed on status.

## References
- Prefer vendor docs for log locations and event IDs (e.g. Microsoft product docs, Azure/Entra troubleshooting).
