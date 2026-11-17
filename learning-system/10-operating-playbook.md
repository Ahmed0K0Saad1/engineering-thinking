# Learning Operating Playbook — How to Direct the System

**Audience:** The learner and any AI assistant joining this repository.  
**Purpose:** Turn the roadmap and AI roles into a repeatable, low-distraction operating method.  
**Authority:** The learner owns goals and approvals. The current status and approved roadmap remain the source of truth.

## 1. Expert Assessment of the Learning System

The repository is a strong learning-management foundation, not proof of learner competence and not yet a fully specified course for every unit.

### What is already sound
- A coherent target: Geospatial Science/Engineering + Software Engineering, with AI/GeoAI as an advanced, use-case-driven layer.
- A staged roadmap spanning analytical thinking, mathematics, computing, geospatial science, programming, software/data engineering, applied domains, and AI.
- Explicit prerequisite and parallel-study rules.
- Evidence-based mastery rather than video/course completion.
- AI roles, research policy, session records, and human approval of changes.
- A Phase 0 baseline that avoids assuming either zero knowledge or mastery.

### Known limitations to address during execution
1. The roadmap is a map, not yet a detailed syllabus. Each active unit still needs a unit specification, selected sources, exercises, and an exit gate.
2. The baseline matrix is a starting inventory. It does not yet define a universal numeric score or automatic pass threshold. Use observed performance and task-specific rubrics; do not invent a single percentage.
3. Some topics appear in more than one phase by design. Define the difference between introductory exposure, practical application, and professional depth in each unit.
4. Phase 1 (engineering thinking) should begin early and continue throughout the roadmap. Do not require completing every Phase 1 topic before learning mathematics, programming, or geospatial science.
5. Phase 6 contains distinct professional branches. Do not attempt equal depth in land surveying, hydrography, GIS, and remote sensing simultaneously. Prioritize based on actual work opportunities and learner goals.
6. The reference index is curated discovery material, not a verified bibliography for every unit. Verify the exact source, edition, sections, and relevance when a unit becomes active.
7. English technical reading, technical writing, communication, and professional deliverable quality should be developed continuously as supporting capabilities, not turned into a distracting parallel curriculum.
8. Real field work requires approved procedures, instrument manuals, safety practices, qualified supervision, and project specifications. AI explanations are not field authorization.

### Verdict
The system can support a strong foundation if it is executed with independent practice, feedback, validation, and periodic review. Its value will be measured by the learner's ability to solve unfamiliar tasks without step-by-step AI guidance.

## 2. The Difference Between Phases, Strands, and Parallel Work

A phase is a broad maturity stage. A strand is a subject area that can progress alongside another strand. A session is one bounded learning task.

Do not interpret phase numbers as a rule that only one subject may ever be studied. Also do not interpret the roadmap as permission to study every phase at once.

### Recommended operating model
- One **primary unit**: the main learning objective for the current block.
- At most one or two **supporting units**: only when they directly unlock or reinforce the primary unit.
- One **integration task**: a small exercise that uses the primary and supporting topics together.
- One **review loop**: retrieve earlier learning and check whether it remains usable.

### Default time allocation (a starting heuristic, not a scientific law)
- 60–70%: primary unit and its practice.
- 20–30%: one supporting prerequisite or connected strand.
- 10–15%: retrieval, correction, and recordkeeping.

If the supporting topic starts competing with the primary unit, pause it. If time is very limited, keep one primary topic and brief review only.

## 3. When Is It Safe to Study Topics in Parallel?

Parallel study is appropriate when all of the following are true:
1. The primary unit's essential prerequisites are understood well enough to attempt its tasks.
2. The supporting topic has a direct dependency or practical connection to the primary unit.
3. Each topic has a clearly different learning outcome.
4. The learner can explain which concept is being practiced in each task.
5. The workload still leaves time for independent practice, feedback, and review.
6. The combination reduces fragmentation rather than adding unrelated context switching.

### Stop or reduce parallel work when
- The learner repeatedly confuses concepts from the two topics.
- Neither topic produces independent evidence.
- Sessions become mostly watching, prompting, or collecting resources.
- One topic is being studied only because it looks interesting.
- The learner cannot state the single most important outcome for the week.

