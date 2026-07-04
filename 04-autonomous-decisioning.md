# Phase 4 — Autonomous Operational Decision-Making (Months 32–48)

Full narrative: see [README.md](../README.md#phase-4--autonomous-operational-decision-making-months-32-48).

## Autonomy Tiering Framework
| Tier | Description | Human Role |
|---|---|---|
| L1 — Advisory | AI recommends; human decides and executes | Full control |
| L2 — Approval-required | AI proposes action; human approves before execution | Gatekeeper |
| L3 — Bounded autonomy | AI executes within pre-approved limits; human monitors, can override | Supervisor |
| L4 — Full autonomy | AI executes and adjusts continuously; periodic human audit only | Auditor |

## Implementation Checklist
- [ ] Classify candidate decisions by reversibility, financial/safety impact, regulatory exposure
- [ ] Select 2–3 pilot domains (e.g., dynamic pricing, fraud blocking, IT auto-remediation)
- [ ] Build simulation/digital-twin test environment before any live deployment
- [ ] Implement guardrail/policy engine constraining agent actions
- [ ] Build immutable audit logging for every autonomous decision
- [ ] Establish guaranteed human override / kill-switch path
- [ ] Require legal/compliance sign-off per autonomy tier before go-live
- [ ] Run 2 consecutive incident-free quarters before expanding tier/scope

See [kpi-dashboard.md](kpi-dashboard.md) and [risk-register.md](risk-register.md) for tracking.
