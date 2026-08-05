# Launch 1 of 3 — Confirm

*Source: internal Proven Process content provided by Igor Zhdanov, Aug 2026.*

The Confirm sub-stage brings JourneyTeam and the customer together to ensure the solution, users, and environment are fully prepared for go-live. Teams validate readiness, finalize plans, and confirm support, escalation, and rollback approaches.

## Key actions

- Code, configurations, and solutions are finalized for the production environment
  - Enforce code/config freeze
- Production System Ready
- End User Readiness
- Escalation Paths established and published
- Support Approach established
- Rollback Approach established

## What "good" looks like

- Solution and environment are production-ready
- Users are trained and prepared
- Deployment and rollback plans are defined
- Support and escalation paths are established
- Stakeholders are aligned and ready for Go-Live

## Who is responsible

Full RASIC chart coming soon.

---

## Customer Impact integration points

Confirm validates that the *system* is ready; for impact engagements it also confirms the *measurement* is ready:

- **Measurement readiness joins the checklist.** Alongside Production System Ready: adoption telemetry configured and tested (dashboards, usage tracking), the baseline snapshot final and archived (the "before" picture is unrecoverable after go-live), and the metric data pipeline confirmed with the customer's data owner. One more readiness line in an existing readiness review.
- **End User Readiness carries the adoption success criteria.** The Deliver exit gate defined user success criteria; Confirm verifies the instruments that will measure them are live *before* users touch the system — day-one usage data is the cleanest adoption signal there is.
- **The go/no-go audience includes the metric owner.** Stakeholder alignment for impact engagements includes the executive who signed the Impact Hypothesis — they confirmed the outcome design at the Deliver gate; they should know go-live starts the clock on it (and when the first VRR will show them numbers).
