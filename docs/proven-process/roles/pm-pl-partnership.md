# PM / PL Partnership — Operating Standard (digest)

*Source: "JourneyTeam: Project Manager / Project Lead Partnership," v1.0, July 2026 (PMO / Practice Directors). This is a structured digest; the Word document is the system of record. Reviewed annually by PMO + practice representatives.*

## Purpose & alignment

Defines how PMs and PLs partner across **PLAN, DELIVER, and LAUNCH**: ownership, decision rights, collaboration expectations, escalation paths, and role boundaries. The PM and PL form the leadership core of the project with a shared commitment to customer outcomes.

## Ownership at a glance

| PM owns | PL owns | Shared |
|---|---|---|
| Delivery governance, project plan, schedule, budget, cadence, stakeholder communication, RAID process, change control, documentation organization, escalation, project closure | Technical direction, solution architecture, backlog readiness, technical estimates, dependencies, acceptance criteria, technical quality, deployment readiness, technical risk mitigation | Project planning, scope alignment, risk visibility, customer readiness, environment governance, status reporting, escalation alignment, unified customer-facing communication |

**Default decision rule:** PM leads delivery decisions; PL leads technical decisions; cross-impact decisions are aligned jointly *before* customer or stakeholder communication.

## Core principles

Mutual respect · shared commitment to project success and customer satisfaction · open and proactive communication · collaborative problem solving · alignment on goals · defined accountability (PM: delivery trade-offs and stakeholder communication; PL: technical decisions, estimates, risks, mitigations) · customer-centricity.

## PM responsibilities (summary)

- **Planning & baselining:** project plan, timeline, milestones, cadence, RAID approach, financial model; incorporates PL's estimates/dependencies/risks; establishes and tracks baselines.
- **Execution, monitoring & control:** delivery execution, project health, corrective actions, formal change process.
- **Stakeholder & customer communication:** primary contact for status, governance, commitments, commercial impacts; status reporting; records meeting decisions and actions.
- **Commitment & cadence management:** coordinates meetings, reviews, planning, retros, steering; tracks commitments; addresses dropped ones.
- **Resource coordination:** attendance, delivery commitments, scheduling; escalates staffing risks with PL and Practice Director.
- **Financial management:** budget, billing, invoices/time-entry accuracy, financial impacts of changes.
- **Risk & issue management:** owns the RAID log; partners with PL so technical risks carry impact statements and mitigation options.
- **Quality support:** organizes/tracks/communicates quality issues; coordinates customer testing logistics.
- **Environment strategy & governance:** tracks environment readiness; manages promotion/deployment/release governance; coordinates cutover, go-live, hypercare, support handoff.
- **Process enforcement & tooling hygiene:** Proven Process adherence; data integrity in Project Operations, Teams, OneNote, repositories.
- **Training coordination** (when the ACM role is vacant): logistics/schedule/comms — not technical content development.
- **Business development support:** communicates new revenue opportunities to the SAM/AE.
- **Project closure:** final reporting, lessons learned, sign-off, transition to support/next phase; sends the retro introduction email to Customer Advocacy or Sales.

## PL responsibilities (summary)

- **Technical ownership & architecture:** primary solution designer; leads technical discussions; drives solution/process documentation.
- **Backlog, requirements & delivery:** creates/refines/maintains backlog; documents requirements, user stories, acceptance criteria; manages sprint execution to scope and budget.
- **Technical planning & estimates:** provides estimates; identifies dependencies/prerequisites/constraints; partners with PM on estimate variances; provides options and impact assessments for trade-offs.
- **Resource & team leadership:** identifies technical resource needs; communicates them to the Practice Director; onboards and coaches the technical team (the Project Developers pool).
- **Customer technical engagement:** leads workshops, design discussions, demos, technical Q&A.
- **Quality assurance:** defines acceptance criteria; confirms delivery through testing; code/design reviews; deployment quality.
- **Environment strategy:** defines environment architecture, security model, lifecycle; configures environments; validates technical readiness; executes promotions/deployments.
- **Technical risk & issues:** identifies technical factors affecting scope/schedule/budget/quality; proposes mitigations; leads technical issue resolution.
- **Training support:** identifies technical training needs; creates supporting documentation.
- **Business development support:** identifies new revenue opportunities (often at closure or when expansion surfaces) and notifies the SAM/AE.
- **Best practices & continuous improvement.**

## Collaboration areas

The standard details nine shared domains (scope, planning & estimation, RAID, change control, customer communication, environments, quality, team leadership, status reporting) — each with PM focus, PL focus, and a shared goal.

## Conflict & escalation

Resolve directly first (facts, project goals, documented agreements). If unresolved and material:

| Issue type | Primary owner | Escalation path |
|---|---|---|
| Scope, schedule, budget, customer commitment, delivery governance | PM | Practice Director |
| Architecture, technical approach, technical quality, standards | PL | Technical practice leadership / architecture review |
| Cross-impact (delivery + technical) | PM and PL jointly | Practice Director and/or technical governance, by primary impact |

PM owns stakeholder communication throughout; PL provides technical content. Decisions are documented in the project system of record.

## Governance of the document

Reviewed annually (or on material change) — PMO coordinates, with Practice Directors, PM/PL representatives, and technical leadership. Related artifacts include the PMO Playbook, kickoff checklists/agendas, RASIC matrix, RAID log template, status report template, change request template, cutover & go-live checklist, adoption checklist, hypercare plan, and the Project Wrap/Customer Signoff/Retrospective template. Version 1.0, July 2026.

---

## Customer Impact integration points (roles are constant — doc 11; no amendments to this standard)

- **Outcome accountability maps cleanly onto the standard's existing split — no new seat needed.** The Impact Hypothesis is a governed project artifact, and the standard already says who governs artifacts: the **PM** carries it (baselines, cadence, stakeholder communication — existing delivery-governance ownership) and the **PL** makes it technically true (metric traceability in stories and acceptance criteria, adoption telemetry as a technical deliverable — existing technical-direction ownership). After close, the thread transfers to the account team through the PM's existing closure duties. The plan's earlier "Outcome Owner role" sketch is retired in favor of this mapping.
- **The decision framework already handles the impact lens.** The standard's joint-evaluation rule (cross-impact decisions aligned before customer communication) covers metric-affecting trade-offs as written: the PL quantifies the effect on the hypothesis metric alongside effort and dependencies; the PM folds it into the delivery trade-off and communicates it — including to the metric-owning executive when material (change-control practice, plan/03-document.md). This is usage of existing decision rights, not a change to them.
- **Both roles already carry a business-development duty — connect it to the flywheel.** PM and PL each must notify the SAM/AE of revenue opportunities. With outcome labeling (which metric the opportunity serves), these notifications become the same VRR-sourced, outcome-labeled leads the Evolve exit gate produces — provenance-tracked per doc 07.
- **The PM's closure duties are the outcome-handoff hook.** "Transition to support or next-phase delivery" and the retro email to Customer Advocacy are where the outcome thread (hypothesis status, first VRR date, adoption telemetry ownership) formally passes to the account team — an existing duty, carrying one more artifact.
- **Impact artifacts live in the existing system of record.** The Impact Hypothesis and Measurement Plan are stored and governed like any other project artifact (Teams site, Project Operations record, OneNote, SharePoint) per the standard's documentation-organization duty — no template-list or standard change required.
