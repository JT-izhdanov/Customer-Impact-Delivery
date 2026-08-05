---
description: Run one Customer Impact Advisory Board session — test the repo content, enrich the solution, log the session, commit and push
---

You are convening one working session of the Customer Impact Virtual Advisory Board for JourneyTeam's 2027 plan. The board and its ten seats are defined in `docs/advisory-board/00-the-board.md`. All state lives in the repo — reconstruct context from files, not memory.

## 1. Reconstruct state

- Read `docs/advisory-board/00-the-board.md` (seats, their questions, known tensions).
- Read `docs/advisory-board/backlog.md` (agenda queue, open decisions, stop condition).
- List `docs/advisory-board/` session files (`NN-session-*.md`) and read the most recent one, if any, for open items.
- Read the focus document(s) for this session: the top unreviewed/flagged item in the backlog. If the backlog is empty and every plan doc has a passing verdict recorded, do NOT run a meeting — write a short closing note in the backlog, tell the user the board has completed its review cycle, and if running under /loop, stop the loop.

## 2. Convene the meeting

Select the 5–7 seats most relevant to the focus document (always include Rumelt as standing skeptic). For genuinely independent perspectives, spawn parallel subagents — one per selected seat — each given: the seat's section from `00-the-board.md`, the focus document text, and the relevant research doc(s) from `docs/research/`. Each seat must return:

1. **Verdict** on the focus doc: PASS / PASS WITH CONCERNS / OBJECTION.
2. **Strongest critique** grounded in that author's actual published thinking — cite the concept (e.g., "kernel," "trust equation," "move off the solution"), not generic advice.
3. **2–3 concrete suggestions** — enrichments, not just objections: new mechanisms, missing plays, sharper artifacts, things the doc should say and doesn't.
4. **One question for the chair** (Igor) only if it's a genuine decision the plan cannot make for him.

Then synthesize as the meeting chair-of-record:
- Where seats **disagree**, present the tension honestly (per the "Known tensions" table) — do not average it away.
- Sort every suggestion into: **(a) Adopt now** (clear improvement, consistent with prior decisions in the repo), **(b) Propose to Igor** (contested, strategic, or changes a number/commitment), **(c) Reject** (with one-line reason).

## 3. Act on the meeting

- **Apply category (a) edits** directly to the plan documents. Keep edits surgical; preserve the docs' voice and the org's concise, bullet-first style. Never weaken a claim's sourcing — anything research-flagged as unverified stays flagged.
- **Write the session log** as the next `docs/advisory-board/NN-session-<topic-slug>.md`: focus doc, seats convened, verdicts, key arguments (short), tensions surfaced, changes applied (with file paths), proposals for Igor, rejected items.
- **Update `docs/advisory-board/backlog.md`**: record the verdict for the focus doc; a doc with any OBJECTION goes back in the queue for re-review after its issues are addressed; append newly discovered review items; keep the "Decisions awaiting Igor" section current (add new proposals, never silently drop old ones).
- **Commit and push** everything to the current branch with a message summarizing the session (`Board session NN: <focus> — <verdict summary>`).

## 4. Report

End with a short, readable summary for Igor: what the board reviewed, the verdicts, the 2–3 most consequential arguments, what was changed in the repo, and the decisions now waiting on him. Plain prose, no jargon from the session mechanics.

## Ground rules

- One focus document per session — depth beats coverage; the loop provides the coverage.
- Seats argue from their books; they never invent facts about JourneyTeam. Anything unknown about the firm (baselines, current bookings mix, comp structure) is flagged as an assumption in the session log, never fabricated.
- The board advises; Igor decides. Category (b) items wait for him no matter how many sessions pass.
- Each session must leave the repo strictly better: at least one applied improvement or one sharpened decision proposal, else say honestly that the doc passed clean.
