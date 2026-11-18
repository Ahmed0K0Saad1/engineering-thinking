# Learning Decision Record
- Decision ID: LD-2026-11-18-01
- Date: 2026-11-18
- Status: Accepted
- Decision owner: Learner

## Context
The learner approved six improvements after the system onboarding review: project capability must be assessed beyond project existence; session records need a durable home; the first diagnostic needs a named topic and a strict precondition; Unit 0.0 needs a formal specification; workflow progress must not be confused with skill mastery; and Engineering Thinking must be described as a continuous strand while Phase 0 remains before systematic Phase 1 instruction.

## Options
1. Leave the existing documentation as-is and handle the distinctions informally in chat.
2. Update the operational files, templates, and indexes to make the approved rules explicit and reusable.

## Evidence
The approved changes directly address gaps identified in the repository review. The master roadmap's target profile, phases, objectives, and exit outcomes do not need alteration.

## Trade-offs
- Benefits: clearer project evidence, durable audit trail, consistent status semantics, controlled diagnostic start, easier handoff to future assistants.
- Costs: additional documentation and a small number of new files to maintain.
- Risks: duplicated or drifting instructions if future edits do not keep the cross-references aligned.
- Reversibility: documentation changes can be amended through follow-up commits without removing historical records.

## Decision
Option 2 is accepted. Implement the six approved improvements while preserving the master roadmap and all existing learning goals. Do not administer the first diagnostic as part of this decision.

## Consequences
The first diagnostic topic is Problem Understanding & Analytical Thinking, selected but not started. Unit 0.0 remains IN PROGRESS until the learner confirms understanding and explicitly approves the first diagnostic. All learner mastery states remain unchanged.

## Review Trigger
Review when Unit 0.0 is closed, when the session-log workflow is used for the first few learning sessions, or if any status terminology becomes inconsistent.
