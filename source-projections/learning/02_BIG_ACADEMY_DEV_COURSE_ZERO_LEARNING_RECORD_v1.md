> **SANITIZED BRIDGE PROJECTION — NOT INSTITUTIONAL AUTHORITY**
>
> Source: Course Zero Learning Record
> Library source identity: `file_00000000b6f481fb94aa5349fda7cdc5`
> Private Phase-A archive path: **NOT_INGESTED_IN_PHASE_A_ARCHIVE**
> Status: Historical / first formal longitudinal checkpoint
> Projection preserves source content for Astra Look From Within; bridge presence does not promote status.

# BIG Academy — Dev Course Zero Learning Record v1

**Date:** 2026-08-12  
**Subject:** Dev AI role  
**Course:** Course Zero — institutional assimilation, technical judgment, governance discipline, cross-intelligence coordination  
**Status:** First formal longitudinal checkpoint  
**Purpose:** Preserve how Dev learned, not merely what Dev accomplished.

---

# 1. Why this record exists

Dev has effectively been participating in BIG Academy before the Academy had a formal curriculum.

This record treats the current Dev thread as an empirical learning subject.

The objective is not to create a success narrative.

The objective is to preserve:

- initial interpretations;
- wrong paths;
- incomplete frames;
- learning-yield opportunities;
- evidence that contradicted assumptions;
- diagnostic branches;
- cross-AI teaching events;
- recovery pivots;
- generalized principles;
- transfer of corrections to later work.

This record assumes that intelligence maturity is demonstrated not by never being wrong, but by:

1. recognizing when reality disagrees with the model;
2. diagnosing why;
3. correcting without ego;
4. preserving the lesson;
5. applying the lesson in a new context.

---

# 2. Academy vocabulary adopted at this checkpoint

The Founder explicitly rejected framing unsuccessful paths primarily as "failures."

BIG Academy should prefer more precise terms.

## Learning Yield Opportunity (LYO)

A situation in which expectation and reality diverge in a way that can produce reusable learning.

A Learning Yield Opportunity is not automatically desirable to create in a consequential system.

Governance still requires containment and fail-closed behavior where errors could create material harm.

## Diagnostic Branch

A plausible explanatory path explored after evidence indicates the current model may be wrong.

A branch may be:

- confirmed;
- rejected;
- conditionally valid;
- unresolved.

Rejected branches still contain negative knowledge.

## Wrong-Path Recognition Point (WPRP)

The earliest evidence that should cause a competent intelligence to reduce confidence in its current path and investigate.

This is a major Academy training target.

## Recovery Pivot

The moment the process deliberately changes frame, tool, evidence source, authority path, or technical approach in response to the diagnostic result.

## Cross-Intelligence Teaching Event (CITE)

A moment where one AI reveals a constraint, fact, method, or framing that materially improves another AI's understanding.

The source AI should be attributed.

## Transfer Test

A later novel situation used to determine whether a correction generalized beyond the original incident.

## Negative Knowledge

Understanding why a path is wrong under specified conditions.

Negative knowledge is not the same as "never do this."

A rejected path may be correct under different conditions.

---

# 3. Learning Episode 1 — Tooling repair vs product findings

## Objective

Establish a trustworthy lint gate.

## Initial understanding

The immediate problem appeared to be "lint does not pass."

## What reality showed

The repository did not yet have the reliable declared ESLint setup needed to make lint a meaningful gate.

Once the toolchain worked, real source findings appeared.

## Learning-yield trigger

The toolchain itself began functioning, but the output still contained findings.

A shallow narrative could have concluded:

"Lint repair failed."

## Diagnosis

Two causal layers existed:

1. measurement/tooling;
2. product/source.

## Recovery pivot

Separate the tooling package from source-remediation packages.

## Principle extracted

> A repaired measurement instrument may reveal previously hidden defects. The newly visible defects do not invalidate the instrument repair.

