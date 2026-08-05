# 02 — The Customer Impact Framework

## Definition

**Customer Impact** = a measurable change in a customer's business metric that JourneyTeam commits to influencing, and that we baseline, deliver against, and measure — regardless of which technologies or practices are involved.

## Principles

1. **Outcome before architecture.** No proposal above the deal threshold without a stated business outcome and metric.
2. **The customer's metric, not ours.** Impact is stated in their terms (days to close, order cycle time, risk score, adoption %) — never in ours (licenses deployed, reports built, go-live achieved).
3. **Practice-agnostic solutioning.** The outcome determines the practice mix. Sellers are rewarded for the right solution, not the familiar one.
4. **Baseline or it didn't happen.** If we can't measure the current state, the first workstream is establishing the baseline — that itself is billable discovery.
5. **Impact continues after go-live.** Value Realization Reviews are part of the engagement, not an optional QBR.

## The engagement chain

Every Customer Impact engagement follows the same chain:

```
Business Outcome → Capabilities → Solution → Adoption → Measured Impact
```

| Link | Question it answers | Artifact |
|---|---|---|
| **Business Outcome** | What result does an executive want, by when? | Impact Hypothesis |
| **Capabilities** | What must the customer be able to *do* to get it? | Capability map |
| **Solution** | Which Microsoft technologies + which practices deliver those capabilities? | Cross-practice solution design |
| **Adoption** | Who has to change behavior, and how do we make that happen? | Adoption & change plan |
| **Measured Impact** | Did the metric move? What's next? | Value Realization Review |

The discipline is refusing to skip links. Today we jump straight from a tech-labeled lead to "Solution" — which is exactly why deals stay single-practice.

## Core artifacts (defined)

### Impact Hypothesis
One page, attached to every qualified deal above the threshold:
- **Outcome statement:** "Reduce monthly close from 12 days to 5 by Q3 2027."
- **Baseline:** current metric and how it was measured.
- **Value estimate:** what the change is worth in $ (customer's numbers, our math shown).
- **Capability gaps:** what's missing today.
- **Solution sketch:** practices and technologies involved, phased.
- **Measurement plan:** who measures, how often, with what data.

### Value Baseline
The measured current state. Captured during discovery. If the customer can't produce the number, we scope a short baseline workstream — this is a Data & AI entry point on almost every deal.

### Value Realization Review (VRR)
Quarterly post-go-live session with the economic buyer:
- Metric vs. baseline vs. target.
- Adoption data (usage telemetry — Copilot dashboards, D365 usage, report consumption).
- Blockers and next-highest-impact opportunity → the structured cross-sell moment.

## Why this naturally drives cross-practice work

Business outcomes almost never respect practice boundaries:

- "Close the books faster" → **BC ERP** (process/system) + **Data & AI** (reporting, reconciliation automation) + **Copilot** (variance narratives, task automation).
- "Adopt AI safely" → **Data & AI** (data estate readiness) + **Security & Compliance** (Purview, sensitivity labels, access) + **Copilot** (deployment & adoption).
- "Grow revenue per rep" → **Copilot & Dynamics** (Sales, Copilot for Sales) + **Data & AI** (pipeline analytics, forecasting).

We don't have to force collaboration. We have to force the outcome conversation — collaboration falls out of it.

## How this maps onto the Proven Process (which is not changing — doc 11)

Every artifact and motion above lands inside an existing Proven Process step; nothing here is a parallel lifecycle:

| Customer Impact element | Proven Process home |
|---|---|
| Outcome reframe of tech-labeled leads | Envision: Lead Outreach → Strategic Alignment ("Define Business Objectives and Outcomes") |
| Business Outcome Discovery (paid) | Envision: Strategy Session (is or sells the discovery) |
| Impact Hypothesis signed | Envision: Solution Meeting agreements → carried in EOW with the Flag Plant |
| Value Baseline captured | Plan: Discovery (process maps gain numbers); "Customer Impact confirmed" gate criterion |
| Mid-phase impact check | Deliver: Customer Review retros |
| Adoption success criteria & telemetry | Deliver exit gate; Launch: Confirm/Deploy/Stabilize |
| Value Realization Review | Evolve: Validate, delivered through the existing SBR/QBR cadence (first 15 minutes = Impact Scorecard) |
| Next-highest-impact opportunity → new lead | Evolve exit gate ("New Non-Support Project Lead") → back to Envision |

Outcome stewardship maps onto the existing roles the same way — AE/SAM in Envision, PM+PL through Launch, account team + Customer Advocacy in Evolve (doc 11).

## What Customer Impact is NOT

- **Not a change to the Proven Process or project roles.** Both are constants (doc 11). No new stages, gates, meetings, or roles — new content flowing through existing structure.
- **Not outcome-based pricing (yet).** We commit to measuring impact, not to fee-at-risk contracts. Value-linked pricing is a later maturity step (see doc 05).
- **Not a rebrand of QBRs.** The VRR rides the existing SBR/QBR cadence — what changes is its evidence: a contractual baseline set before delivery started, presented as the Impact Scorecard.
- **Not a new practice or team.** It's a shared motion the four practices run together, governed as described in doc 07.
- **Not for every deal.** Small, genuinely single-stack work (a report pack, a tenant hardening sprint) can stay simple. The threshold (proposed: $100K) keeps overhead proportional.
