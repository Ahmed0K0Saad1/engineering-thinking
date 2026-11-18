# Learning Operating Playbook — How to Direct the System

**Audience:** The learner and any AI assistant joining this repository.  
**Purpose:** Turn the roadmap and AI roles into a repeatable, low-distraction operating method.  
**Authority:** The learner owns goals and approvals. The current status and approved roadmap remain the source of truth.

## 1. Expert Assessment of the Learning System

The repository is a learning-management system, not proof of learner competence and not yet a fully specified course for every unit.

### What is already sound
- A coherent hybrid geospatial/software target with AI/GeoAI as an advanced, use-case-driven layer.
- A staged roadmap, prerequisite rules, evidence-based mastery, AI roles, research policy, and human approval of changes.
- A Phase 0 baseline that avoids assuming either zero knowledge or mastery.

### Known limitations to address during execution
1. Each active unit still needs a unit specification, selected sources, exercises, and an exit gate.
2. There is no universal numeric pass threshold; use observed performance and task-specific rubrics.
3. Repeated topics across phases represent different depths: exposure, practical application, and professional depth.
4. Engineering Thinking is a continuous cross-phase strand. Its habits begin during orientation and Phase 0, deepen through practice, and continue through every later phase. Phase 0 is the prerequisite setup/baseline gate before systematic Phase 1 instruction; this does not suspend the continuous use of analytical habits.
5. Phase 6 has distinct professional branches; prioritize by actual opportunity and learner goals.
6. The reference index is discovery material, not a verified bibliography for every unit.
7. English reading/writing and professional communication develop continuously as supporting capabilities.
8. Field work requires approved procedures, manuals, safety practices, qualified supervision, and project specifications.

## 2. Phases, Strands, Units, and Sessions

A phase is a broad maturity stage. A strand is a subject area that can progress alongside another strand. A unit is a bounded outcome. A session is one bounded task.

Engineering Thinking is a **continuous strand**, not merely a one-time phase. Phase 0 comes first for baseline setup and diagnostics. The systematic curriculum for Phase 1 begins after Phase 0's exit gate; however, problem-framing habits may be used lightly during Phase 0 and continue throughout Phases 2–7.

### Recommended operating model
- One primary unit.
- At most one or two directly supporting units.
- One integration task.
- One review loop.

### Default time allocation (heuristic, not a scientific law)
- 60–70%: primary unit and practice.
- 20–30%: directly supporting prerequisite.
- 10–15%: retrieval, correction, and recordkeeping.

## 3. Parallel Study Rules

Parallel study is appropriate only when prerequisites are adequate, the supporting topic directly unlocks the primary unit, outcomes are distinct, and time remains for independent practice and review.

Stop parallel work if it fragments attention, creates concept confusion, or produces no independent evidence.

## 4. Phase Interaction

- **Phase 0:** establish records and run short diagnostics one topic at a time. Do not start full courses.
- **Phase 1:** systematic problem framing, requirements, constraints, risks, trade-offs, and validation. Engineering-thinking habits are used continuously before and after this phase.
- **Phase 2:** math, computing, and geospatial foundations; overlap selectively.
- **Phase 3:** programming and problem solving when relevant prerequisites are adequate.
- **Phase 4:** software and data engineering after practical programming readiness.
- **Phase 5:** geospatial software engineering after Python, data, geometry, and CRS readiness.
- **Phase 6:** applied professional branches prioritized by real opportunities and safe supervision.
- **Phase 7:** AI/advanced geospatial systems after foundations and justified use cases.

## 5. AI Roles — Minimum Effective Team

Use only the smallest team needed. Roles are responsibilities, not separate subscriptions.

