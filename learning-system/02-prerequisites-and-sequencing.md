# Prerequisites & Sequencing Rules

## Purpose
The roadmap says what to learn; this file controls readiness and parallel study.

## Cross-Phase Strand and Phase Sequence
Engineering Thinking is a continuous strand, not an isolated phase. Its habits—clarifying the problem, identifying constraints and assumptions, reasoning from evidence, and checking results—may be used lightly during orientation and Phase 0 and should continue throughout every later phase.

Phase 0 is the required baseline/setup gate before the systematic Phase 1 curriculum begins. This sequencing rule does not prohibit using analytical habits in Phase 0; it prevents the full Phase 1 syllabus from displacing the baseline and prerequisite audit.

## Dependency Map
| Topic | Minimum prerequisites |
|---|---|
| Fractions, ratios, units | Arithmetic |
| Algebra | Arithmetic, fractions, negative numbers |
| Equations | Algebraic expressions and inverse operations |
| Geometry | Arithmetic, units, basic algebra |
| Trigonometry | Fractions, algebra, geometry, angles |
| Coordinate geometry | Algebra, geometry, coordinate plane |
| Vectors | Coordinate geometry, algebra |
| Matrices | Arithmetic, algebra |
| Statistics | Arithmetic, fractions, ratios, graphs |
| Probability | Fractions, ratios, basic logic |
| Calculus | Algebra, functions, trigonometry, graphs |
| Numerical methods | Algebra, functions, numerical precision |
| Algorithms | Logic, decomposition, basic programming model |
| Data structures | Variables, control flow, functions, simple algorithms |
| Complexity | Algorithm tracing, loops, data structures |
| Python problem solving | Programming fundamentals and decomposition |
| SQL | Tables, records, keys, logic |
| Database design | Entities, relationships, keys, constraints |
| APIs | HTTP, JSON, programming, client/server |
| Architecture | Requirements, modularity, data flow, testing |
| CRS/projections | Coordinates, Earth models, units, map purpose |
| Survey computations | Arithmetic, algebra, geometry, trigonometry, measurement |
| GeoPandas/Shapely | Python basics, tabular data, geometry, CRS awareness |
| PostGIS | SQL, relational databases, geometry/geography |
| Remote sensing analysis | Raster concepts, spectral fundamentals, statistics, data quality |
| ML | Python, statistics, probability, data preparation, evaluation |
| Deep learning | ML, linear algebra, calculus concepts, optimization |
| GeoAI | Geospatial expertise + ML + domain-specific evaluation |

These are minimum dependencies, not a requirement to master every related subject before making progress.

## Parallel Study Rule
At any time:
- One primary topic receives most attention.
- Up to two supporting topics are allowed only if they directly unlock or reinforce the primary topic.
- One practical task integrates the topics.
- Review of previously learned material is always allowed.

Examples:
- Survey coordinates: primary coordinate geometry/surveying; support algebra and units; apply to point distances.
- Python algorithms: primary decomposition/Python; support logic/data structures; apply to measurement-record filtering.
- Spatial databases: primary SQL/schema; support geometry/CRS; apply to PostGIS queries.

## Mathematics Sequence
Arithmetic/fractions/ratios/units -> algebra/formula rearrangement -> equations -> geometry/angles -> trigonometry -> coordinate geometry -> vectors -> practical statistics/probability -> matrices/linear systems -> numerical methods -> calculus/advanced topics when required.

Statistics may start after arithmetic and basic algebra; it need not wait for calculus.

## Computing Sequence
Computer/file fundamentals -> logic/computational thinking -> programming fundamentals -> algorithm tracing -> collections/data structures -> search/sort/complexity -> SQL/data modeling -> networking/HTTP -> APIs/software design -> architecture/testing/security/deployment.

## Geospatial Sequence
Measurement/units/error -> coordinates/Earth reference surfaces -> datums/CRS/projections -> vector/raster and metadata -> GIS operations/cartography -> data quality -> remote sensing -> spatial programming/databases -> applied domain workflows.

## Allowed Parallel Work
Basic math with computer literacy; math with introductory surveying examples; Python with algorithmic thinking; SQL with relational modeling; GIS concepts with data quality; remote sensing with raster literacy; AI-tool literacy in any phase if it does not replace the task.

## Not Allowed by Default
Multiple new languages; multiple backend frameworks; deep learning before ML/statistics; spatial automation before CRS/geometry concepts; field procedures learned only from AI.

## Change Rule
A real job/project may justify a local reorder. Record evidence, changed dependencies, benefits/costs, and temporary scope. Never silently rewrite the master roadmap.