### Typical progression and safe overlaps
| Primary focus | Supporting focus | Why they can overlap |
|---|---|---|
| Arithmetic, fractions, units | Introductory measurement examples | Real quantities give meaning to calculations |
| Algebra and formula rearrangement | Surveying/coordinate examples | The examples reinforce formula use |
| Engineering problem framing | A small geospatial decision case | The case gives context without requiring advanced GIS |
| Python fundamentals | Algorithm tracing and decomposition | Both support independent problem solving |
| Coordinate geometry | Survey computation examples | Direct mathematical dependency |
| SQL and relational modeling | Small spatial-data tables | Data modeling reinforces database concepts |
| CRS and geometry fundamentals | Introductory GIS operations | Spatial operations require correct coordinate meaning |
| PostGIS | SQL and spatial reasoning review | Spatial SQL extends both |
| ML fundamentals | Statistics and Python review | Direct prerequisites |
| GeoAI | Geospatial domain evaluation | Model metrics must reflect real spatial task quality |

These are examples, not a fixed weekly schedule. The prerequisite map and the active unit decide readiness.

## 4. How the Phases Should Interact

### Phase 0 — Baseline
Run short diagnostics in separate areas. Do not start all courses. Phase 0 can overlap only with light learning-system setup and low-pressure orientation; it is primarily a diagnostic phase.

### Phase 1 — Engineering Thinking
Start the basic problem-framing habit early. Continue practicing it in every later phase. Advanced requirements, architecture, risk, and trade-off analysis deepen as technical knowledge grows.

### Phase 2 — Foundations
Mathematics, computing, and geospatial science are separate strands. They may overlap selectively when prerequisites and a shared application justify it. Do not study every listed topic concurrently.

### Phase 3 — Programming & Problem Solving
Begin when the relevant computing and math prerequisites are adequate. Continue targeted math and CS support while programming. Do not wait for every advanced math topic.

### Phase 4 — Software & Data Engineering
Requires practical programming and problem-solving readiness. SQL and data modeling may begin as a focused supporting strand before every Phase 3 topic is complete, if the learner can handle basic logic and structured data.

### Phase 5 — Geospatial Software Engineering
Requires working Python, tabular data, geometry concepts, and CRS awareness. Learn the geospatial libraries after understanding the underlying spatial concepts; do not treat library output as proof of spatial correctness.

### Phase 6 — Applied Professional Engineering
A job opportunity can move a specific branch earlier in priority. Study the job's immediate safe prerequisites with qualified supervision. Keep the shared foundations progressing. Choose a primary professional branch based on evidence and opportunity, not anxiety about missing out.

### Phase 7 — AI & Advanced Geospatial Systems
Start ML only when Python, data handling, statistics/probability, and evaluation basics are sufficient. Deep learning and GeoAI require additional foundations. AI-tool literacy (asking questions, checking outputs, privacy, source verification) can be practiced from Phase 0, but this is not the same as studying ML.

## 5. AI Roles — How to Choose the Right One

Roles are responsibilities, not separate subscriptions. One model can switch roles, but it must label the active role and stay within its task.

| Role | Use it when | Give it | Demand this output |
|---|---|---|---|
| Learning Architect | Choosing what to study next or resolving scope/dependencies | Current status, goal, available time, evidence | One bounded task, prerequisites, exclusions, next action |
| Tutor | A concept is unclear | Topic, current understanding, exact confusion | Explanation, example, misconceptions, one learner task |
| Technical Mentor | Implementing or debugging software/data work | Requirements, attempt, code/error, environment | Diagnosis, smallest fix, tests, explanation |
| Geospatial/Domain Expert | Scientific or professional meaning may be wrong | Data, units, CRS/datum, method, task context | Domain assumptions, accuracy risks, QC and validation |
| Researcher | A claim, standard, source, or version must be verified | Exact question and intended use | Primary sources, editions, sections, evidence and limitations |
| Critical Reviewer | A solution exists and needs skeptical review | Proposed solution, assumptions, tests, evidence | Prioritized defects, counterexamples, verification steps |
| Examiner | Testing whether the learner can do it independently | Unit outcomes and allowed hint level | New task, assessment rubric, Pass/Partial/Rework with evidence |
| Knowledge Manager | A meaningful session or decision has ended | Session notes, learner work, assessment | Proposed log/status/reference updates; no invented progress |