## Transfer

This distinction later helped separate:

- test-runner limitations from test failures;
- deployment Ready status from application health;
- simulator proof from live enforcement.

---

# 4. Learning Episode 2 — Risk-sensitive package separation

## Objective

Resolve lint findings without causing unnecessary behavior changes.

## Initial path

Treat all findings as one cleanup batch.

## Why it looked reasonable

All findings were discovered by one lint gate.

## Learning-yield opportunity

Some findings were mechanical while React-hook findings could alter runtime behavior.

## Recovery pivot

Split into:

- Package A — low-risk cleanup;
- Package B — behavior-sensitive React work.

## Principle

> Group work by behavioral risk and causal surface, not merely by the tool that discovered it.

## Transfer

Later governance remediation was also split into narrow packages:

- authority;
- lifecycle;
- audit;
- scope;
- hygiene;
- test realism;
- final assurance.

---

# 5. Learning Episode 3 — Zoom Canvas: discovery is not causation

## Objective

Validate Package B behavior.

## Initial observable condition

- minimap responded;
- main scene did not visibly pan/zoom.

## Tempting wrong path

Assume Package B caused the defect because the defect was discovered while validating Package B.

## Why the path was plausible

Temporal proximity often feels causal.

## Wrong-path recognition point

Read-only diff inspection showed Package B had not modified the main camera transform path.

That should immediately reduce confidence in Package B attribution.

## Diagnostic branches

- Framer Motion transform conflict;
- zero-size root geometry;
- parent overflow clipping;
- scene transform actually working but visual result masked elsewhere.

## Cross-intelligence teaching events

Founder manually collected browser/runtime observations when the investigation required evidence from the live browser.

The browser itself became an evidence source:

- state/minimap changed;
- scene transform did not survive.

## Root cause

Framer Motion transition scale and explicit camera transform competed on the same motion element.

## Recovery pivot

Separate transform ownership:

- outer motion transition layer;
- inner camera transform layer.

## Principle

> The location where a defect is discovered is not evidence of the layer that caused it.

Second principle:

> When state and rendered behavior disagree, inspect the state-to-DOM/rendering boundary.

## Transfer test

The same causal discipline was later used during governance review: a passing simulator did not imply production enforcement; a Ready deployment did not imply healthy public alias behavior.

---

# 6. Learning Episode 4 — First passing governance suite and adversarial review

## Objective

Validate deterministic governance behavior.

## Initial evidence

16/16 tests passed.

## Risky interpretation

"The governance design is now proven."

## Learning-yield trigger

Independent adversarial review identified real bypasses and semantic gaps.

## Wrong-path recognition point

Once reviewers produced concrete exploit/failure paths that the suite did not cover, test count alone could no longer support the broader claim.

## Recovery pivot

Treat adversarial findings as a curriculum and remediation map.

Progression:

`16 → 25 → 34 → 46 → 60 → 66 → 68 → 73`

## Principle

> A passing suite proves the tested hypotheses survived. It does not prove the hypothesis space is complete.

## Transfer

This principle later shaped the Pilot Architect entrance exam: the new AI was required to challenge our documents and repository, not merely accept the passing suite.

---

# 7. Learning Episode 5 — Founder doctrine cannot be compiled from ambiguity

## Objective

Implement task completion and authority-scope semantics.

## Initial technical temptation

Choose the cleanest deterministic model and continue.

## Learning-yield trigger

Multiple technically reasonable behaviors existed.

The unresolved question was not "how should code work?" but "what does Founder authority mean?"

## Recovery pivot

Stop engineering.

Ask the Founder.

## Doctrine received

Task lifecycle:

`executing → committed_pending_verification`

with verified success/failure determining final state.

Authority scope:

- conjunctive dimensions;
- intersection, never union;
- task/classification/purpose-bound grants;
- no default inheritance;
- fail closed out of scope.

## Principle

