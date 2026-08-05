# Proven Process — Stage 3: Deliver

*Source: internal Proven Process content provided by Igor Zhdanov, Aug 2026. Internal links point to JourneyTeam SharePoint/Power BI/Dynamics — access-controlled.*

## Purpose

Deliver brings the project to life through execution — teams build, configure, and deliver solutions aligned to the flag plant. It begins once planning is complete and continues until the solution is validated and ready for launch.

## Who leads Deliver

| Leader | Role |
|---|---|
| Ben Miller | Practice Director for CXC |
| Biplab Mandal | COO |

These leaders ensure teams execute with consistency, stay aligned to the flag plant, and deliver measurable outcomes for the customer. Executive leadership + change champion; full RASIC chart to come.

## Sub-stages (a structured cycle, in order)

1. [Plan](https://journeyteam.sharepoint.com/sites/ProjectDelivery/SitePages/Plan(1).aspx)
2. [Review](https://journeyteam.sharepoint.com/sites/ProjectDelivery/SitePages/Review.aspx)
3. [Execute](https://journeyteam.sharepoint.com/sites/ProjectDelivery/SitePages/Execute.aspx)

*(Local sub-stage docs will be added as content is provided, mirroring `envision/` and `plan/`.)*

## How success is measured

**Customer Engagement Rate (CER)** — measures success by the level of active customer participation and engagement throughout delivery, ensuring alignment, adding value, timely feedback, and progress toward project outcomes. ([CER report](https://app.powerbi.com/groups/me/apps/b6a29afa-fcfa-4e68-9f30-767c1fb2a3b3/reports/9fd01160-de68-408a-b27c-255af72caa76/6f2698c0626b8ee464b4?ctid=b59c07c6-9496-463a-ab81-77697ac73d11&experience=power-bi))

**Customer Satisfaction (CSAT)** — external measure of how customers perceive the value and quality delivered throughout an engagement; whether execution, communication, and outcomes met or exceeded expectations. *(Being finalized in Q2 2026.)*

**Leading indicators, by sub-stage:**
- **Plan:** 3 sprints planned ahead (Green: 3 · Yellow: 2 · Red: 0–1). ([Planned Work report](https://jtp.crm.dynamics.com/crmreports/viewer/viewer.aspx?action=run&id=6038d40a-630c-f111-8406-000d3a3529aa&helpID=Planned%20Work.rdl&appid=78854deb-627f-e911-a818-000d3a3b5b14); [sprint planning guide](https://journeyteam.sharepoint.com/sites/ProjectDelivery/SitePages/Project-Sprint-Planning.aspx))
- **Review:**
  - On-budget: percent budget spent aligned with requirement progress (Percent Spent vs. Percent Complete = % features complete × budget-per-feature forecast)
  - Planned vs. Actual (Planned Work vs. CER Effort)
  - Progress of project (% features completed)
- **Execute:**
  - [On-Time](https://journeyteam.sharepoint.com/sites/ProjectDelivery/SitePages/Milestone-Planning.aspx) (% of milestones on-time)
  - Sprint Commitment Met (% of planned commitments completed)

## Exit gate — Production-Ready Approval

Before moving from Deliver to Launch:
1. Customer written sign-off on delivery that aligns with the project Flag Plant:
   1. **Production Readiness** — rollout, adoption, and support plans defined and validated
   2. **User Adoption Preparedness** — end-users enabled with training, communications, and success criteria
   3. **Support Readiness** — clear support model, ownership, and escalation paths in place
   4. **Post Go-Live Alignment** — backlog, known issues, and next steps documented and prioritized
   5. **Handoff Complete** — development and operational transition finalized and customer written sign-off obtained

---

## Customer Impact integration points

Deliver's machinery is delivery-health-focused (rightly so); the plan adds a thin impact thread through the existing cycle rather than new ceremonies:

- **The Review sub-stage hosts the mid-phase impact check.** Review already inspects budget vs. progress; for impact engagements it adds one standing question — *are we still building what moves the metric?* (doc 06). The user-story-to-metric traceability created in Plan/Discovery makes this a five-minute check, not an analysis.
- **CER is a leading indicator of impact, not just delivery.** A disengaged customer can't adopt, and unadopted solutions produce zero measurable impact regardless of build quality. Proposed: for impact engagements, low CER triggers the Outcome Owner (not just the PM) — because the thing at risk is the outcome, not the timeline.
- **Exit-gate items 2 and 4 are where impact survives go-live:**
  - *User Adoption Preparedness* already requires "success criteria" — for impact engagements those criteria are the adoption-telemetry targets from the measurement plan (usage thresholds that historically precede metric movement).
  - *Post Go-Live Alignment* already documents "next steps" — the first VRR date (set at kickoff) and the measurement plan belong on that list, so the handoff hands off the *outcome commitment*, not just the system.
- **"Aligns with the project Flag Plant" sign-off gains the hypothesis.** Where "Customer Impact confirmed" entered at the Plan gate, the Deliver gate's written sign-off references the same Impact Hypothesis — the customer confirms the delivered solution is the one designed to move the metric. This keeps one artifact threaded through both gates.
- **CSAT and impact measurement should be designed together (timely — CSAT is being finalized).** CSAT asks "were you satisfied?"; the VRR asks "did the metric move?" Both are customer-voice instruments and should share cadence and ownership rather than compete for the customer's attention. Worth raising with the CSAT working group now, while the instrument is still in design.

### Watch (routed to backlog)

All Deliver leading indicators measure **delivery health** (sprints, budget, on-time, commitments) — none measure **impact readiness** (baseline still valid, adoption telemetry live, metric owner engaged). That's fine while impact checkpoints live in the milestone definition (Plan stage, still being finalized by PMO) — but if they don't land there, Deliver has no instrument that notices an on-time, on-budget project drifting off-outcome. Depends on the PMO milestone-definition decision.
