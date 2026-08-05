# Launch 2 of 3 — Deploy

*Source: internal Proven Process content provided by Igor Zhdanov, Aug 2026.*

Deployment brings the solution into production by executing deployment and cutover activities. Teams transition from build to live use, ensuring systems, data, and integrations are in place and ready for users.

## Key actions

- **Execute Deployment:** places the solution into the production-ready environment or state, so it is technically available but not yet operational.
- **Execute Cutover:** executing the activities necessary to operate using the new solution (data migration, integration processes, etc.), according to the approved cutover plan.
- **Post-Cutover Validation:** a set period after cutover, before user access, to check production readiness — data accuracy, integrations, security, etc. Typical duration: hours–days.
- **Go-Live:** the business milestone when users are enabled to begin using the system for real business work.

## What "good" looks like

- Deployment and cutover run smoothly
- Systems, data, and integrations function correctly
- Issues are resolved quickly
- Users transition successfully
- System is live and operating as expected

## Who is responsible

Full RASIC chart coming soon.

---

## Customer Impact integration points

Deploy is the most technical sub-stage; the impact additions are timestamps and telemetry, not process:

- **Go-Live is the measurement epoch.** The Impact Hypothesis's "before/after" splits at this date — record it as the official T₀ in the measurement plan. Every VRR reports metric movement relative to this timestamp; ambiguity about when "after" started is a classic attribution-dispute source (research 03 failure modes).
- **Post-Cutover Validation includes telemetry validation.** The existing validation window (data accuracy, integrations, security) adds one check: adoption/usage telemetry is actually recording. A week of missing day-one usage data is the most common silent hole in adoption evidence.
- **Cutover data migration is a baseline opportunity.** Migration touches the historical data anyway — where the measurement plan needs historical series (cycle times, close days, error rates), capture them during migration rather than as a separate ask later.