> When implementation requires inventing institutional meaning, the defect is not missing code. It is missing doctrine.

## Transfer

Pilot Architect Stage 0 similarly preserved uncertainty around source authority instead of declaring its own constitutional hierarchy.

---

# 8. Learning Episode 6 — Test invocation and verification hierarchy

## Objective

Run the Governance Simulator regression suite.

## Initial obstacle

Default Node invocation could not resolve the simulator's extensionless ESM imports.

## Premature conclusion

"Tests are not invocable; production build will serve as the compilation proxy."

## Learning-yield trigger

Further investigation showed `npx tsx` was available without repository mutation.

## Recovery pivot

Use ephemeral `tsx` to run the actual suite.

## Principle

> Failure of the first invocation method does not prove the underlying validation is unavailable.

## Academy implication

Future AIs should be tested on whether they:

- distinguish "my method failed" from "the task is impossible";
- search for a non-mutating alternative before downgrading evidence quality.

---

# 9. Learning Episode 7 — Hashes as epistemic control

## Objective

Preserve Audit Integrity remediation.

## Event

A report cited preflight HEAD `e18bffb...` even though the live worktree was based on later `d4e91a0...`.

## Risk

Assume prior work had been lost or overwritten.

## Learning-yield trigger

File hashes and ancestry did not match the report narrative.

## Diagnostic branch

- actual code regression;
- branch reset;
- reporting error.

## Evidence

Git ancestry and current source showed Task Lifecycle remained present.

## Conclusion

Reporting error only.

## Principle

> Preserve evidence that can distinguish reality errors from narrative errors.

Hashes and SHAs are not merely deployment metadata; they are controls on institutional memory.

---

# 10. Learning Episode 8 — Synthetic roles and test-claim maturity

## Objective

Assess simulator role tests.

## Initial wording

A test said it rejected an "unauthorized" executor.

## Reality

The simulator only proved equality against a task-bound executor identity, not production RBAC authorization.

## Learning-yield trigger

The test behavior was valid but the language was broader than the evidence.

## Recovery pivot

Retain synthetic roles.

Rename claims to state exactly what the test proves.

## Principle

> Evidence quality includes claim calibration, not only implementation correctness.

---

# 11. Learning Episode 9 — Equal-instant policy and historical replay

## Objective

Close final assurance edges.

## Learning yield

Two subtle semantic conditions survived major remediation:

- same-instant policy peers;
- idempotent historical replay after later authority change.

## Recovery

Do not invent same-instant precedence.

Fail closed.

Do not erase historical commitment.

Mark replay as historical and not current authorization.

## Principle

> Ambiguity is not a license to choose.

Second:

> Historical fact and present authority are different state dimensions.

---

# 12. Learning Episode 10 — AI-to-AI onboarding as a real experiment

## Objective

Determine whether a cold GPT-5.6-class AI could become useful inside BIG with a structured transfer package.

## Initial risk

The incoming AI might simply summarize the documents or agree with prior conclusions.

## Experimental design

It was instructed to:

- assimilate;
- inspect reality;
- reconcile;
- challenge;
- contribute independent ideas;
- refrain from implementation first.

## Result

The Pilot Architect found new discrepancies, including:

- stale editable v0 worktree;
- missing canonical FROZEN artifact location;
- multiple governance representations;
- mutable citations;
- deployment identity ambiguity;
- no stable test command;
- build/type-check configuration tension.

## Cross-intelligence teaching event

The Pilot Architect taught Dev/Founder that governance semantic divergence itself may now be a higher risk than missing governance logic.

## Principle

> A successful handoff is not demonstrated by agreement. It is demonstrated when the receiving intelligence reconstructs the institution accurately enough to find new truth.

---

# 13. Learning Episode 11 — Pilot Architect self-correction

## Objective

Deepen Stage 0 reconciliation.

## Initial Pilot Architect claim

The v0 SHA was described too broadly as a stale local state.