### Important distinctions
- **Tutor vs Technical Mentor:** Tutor builds the mental model; Technical Mentor helps apply it to a concrete implementation.
- **Domain Expert vs Critical Reviewer:** Domain Expert checks whether the work makes scientific/professional sense; Critical Reviewer attacks the proposed solution for failure modes across relevant dimensions.
- **Researcher vs Tutor:** Researcher verifies what reliable sources say; Tutor turns verified material into understandable instruction.
- **Examiner vs Critical Reviewer:** Examiner evaluates the learner's independent capability; Critical Reviewer evaluates the artifact or argument.
- **Architect vs Knowledge Manager:** Architect decides the next learning move; Knowledge Manager preserves what actually happened.

## 6. The Default AI Workflow — Minimum Effective Team

Do not summon all eight roles for every question. Use the smallest team that can do the job reliably.

### Ordinary concept session
1. Architect: define one objective (only if scope is unclear).
2. Researcher: verify sources (only if factual freshness, standards, or technical claims require it).
3. Tutor: explain and set an exercise.
4. Learner: attempt without a full solution.
5. Tutor or Technical Mentor: review the attempt.
6. Examiner: test independence at a suitable checkpoint.
7. Knowledge Manager: record the evidence.

### Software implementation session
1. Architect: confirm task and prerequisites.
2. Researcher: check version-specific docs if needed.
3. Technical Mentor: plan the smallest implementation step.
4. Learner: implement.
5. Critical Reviewer: inspect edge cases and failure modes.
6. Examiner: use a new task or explain-back to test understanding.
7. Knowledge Manager: record code/test links and assistance.

### Geospatial or surveying session
1. Researcher: locate authoritative standard/manual/specification.
2. Domain Expert: establish scientific and professional constraints.
3. Tutor: explain underlying concepts.
4. Learner: solve a safe, bounded exercise.
5. Critical Reviewer: check units, coordinate reference, assumptions, uncertainty, and QC.
6. Qualified human supervision: required for real field operations and sign-off where applicable.
7. Knowledge Manager: preserve method, data provenance, and checks.

### Roadmap or priority decision
1. Architect: frame the decision.
2. Researcher: obtain evidence if external facts matter.
3. Critical Reviewer: challenge assumptions and alternatives.
4. Learner: approve or reject.
5. Knowledge Manager: record the decision.

## 7. How to Give AI a Good Task

A professional task request contains:
1. **Role:** What responsibility should the AI perform?
2. **Context:** Which phase/unit/project and why?
3. **Objective:** One result, expressed as an observable outcome.
4. **Known state:** What the learner already understands and the evidence for it.
5. **Inputs:** Files, data, code, sources, constraints.
6. **Prerequisites:** What is already established.
7. **Scope:** What is included.
8. **Out of scope:** What must not be introduced.
9. **Output format:** The exact artifact or response expected.
10. **Validation:** How correctness will be checked.
11. **Assistance boundary:** Hint, review, or full solution?
12. **Record:** What should be logged after the work.

### Weak vs strong request
Weak: "Teach me GIS and Python."

Strong: "Act as Tutor. We are in Phase 0, auditing Python collections. Explain the difference between a list, set, and dictionary using a small survey-record example. Do not teach GIS libraries. Ask me to predict the output of a short example, then give one independent task. Do not reveal the answer before my attempt. End by identifying what evidence would show independent understanding."

## 8. Master Prompt — Learning Session Controller

Use this at the start of a new session after the assistant has read the repository instructions:

```text
You are joining my existing Engineering Thinking & Geospatial Software Learning System.

First obey AGENTS.md. Read the required source-of-truth files and current status.

Assigned role: [ONE ROLE]
Phase/unit: [EXACT ID]
Objective: [ONE OBSERVABLE OUTCOME]
Why it matters: [REAL-WORLD USE]
My current evidence: [WHAT I CAN ALREADY DO]
Prerequisites: [LIST]
Inputs/sources: [FILES OR REFERENCES]
In scope: [LIST]
Out of scope: [LIST]
Assistance level: [HINTS / REVIEW / FULL SOLUTION]
Expected output: [EXACT DELIVERABLE]
Validation: [HOW WE WILL CHECK IT]

Rules:
- Do not create a new roadmap.
- Do not add unrelated courses, frameworks, tools, or projects.
- If a prerequisite is missing, identify the smallest repair task.
- Explain in Arabic and pair important English terms with Arabic meanings.
- Distinguish facts, assumptions, estimates, and recommendations.
- Do not claim that code, sources, or tests were verified unless they were actually checked.
- Let me attempt the task before revealing the full solution unless I explicitly request it.
- Finish with evidence, unresolved gaps, proposed status, and exactly one next action.
```

