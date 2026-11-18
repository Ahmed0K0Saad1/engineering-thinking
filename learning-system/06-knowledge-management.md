# Knowledge Management & Recordkeeping

## Principle
The repository is durable learning memory. Chat history is temporary working context, not the authoritative record.

## Record Types
| Record | Purpose |
|---|---|
| Master roadmap | Approved scope and order |
| Current status | Concise current execution snapshot and next authorized action |
| Unit specification | Outcomes, prerequisites, tasks, and exit gate |
| Session log | Detailed historical record of work, evidence, assistance, errors, and validation |
| Mistake record | Repeated errors and correction |
| Knowledge gap | Missing capability and closure plan |
| Decision record | Rationale for material choices |
| Reference record | Source, version, use, limitations |
| Evidence artifact | Code, calculations, diagrams, reports, tests |

## Valid Evidence
Independent solution with reasoning; calculation with units and check; program with tests and explanation; system/data-flow diagram; GIS output with source, CRS, method and validation; professionally reviewed field report where required; model evaluation with baseline, metrics and error analysis.

A completed video, AI answer, copied code, or attractive map alone is not mastery evidence.

## Session Logs
- Permanent location: `learning-system/session-logs/`.
- Naming convention and synchronization rules: `learning-system/session-logs/README.md`.
- Start from `templates/session-log.md`.
- One meaningful session = one new log; preserve historical logs rather than overwriting them.
- Detailed logs hold evidence and history. `09-current-status.md` holds only the current snapshot and links to relevant logs/evidence.
- A session log proposes status changes; it does not silently update the status file or mastery state.

## Status Vocabulary
Use the separate vocabularies in `03-mastery-and-assessment.md`:
- **Workflow statuses:** NOT STARTED, IN PROGRESS, BLOCKED, READY FOR REVIEW, COMPLETED, DEFERRED.
- **Mastery states:** NOT ASSESSED, FAMILIAR, EXPLAINED, APPLIED WITH HELP, APPLIED INDEPENDENTLY, EVALUATED, DEVELOPED, NEEDS REVIEW, DEFERRED.
- **Gate outcome:** GATE PASSED is an exit-gate result, not a workflow status or mastery state.
- **Next-action classification:** Skip for now, Review briefly, Study, Defer, or Needs external/supervised practice. These guide prioritization and are not status labels.

Use the most specific mastery state supported by evidence. Do not mark a whole phase complete because one unit passed.

## Git Practices
- Commit meaningful, reviewable changes with descriptive messages.
- Keep learning notes and unrelated code changes separate.
- Never commit credentials, tokens, private identifiers, or confidential client/employer data.
- Avoid large source datasets/binaries unless licensing and project needs justify them.
- Preserve history; correct records with follow-up commits.
- Link evidence rather than copying entire projects into the journal.

## AI Assistance Disclosure
For substantial AI-assisted work, record what AI contributed, what the learner changed, what the learner understands independently, what tests were performed, and what remains unverified. Honest capability matters more than hiding tool use.
