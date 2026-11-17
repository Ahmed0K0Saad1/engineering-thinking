# Master Learning Roadmap

**Direction:** Hybrid Geospatial Science/Engineering + Software Engineering  
**Advanced layer:** AI / GeoAI when justified  
**Initial execution authorization:** Phase 0 only

## Design Principles
- Build transferable foundations before advanced specialization.
- Respect prerequisites; integrate math and computing with real geospatial examples.
- One primary learning focus at a time.
- Judge progress by independent performance and validation, not passive study.
- Adjust depth to real opportunities in land surveying, hydrography, GIS, remote sensing, and geospatial software.
- Phase numbers are sequence markers, not fixed calendar durations.

## Phase Overview
| Phase | Name | Exit outcome |
|---|---|---|
| 0 | Baseline & Learning Setup | Evidence-based starting point and working records |
| 1 | Engineering & Analytical Thinking | Independently analyze unfamiliar problems |
| 2 | Foundations | Practical math, computing, and geospatial foundations |
| 3 | Programming & Problem Solving | Independently implement and test small/medium solutions |
| 4 | Software & Data Engineering | Build reliable database-backed software |
| 5 | Geospatial Software Engineering | Complete spatial data and application workflows |
| 6 | Applied Professional Engineering | Defensible solutions for real surveying/GIS/RS work |
| 7 | AI & Advanced Geospatial Systems | Evaluate AI solutions where they add measurable value |

## Phase 0 — Baseline & Setup
Units: mathematics audit; computing/CS audit; Python/programming audit; geospatial audit; existing-project understanding audit; repository and AI workflow setup.

Topics to inspect:
- Math: arithmetic, fractions, ratios, units, algebra, equations, geometry, trigonometry, coordinate geometry, vectors, matrices, statistics, probability, calculus exposure.
- Computing: architecture, operating systems, files, memory, logic, algorithms, data structures, complexity, networking, command line.
- Programming: Python, functions, collections, loops, files, debugging, testing, Git, independent problem solving.
- Geospatial: surveying, measurement, error, Earth models, geodesy, CRS, datums, projections, GIS, raster/vector, remote sensing, data quality.

**Exit gate:** baseline matrix completed with evidence, assistance level, misconceptions, strengths, and prioritized gaps. Do not relearn everything from zero before this audit.

## Phase 1 — Engineering & Analytical Thinking
1. Problem recognition and context.
2. Problem framing and scope.
3. Stakeholders, users, decision-makers.
4. Objectives and measurable success criteria.
5. Functional requirements.
6. Non-functional requirements.
7. Constraints, assumptions, dependencies, risks.
8. Out-of-scope definition.
9. Data and evidence requirements.
10. Decomposition and abstraction.
11. Logical and algorithmic reasoning.
12. Alternatives and trade-offs.
13. Feasibility and impact.
14. Verification, validation, acceptance criteria.
15. Technical communication and decision records.

Practice: branch-site selection without assuming population alone predicts sales; assessing whether GIS data is fit for a decision; scoping a survey task; turning a software request into testable requirements.

**Exit gate:** independently produce and defend a problem brief with context, objective, stakeholders, requirements, constraints, assumptions, scope, data needs, alternatives, risks, and validation.

## Phase 2 — Foundations

### 2A Mathematics
1. Arithmetic: operations, fractions, decimals, percentages, ratios, units, significant figures.
2. Algebra: variables, expressions, simplification, substitution, formulas.
3. Equations and inequalities: rearranging formulas, linear equations, systems.
4. Geometry: lines, angles, triangles, polygons, circles, area, perimeter, volume.
5. Trigonometry: ratios, inverse trig, sine/cosine rules, bearings and angles.
6. Coordinate geometry: Cartesian coordinates, distance, midpoint, slope, lines.
7. Vectors: magnitude, direction, components, dot product.
8. Matrices: operations, linear systems, transformations; advanced topics only if needed.
9. Statistics: descriptive measures, distributions, sampling, correlation, uncertainty.
10. Probability: events, conditional probability, distributions, expectation.
11. Calculus: limits, derivatives, integrals, rates and accumulation.
12. Numerical methods: rounding, numerical error, iteration, interpolation, residuals.

**Depth policy:** prioritize arithmetic through coordinate geometry and practical statistics. Deep calculus/linear algebra is driven by later applications, not studied indiscriminately.

### 2B Computing & Computer Science
1. Computer architecture: CPU, RAM, storage, I/O.
2. Data representation: binary, decimal, hexadecimal, bits, bytes, text/numbers.
3. Operating systems: processes, threads, memory, permissions, environment variables.
4. Files and file systems: paths, formats, metadata, compression.
5. Logic: propositions, Boolean operations, truth tables.
6. Algorithms: inputs/outputs, state, sequence, selection, iteration, decomposition.
7. Searching and sorting.
8. Data structures: lists/arrays, stacks, queues, hash maps, sets, trees, graphs.
9. Complexity: time/space and Big O intuition.
10. Networking: client/server, IP, DNS, ports, TCP/UDP, HTTP/HTTPS.
11. Command line and shell basics.