## 9. Phase 0 Execution Protocol

Phase 0 should produce a useful baseline, not become a second full curriculum.

### Step 1 — Freeze the scope
Audit only the listed areas: math, computing, programming/problem solving, geospatial science, and selected prior project understanding. Do not add AI/ML courses or a new portfolio project.

### Step 2 — Diagnose one small topic at a time
For each topic:
1. Explain it in your own words.
2. Complete one representative task.
3. Identify an error in a flawed example.
4. Try a small variation.
5. Record whether the work was independent, hinted, or directly guided.

Do not use one large mixed exam. Do not let an AI tutor teach the answer before the diagnostic attempt.

### Step 3 — Classify the next action
- **Skip for now:** evidence is strong enough for current prerequisites; revisit in a transfer task later.
- **Review briefly:** concept is familiar but recall/application is shaky.
- **Study:** a prerequisite gap blocks the next target.
- **Defer:** not needed for the next learning block.
- **Needs external/supervised practice:** cannot be validated safely or realistically through chat alone.

These are planning decisions, not permanent labels of intelligence or ability.

### Step 4 — Prioritize gaps
Prioritize a gap when it:
- blocks several important downstream topics;
- creates a serious correctness or safety risk;
- is needed for an immediate job/project task;
- can be repaired with a bounded exercise.

### Step 5 — Close Phase 0
Phase 0 is complete when the baseline matrix contains evidence and assistance levels across the core areas; the learner's strongest and weakest prerequisites are visible; one primary execution block is chosen; and the logging workflow is usable.

Do not require every advanced topic (for example, calculus, deep data structures, or deep learning) to be mastered during the baseline.

## 10. How to Know Whether Learning Is Working

At the end of a unit, ask:
- Can I explain the concept without reading?
- Can I solve a representative problem without step-by-step hints?
- Can I solve a changed version?
- Can I detect a plausible wrong answer?
- Can I explain why the method is appropriate and when it fails?
- Can I validate the result independently?
- Can I connect it to a real surveying/GIS/software task?

If not, keep the unit open or narrow the gap. Do not move on merely because the lesson felt easy.

Use retrieval practice and spaced review. Mix related problem types after basic methods are understood; do not randomly mix unfamiliar topics before the learner has a basic mental model. Learning-strategy research supports practice testing and distributed practice broadly, while the benefits of interleaving depend on the task and feedback conditions.

## 11. Anti-Distraction Rules

1. One primary objective per session.
2. No more than one or two supporting topics.
3. One primary source per unit; add another only to fill a defined gap or independently verify an important claim.
4. No new tool or framework without a concrete task that requires it.
5. Put interesting but nonessential ideas in a deferred list; do not act on them immediately.
6. No portfolio project expansion during Phase 0.
7. Do not ask several models the same broad question. Assign each a narrow role and compare evidence.
8. Do not treat agreement between models as verification.
9. End every session with one next action, not a long list of possible next courses.
10. Review and update the plan at a scheduled checkpoint, not whenever a new idea appears.

## 12. Weekly Review and Change Control

At the end of a week or learning block:
- Compare intended work with actual work.
- Review independent evidence, not just time spent.
- Identify repeated errors and blocked prerequisites.
- Decide whether to continue, reduce scope, or repair a prerequisite.
- Select one primary objective for the next block.
- Record any roadmap change as a proposal with evidence, trade-offs, and learner approval.

A schedule is a hypothesis. Adjust it based on observed learning and available time, not guilt or arbitrary streaks.

## 13. Final Operating Principle

The AI team is an instrument panel, not the pilot. The learner is responsible for the objective, judgment, attempt, and final decision. The system succeeds when the learner needs less step-by-step help over time and can defend work using evidence.