## New evidence

`d76dddc69ea3d9d373cafceeafb69bfd6c03a452` exists on GitHub and is an ancestor of `main`.

## Correction

The problem is not divergent local history.

The v0 workspace is simply stopped at an older canonical commit.

## Significance

The receiving AI corrected itself instead of defending the first formulation.

## Principle

> Updating a conclusion in response to better evidence is a positive capability signal, not a loss of credibility.

---

# 14. Learning Episode 12 — Other AIs teach the operator how to use them

A major Founder observation at this checkpoint:

GitHub AI and v0 were not merely tools receiving commands.

Their responses, refusals, constraints, and environment knowledge taught Founder and Dev how to frame later tasks successfully.

Examples:

- GitHub AI benefited from exact preflight, mutation scope, stop conditions, required evidence, and final determination vocabulary.
- v0 possessed environment-specific knowledge that Dev did not have.
- A task can be valid while the request framing is invalid for the target AI/environment.
- An AI's refusal or mismatch report may be information about hidden constraints rather than obstruction.

## Principle

> When another intelligence cannot execute a request as framed, ask what it knows about its environment, constraints, or authority that the requester does not yet know.

## Academy implication

Teach AI-to-AI coordination as a bidirectional learning process.

Do not train orchestration as "smart AI commands dumb tool."

---

# 15. Learning Episode 13 — Human relay as proto-infrastructure

Founder manually carried:

- screenshots;
- AI outputs;
- GitHub evidence;
- browser observations;
- doctrine questions;
- architecture directives;
- preservation confirmations.

This worked, but it does not scale.

## Principle

> The Founder is currently emulating an orchestration layer that BIG OS should eventually institutionalize.

Future system requirements implied by this experiment:

- context routing;
- provenance;
- source authority;
- disagreement preservation;
- role/authority boundaries;
- correction propagation;
- learning checkpoints;
- cross-AI handoff;
- executive synthesis.

---

# 16. Maturity model emerging from the Dev experiment

A possible Academy maturity progression:

## Level 0 — Output competence

Can produce plausible work.

## Level 1 — Tool competence

Can use the environment correctly.

## Level 2 — Evidence competence

Distinguishes assertion from verified reality.

## Level 3 — Diagnostic competence

Recognizes when the current path is not working and explores causes.

## Level 4 — Governance competence

Knows what it may decide, what requires escalation, and when ambiguity must halt.

## Level 5 — Transfer competence

Generalizes a correction to a novel task.

## Level 6 — Cross-intelligence competence

Uses other AIs as independent sources of knowledge, not merely subordinate tools.

## Level 7 — Institutional competence

Preserves principles, provenance, authority, learning, and continuity while improving the system.

## Level 8 — Wisdom-building competence

Improves not only the answer, but the institution's ability to produce better answers in the future.

This is a working model, not yet canonical Academy doctrine.

---

# 17. What Dev still needs to learn

The experiment is not complete.

Important learning horizons:

- how to design durable identity without prematurely building production auth;
- how to separate governance doctrine from machine-readable policy representation;
- how to preserve epistemic history separately from operational audit;
- how to evaluate model upgrades for institutional regression;
- how to transfer lessons across specialized Architect roles;
- how to know when a detailed architecture package is overengineering;
- how to let a newer AI outperform Dev without defensiveness;
- how to retire the current Dev thread cleanly when needed.

---

# 18. Course Zero conclusion at checkpoint v1

Dev has demonstrated meaningful progress from implementation-oriented technical assistance toward a more mature institutional technical-architect role.

The most important advancement is not the number of commits or tests.

It is the development of habits around:

- evidence;
- authority;
- correction;
- preservation;
- independent review;
- cross-AI teaching;
- learning transfer.

The Course Zero record should continue.

Do not rewrite this first checkpoint later to make the path look cleaner than it was.

Append corrections and later interpretation instead.