| Role | Use it when | Expected output |
|---|---|---|
| Learning Architect | Selecting the next authorized task or resolving dependencies | Bounded brief, prerequisites, exclusions, next action |
| Tutor | A concept is unclear | First-principles explanation, example, misconceptions, learner task |
| Technical Mentor | Implementing/debugging code, SQL, diagrams, or tests | Diagnosis, smallest next fix, validation |
| Geospatial / Domain Expert | Scientific or professional meaning may be wrong | Assumptions, measurement/CRS risks, QC requirements |
| Researcher | A claim, standard, source, or version needs verification | Authoritative sources, editions, sections, limitations |
| Critical Reviewer | A solution or argument needs skeptical review | Prioritized failure modes and verification steps |
| Examiner | Independent capability needs assessment | New task, hint control, evidence-based recommendation |
| Knowledge Manager | A meaningful session or decision has ended | Proposed log/status/reference updates without invented progress |

## 6. Standard Workflows

- **Concept:** Architect if scope is unclear → Researcher if verification is needed → Tutor → learner attempt → review → Examiner at checkpoints → Knowledge Manager.
- **Software:** Architect → Researcher for version-specific facts if needed → Technical Mentor → learner implementation → Critical Reviewer → Examiner → Knowledge Manager.
- **Geospatial/Surveying:** Researcher → Domain Expert → Tutor → safe learner task → Critical Reviewer → qualified human supervision where needed → Knowledge Manager.
- **Priority decision:** Architect → Researcher if external facts matter → Critical Reviewer → learner approval → Knowledge Manager.

Do not invoke every role by default.

## 7. Task Brief Requirements

A good task defines role, context, one observable objective, current evidence, inputs, prerequisites, scope, exclusions, output, validation, assistance boundary, and record.

## 8. Phase 0 Execution Protocol

Phase 0 is a baseline, not a second full curriculum.

### Step 1 — Complete Unit 0.0 before diagnostics
Follow `units/00-unit-0.0-baseline-protocol.md`. Confirm the matrix, project audit, session-log directory/template, status synchronization rules, separate status vocabularies, selected first topic, and readiness checklist. No diagnostic task may be presented until the checklist is complete and the learner explicitly approves.

### Step 2 — First diagnostic
The first diagnostic topic is **Problem Understanding & Analytical Thinking**. Selection is not commencement. Do not teach, hint, or test this topic as a diagnostic until Unit 0.0 is closed and the learner approves.

### Step 3 — Diagnose one small topic at a time
For each topic: explain in own words; apply to a representative task; diagnose an error; transfer to a changed context; record exact assistance. Do not use a large mixed exam.

### Step 4 — Classify the next action
- Skip for now: evidence supports current prerequisites; revisit later.
- Review briefly: recall/application is shaky.
- Study: a prerequisite gap blocks progress.
- Defer: not needed now.
- Needs external/supervised practice: chat cannot validate it safely or realistically.

These are planning actions, not mastery states.

### Step 5 — Prioritize gaps and close Phase 0
Prioritize gaps that block downstream topics, create serious correctness/safety risks, are needed for immediate work, or can be repaired with a bounded exercise.

Close Phase 0 when core-area evidence and assistance levels are recorded, project capability is honestly assessed, priority gaps are visible, one primary execution block is selected, and the logging workflow works. Advanced topics need not be mastered.

## 9. Session Records and Status Synchronization

Create one detailed record per meaningful session in `learning-system/session-logs/`, using the filename convention in that directory's README and `templates/session-log.md`.

The session log is the historical evidence record. `09-current-status.md` is the concise current snapshot. Update the latter only when the current execution state, next authorized action, or approved mastery summary changes; link the supporting log/artifact. Never copy the full session diary into the status file.

## 10. Anti-Distraction and Review

Keep one primary objective, no more than two supporting topics, no unnecessary tools/courses, no project expansion during Phase 0, and one next action per session. Review intended vs actual work and change priorities only with evidence and learner approval.

## 11. Final Operating Principle

The AI team is an instrument panel, not the pilot. The learner owns the objective, judgment, attempt, and final decision. The system succeeds when the learner needs less step-by-step help and can defend work using evidence.