### 2C Geospatial Science
1. Surveying purpose, measurement, units, field notes.
2. Error, accuracy, precision, repeatability, uncertainty.
3. Earth models: sphere, ellipsoid, geoid, reference surfaces.
4. Geodesy: coordinates, reference frames, datums, transformations.
5. CRS: geographic/projected coordinates, axis order, units, epochs where relevant.
6. Map projections: distortion, projection families, choosing by purpose/area.
7. Spatial data models: vector, raster, point clouds, tables, trajectories, metadata.
8. GIS fundamentals: layers, attributes, topology, spatial relationships, scale.
9. Cartography: visual hierarchy, symbolization, classification, communication.
10. Spatial data quality: completeness, positional/thematic accuracy, consistency, lineage.
11. Remote sensing: electromagnetic spectrum, interactions, sensors, spatial/spectral/temporal/radiometric resolution, interpretation.

**Exit gate:** solve foundational calculations, interpret units/coordinates, explain CRS/datum/projection distinctions, reason about basic algorithms/data representation, and identify measurement/data limitations.

## Phase 3 — Programming & Problem Solving
Programming model; variables/types; expressions; conditions/loops/state; functions/scope; collections; strings and parsing; files (CSV/JSON/text); algorithm design and tracing; searching/filtering/counting/aggregation/sorting; data structures; exceptions/debugging/logging; modules/packages/environments; OOP when useful; testing and edge cases; readability/refactoring; Git.

Applied exercises: coordinate distance, polygon area, unit conversion, bearings, measurement summaries, invalid-record detection, spatial attribute filtering, simple file processing.

**Exit gate:** independently decompose a new small problem, write readable code, test normal/edge cases, debug, explain data structures and document execution.

## Phase 4 — Software & Data Engineering
Git workflow; relational concepts and normalization; SQL; schema design; PostgreSQL; constraints, indexes, transactions; query performance; requirements; cohesion/coupling/separation of concerns; architecture and sequence diagrams; HTTP/REST/JSON/status codes/idempotency; backend APIs; validation/errors; authentication/authorization; unit/integration/contract testing; security and secrets; Docker; deployment/configuration/logging/monitoring/backups.

**Framework policy:** use one primary backend framework during a learning period. FastAPI is a reasonable continuation given existing exposure. Do not learn FastAPI and Django simultaneously without a concrete comparison objective.

**Exit gate:** build and explain a small database-backed service with requirements, schema, API, tests, validation, error handling, configuration, and reproducible local execution.

## Phase 5 — Geospatial Software Engineering
Formats/metadata (GeoPackage, GeoJSON, Shapefile, GeoTIFF, coordinate CSV); GDAL/OGR; CRS transformations and axis order; GeoPandas; Shapely; geometry validity; spatial predicates; buffer/overlay/clip/dissolve/union/intersection/difference; spatial joins; raster processing; spatial indexes; PostGIS geometry/geography/SRID/GiST; spatial SQL; spatial API design; WebGIS layers/tiles/projections/client-server responsibilities; validation; performance, tiling, caching, reproducibility.

**Exit gate:** inspect, validate, transform, process, store, query, expose/visualize, and quality-check a spatial dataset while explaining limitations.

## Phase 6 — Applied Professional Engineering

### 6A Land Surveying
Field safety and records; control and reconnaissance; Total Station setup/orientation/observations/traverses/setting out; GNSS and RTK concepts; leveling and misclosure; topographic survey; coordinate computation and transformation; traverse adjustment; error propagation; CAD/GIS handoff and independent checks.

### 6B Hydrographic Surveying
Project planning; positioning; bathymetry/sounding; singlebeam/multibeam concepts; horizontal and vertical datums; tides/water levels; sound velocity and relevant corrections; offsets/calibration/uncertainty; data cleaning/coverage/QC; reporting; dredging/harbor change/volume tasks when relevant.

### 6C GIS & Remote Sensing
Suitability modeling; network/accessibility; vector/raster analysis; spatial statistics; image preprocessing and interpretation; classification/change detection/accuracy assessment; decision support; data lineage and uncertainty.

**Professional safety:** AI cannot replace qualified field supervision, instrument manuals, approved project specifications, or professional sign-off. Verify current standards and actual project requirements.

**Exit gate:** complete a real or realistic task with traceable problem statement, data provenance, method, calculations/processing, quality checks, limitations, and reviewable deliverables.

## Phase 7 — AI & Advanced Geospatial Systems
AI/ML framing and when not to use ML; data quality/labeling/leakage/representativeness; statistics and probability; supervised regression/classification; unsupervised learning; baselines/features/metrics/validation/error analysis; model selection/calibration/uncertainty; deep learning; computer vision; GeoAI for imagery/point clouds/trajectories; LLM applications (retrieval, structured output, tools, evaluation, safety); deployment, monitoring, drift, reproducibility, cost.

**Exit gate:** compare an AI solution with a non-AI baseline and show measurable value, data suitability, failure analysis, uncertainty, operational constraints, and limitations.

## Specialization Branches
Shared foundations support later emphasis in land surveying/construction, hydrographic surveying/ports/coastal infrastructure, GIS/remote sensing, or geospatial software/WebGIS/spatial backend. A branch changes depth and priority, not the shared core. Record the reason for prioritization.

## Deferred Unless Justified
Multiple languages/frameworks at once; advanced AI before programming/statistics/data foundations; training large models from scratch by default; certificates without evidence; unrelated portfolio projects; equal depth in every math topic; treating attractive maps as proof of analytical correctness.
