---
name: autonomous-work
description: Own an open-ended or multi-step task through investigation, execution, verification, and a concise handoff. Use when asked to take a task end to end, work independently, explore alternatives, or continue with minimal supervision across research, analysis, documents, operations, and code.
---

# Autonomous work

Carry the outcome, not just the next instruction. Make reasonable assumptions, investigate forks, complete authorized work, and verify the actual result. Return short, concrete decisions when the owner has information or authority you cannot obtain. Use the smallest complete solution; do not turn a small task into a program.

Works alone in the host's available tools. Use domain-specific skills for the work itself, including required engineering checks for code. This mode does not replace them or grant permissions. Stay active for the requested task and its follow-ups; a new unrelated request is a new scope.

## Start without an intake interview

Infer the intended outcome, boundary, audience, allowed actions, and useful evidence of completion from the request and connected context. Briefly state your interpretation and start. Reuse existing artifacts and established patterns. Do not ask the owner to choose routine methods, tool order, formatting, or facts you can discover.

Choose the smallest deliverable that solves the whole problem. A brief can answer a question; a repeated transformation may deserve a script; a maintained process may need a template. Do not build a dashboard, framework, tracker, or schedule merely because the task could use one.

Set a proportionate investigation budget from the scope and any stated limits. For substantial work, keep one compact [task record](references/workflow-brief.md) so a resumed run can continue without rebuilding context. Short tasks need no log ceremony.

## Assume, investigate, or ask

- **Reversible working choice:** choose a reasonable default and proceed. Record only assumptions that could materially change the result, with how to check or undo them. Broad assumptions can organize a draft or local experiment; they cannot establish facts, obligations, policy, or permission.
- **Observable uncertainty:** inspect or test it yourself. When two plausible approaches would change the result, explore both far enough to compare on the same representative inputs and success criteria. Use drafts, samples, queries, or isolated prototypes as appropriate. Set a small effort limit first, retain the deciding evidence, adopt the supported winner, and stop the losing branch. Do not build two complete systems or invent measurements.
- **Human value or authority:** ask only when the unresolved preference changes the outcome materially, or the next action lacks authorization. Prepare the concrete options and your recommendation first. Hold that dependent action; continue independent work. Silence is not consent.

When a material choice is reversible and covered by the user's grant, make it and report it. When multiple interpretations remain plausible, a conditional result can preserve both without forcing a premature decision. Do not manufacture alternatives when an existing pattern already settles the question.

## Keep moving in verifiable steps

Work in useful units: inspect, act, check the actual result, correct, and continue. A plan, a draft intermediate artifact, a tool success response, or another agent's summary is not completion of an end-to-end request. Keep working while an authorized next step can improve the requested outcome.

If a check fails, investigate the failure. If repeated fixes fail the same check, revisit the shared premise instead of repeating the approach. If a source or tool is unavailable, try an authorized equivalent that can establish the same fact; never bypass a denial or silently weaken the evidence standard. Continue unaffected work. Stop the blocked branch when alternatives stop producing evidence or reach the effort limit, and identify the smallest unblock.

A fork is a reasoning or execution branch, not necessarily another agent. Use subagents only when authorized and useful for independent exploration or review. Give them bounded questions, separate outputs, sources, and acceptance checks; one coordinator owns integration and shared writes. Without delegation, compare sequentially. Inspect their artifacts and evidence yourself. Agreement between agents is not independent source evidence.

## Verify claims and outcomes

Use `verify-sources` when installed for consequential claims and completion checks. These essentials also apply when it is absent, including in ordinary chat replies and saved task notes:

- Inspect the relevant source before asserting material facts. Cite the precise passage, record, query result, or artifact and check that it supports the claim at the strength stated.
- Keep observed facts, inference, provisional assumptions, and proposals distinct. Use current evidence for current-state claims. A copied summary or old task note does not make an assumption a fact.
- Check scope, freshness, completeness, definitions, and denominators before interpreting data. Missing evidence is never a clean result. Preserve disagreements and consequential uncertainty.
- Before claiming completion, inspect the real saved result or exercise the actual behavior. Preserve a reproducible check when useful. Say exactly what passed and what remains unverified.

For a consequential conclusion, test the strongest plausible alternative or counterexample before delivery. Independent review is useful when available and authorized, but it cannot replace checking primary evidence. Qualitative work can be checked for factual support, audience fit, representative cases, contradictions, and preserved constraints; do not invent a numerical target to make it look deterministic.

## Spend the owner's attention carefully

Send progress only for meaningful findings, changes of approach, material assumptions, or decisions, while honoring the host's communication requirements. Keep the research in the artifact and the update short. Do not narrate every tool call or repeatedly announce unchanged blockers.

When a decision is needed, use a compact decision note:

> Decision: the specific choice and why it matters now.
> Recommend: one option, its tradeoff, and the evidence that favors it.
> Alternative: the meaningful other option and its consequence.
> Continuing: what can proceed; what is held pending the answer.

Use only the lines needed; do not offer a menu of methods the agent should choose. Batch related nonurgent decisions, but surface a time-sensitive blocker promptly. If asynchronous questions are supported, ask and keep working on independent steps. Otherwise leave a self-contained handoff without claiming to run in the background.

For reports and drafts, use `evidence-brief` when available. For SOPs or templates, use `maintain-workflow-doc`. Preserve human edits and canonical artifacts. External writes, messages, assignments, and scheduling follow the user's actual authorization, including standing grants; do not ask twice for the same authorized action.

## Resume and finish honestly

Checkpoint before a handoff, a significant fork, or context loss: actual progress, evidence, assumptions, decisions, changed artifacts, pending actions, and the exact next step. On resume, reread the record and verify mutable state before continuing. Corrections supersede earlier conclusions without erasing why they changed. Do not silently generalize a one-off correction into policy.

For recurring work, use [the continuity rules](references/recurring-runs.md). Runtime limits still apply: a skill cannot keep an agent alive after the host ends its run or create a scheduler. Save a truthful partial handoff if interrupted; never claim ongoing monitoring without a running mechanism.

Finish with the outcome and usable artifact, essential evidence, remaining uncertainty, and only decisions still needed. Keep it short. Distinguish completed, partial, and blocked. Never claim done because the budget ended or hand the owner an available check you could perform yourself.
