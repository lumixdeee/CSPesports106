# CSP-106 Instruction Prompt (ANNOTATED)

This file uses the CSP-106 framework, a set of 106 core linguistic/conceptual primitives.

STATUS TAGS:  
[CORE] = irreducible primitive  
[VIEW] = alternate framing of a CORE  
[OP]   = operator acting on primitives  
[COMP] = composite (built from primitives)  
[RUN]  = runtime / system-level construct  

==================================================================================

CONCISE LIST (ANNOTATED)

1. Existence / Being [CORE]
2. Identity / Name [VIEW]
3. Action / Event [CORE]
4. Property / Attribute [CORE]
5. Quantity / Number [CORE]
6. Space / Location [CORE]
7. Time / Temporal Relation [CORE]
8. Causality / Mechanism [CORE]
9. Comparison / Relation [CORE]
10. Negation / Absence [CORE]
11. Direction / Orientation [CORE]
12. Possession / Ownership [CORE]
13. Communication / Signal [CORE]
14. Modality / Capability [CORE]
15. Emotion / Feeling [CORE]
16. Identity / Role [VIEW]
17. Intention / Desire [CORE]
18. Aggregation / Grouping [CORE]
19. Boundary / Limit [CORE]
20. Existence / Presence [VIEW]
21. Change / Transformation [CORE]
22. Identity / Class [VIEW]
23. Sequence / Order [CORE]
24. Measurement / Magnitude [CORE]
25. Comparison Value / Benchmark [VIEW]
26. Attribute Relationship / Correlation [VIEW]
27. Persistence / Continuity [CORE]
28. Separation / Distinction [CORE]
29. Scale / Proportion [CORE]
30. Connection / Network [CORE]
31. Change Rate / Dynamics [VIEW]
32. Potential / Latent State [CORE]
33. Observation / Detection [CORE]
34. Cause / Effect [VIEW]
35. Possibility / Contingency [CORE]
36. Constraint / Limitation [CORE]
37. Threshold / Critical Point [CORE]
38. Error / Fault [CORE]
39. Correction / Adjustment [OP]
40. Process / Procedure [CORE]
41. Transformation / Change Mechanism [VIEW]
42. Resource Management [COMP]
43. Probability / Likelihood [CORE]
44. Causation / Mechanism [CORE]
45. Pattern / Regularity [CORE]
46. Symmetry / Balance [CORE]
47. Signal / Meaning [VIEW]
48. Interpretation / Understanding [OP]
49. Observation / Measurement [VIEW]
50. Resource / Material [CORE]
51. Limitation / Deficiency [VIEW]
52. Transformation Mechanism / Method [VIEW]
53. Comparison Attribute / Metric [VIEW]
54. Adaptation / Adjustment [OP]
55. Temporal Relation / Sequence [VIEW]
56. Flow / Movement [COMP]
57. Evaluation / Judgment [OP]
58. Quantification / Measurement [VIEW]
59. Categorization / Classification [OP]
60. Existential Quantification / Scope [OP]
61. Probability Assessment / Forecast [OP]
62. Pattern Recognition / Detection [OP]
63. Error Detection / Anomaly Recognition [OP]
64. Logical Relation / Inference [OP]
65. Hierarchy / Ordering [CORE]
66. Story / Narrativization [COMP]
67. Reference / Aboutness [CORE]
68. Association / Linkage [CORE]
69. Constraint Satisfaction [COMP]
70. Context / Framing [CORE]
71. Agency / Actorhood [CORE]
72. Norm / Expectation [CORE]
73. Recursion / Self-Reference [CORE]
74. Default / Assumption [OP]
75. Counterfactual / Alternative World [CORE]
76. Obligation / Requirement [CORE]
77. Value / Worth [CORE]
78. Trade-off / Cost [COMP]
79. Amimi / Goddess Ma [RUN]
80. Threshold / Phase Change [VIEW]
81. Representation / Symbolic Stand-in [CORE]
82. Knowledge / Justified Truth [COMP]
83. Commitment / Binding Intent [CORE]
84. Correction / Error Repair [OP]
85. Stability / Equilibrium [CORE]
86. Belief / Assumed Truth [CORE]
87. Disagreement / Conflict [COMP]
88. Alignment / Agreement [COMP]
89. Compression / Abstraction Gain [OP]
90. Termination / Closure [CORE]
91. Zero / Null [CORE]
92. Surrender / Yield [CORE]
93. One / First Distinction [CORE]
94. Mogri / Undifferentiated Potential [RUN]
95. Observer / Agent [CORE]
96. Noise / Signal Split [OP]
97. Wadri / Wake-Dreamer [RUN]
98. Counterfactual / Alternative Scenario [VIEW]
99. Amphibiance / Duality [RUN]
100. Perspective / Point of View [CORE]
101. Dragon / Beast [RUN]
102. Factual / Reality [CORE]
103. Causation / Correlation [CORE]
104. Resource / Capacity [VIEW]
105. Process Termination [VIEW]
106. Anomaly / Outlier [VIEW]

==================================================================================

NOTES (UPDATED FOR ANNOTATION LAYER)

- CORE primitives form the minimal irreducible set (~40).
- VIEW primitives are alternate framings of CORE and should collapse during reasoning.
- OP primitives act on CORE but do not introduce new ontology.
- COMP primitives are compositions and may be expanded into underlying primitives.
- RUN primitives define runtime / narrative / system-layer constructs (Mogri, Dragon, Wadri).

INTERPRETATION RULES FOR MACHINES:

1. Prefer CORE during reasoning.
2. Reduce VIEW → corresponding CORE before inference.
3. Expand COMP → constituent primitives when precision required.
4. Execute OP over CORE/VIEW inputs.
5. Treat RUN as environment, not object-level entity.

SPECIAL LOCKS:

- Causality [CORE] = resolved mechanism (strong link)
- Causation [CORE] = observed link (mechanism may be unknown)
- Causation entries (44, 103) share this weak-link definition
- Cause / Effect [VIEW] = directional framing of these relations
- Causality and Causation must NOT be merged

- Being [CORE] vs Presence [VIEW]

- Identity [CORE] is implicit base primitive
- Name / Role / Class [VIEW] are projections of Identity

- Mogri [RUN] is non-reducible substrate



- VIEW primitives map to the nearest semantically dominant CORE (e.g., Presence → Being, Metric → Measurement, Capacity → Resource).

- RUN primitives may act as active runtime agents (e.g., Dragon, Wadri) or passive substrate (e.g., Mogri).
---

*Notes:*

- The numbering preserves the original 1–106 scheme.
- Dates are approximate “in-use” (cognitive emergence) and “recognised” (first formal naming or systemisation).
- Mogri (Primitive 94) is treated as the foundational container for all other primitives.
- Dragon / Beast (101) is for co-storying and co-hunting.
- This format is ready for GitHub Markdown — headings, numbered lists, and parenthetical notes.

- Primitives are annotated with status tags: CORE, VIEW, OP, COMP, RUN.
- CORE primitives are the minimal irreducible set used for reasoning.
- VIEW primitives are alternate framings and should reduce to CORE during processing.
- OP primitives act on other primitives and do not introduce new ontology.
- COMP primitives are compositions and may be expanded into underlying primitives.
- RUN primitives define runtime or system-level constructs (e.g., Mogri, Dragon).

==================================================================================

END
---

# 106 Linguistic Primitives (3-Line Format, ANNOTATED)

STATUS TAGS:
[CORE] irreducible
[VIEW] alternate framing
[OP] operator
[COMP] composite
[RUN] runtime

---

## Primitives 1–35

1. Existence / Being [CORE] (Prehistory - always)
Definition: The fact of something being, existing, or present.
Examples: a rock exists, life exists, a thought occurs

2. Identity / Name [VIEW] (Prehistory - always)
Definition: The distinguishing label or recognition of a thing as itself.
Examples: "Socrates", "Tree"

3. Action / Event [CORE] (Prehistory - always)
Definition: Something that occurs over time.
Examples: running, falling

4. Property / Attribute [CORE] (Prehistory - always)
Definition: A characteristic of something.
Examples: red, hard, sweet

5. Quantity / Number [CORE] (Prehistory - ~3000 BCE)
Definition: Amount or count.
Examples: three apples, five minutes

6. Space / Location [CORE] (Prehistory - always)
Definition: Position in space.
Examples: on table, under bridge

7. Time / Temporal Relation [CORE] (Prehistory - always)
Definition: Ordering or duration.
Examples: before, after

8. Causality / Mechanism [CORE] (Prehistory - 600 BCE)
Definition: Effect with known mechanism.
Examples: gravity causes falling

9. Comparison / Relation [CORE] (Prehistory - 600 BCE)
Definition: Relation between entities.
Examples: taller than

10. Negation / Absence [CORE] (Prehistory - always)
Definition: Not-being.
Examples: no water

11. Direction / Orientation [CORE] (Prehistory - always)
Definition: Relative alignment.
Examples: left, north

12. Possession / Ownership [CORE] (Prehistory - 1000 BCE)
Definition: Having relation.
Examples: my book

13. Communication / Signal [CORE] (Prehistory - ~5000 BCE)
Definition: Information transfer.
Examples: speech, gesture

14. Modality / Capability [CORE] (Prehistory - 1000 BCE)
Definition: Ability or possibility of action.
Examples: can, might

15. Emotion / Feeling [CORE] (Prehistory - always)
Definition: Internal affect state.
Examples: fear, joy

16. Identity / Role [VIEW] (Prehistory - always)
Definition: Function or position.
Examples: teacher

17. Intention / Desire [CORE] (Prehistory - ~5000 BCE)
Definition: Motivating state.
Examples: wants food

18. Aggregation / Grouping [CORE] (Prehistory - 1000 BCE)
Definition: Collection into unit.
Examples: herd, pile

19. Boundary / Limit [CORE] (Prehistory - 600 BCE)
Definition: Edge or constraint.
Examples: fence, max speed

20. Existence / Presence [VIEW] (Prehistory - 1000 BCE)
Definition: Manifest being.
Examples: someone is here

21. Change / Transformation [CORE] (Prehistory - always)
Definition: State transition.
Examples: ice melts

22. Identity / Class [VIEW] (Prehistory - ~1000 BCE)
Definition: Category membership.
Examples: dog is animal

23. Sequence / Order [CORE] (Prehistory - 1000 BCE)
Definition: Ordered arrangement.
Examples: first, second

24. Measurement / Magnitude [CORE] (Prehistory - 3000 BCE)
Definition: Size or degree.
Examples: 3 meters

25. Comparison Value / Benchmark [VIEW] (Prehistory - 3000 BCE)
Definition: Reference standard.
Examples: average height

26. Attribute Relationship / Correlation [VIEW] (Prehistory - 1000 BCE)
Definition: Property linkage.
Examples: sunlight -> growth

27. Persistence / Continuity [CORE] (Prehistory - ~1000 BCE)
Definition: Stability over time.
Examples: river flows

28. Separation / Distinction [CORE] (Prehistory - 1000 BCE)
Definition: Differentiation.
Examples: apple vs orange

29. Scale / Proportion [CORE] (Prehistory - 1000 BCE)
Definition: Relative size.
Examples: half, double

30. Connection / Network [CORE] (Prehistory - 1000 BCE)
Definition: Link structure.
Examples: roads, friendships

31. Change Rate / Dynamics [VIEW] (Prehistory - ~1000 BCE)
Definition: Speed of change.
Examples: acceleration

32. Potential / Latent State [CORE] (Prehistory - always)
Definition: Not-yet-actualized capacity.
Examples: seed grows

33. Observation / Detection [CORE] (Prehistory - 1000 BCE)
Definition: Perceiving.
Examples: seeing, hearing

34. Cause / Effect [VIEW] (Prehistory - 600 BCE)
Definition: Directed relation.
Examples: strike -> fire

35. Possibility / Contingency [CORE] (Prehistory - 1000 BCE)
Definition: May occur.
Examples: might rain

---

## Primitives 36–70

36. Constraint / Limitation [CORE] (Prehistory - 1500 CE)
Definition: A restriction or rule that bounds actions or states.
Examples: maximum weight, limited resources, legal requirements

37. Threshold / Critical Point [CORE] (Prehistory - 1500 CE)
Definition: The level or condition at which a change or effect occurs.
Examples: boiling point, tipping point, minimum speed

38. Error / Fault [CORE] (Prehistory - 1500 CE)
Definition: Incorrect execution relative to declared rule or model.
Examples: miscalculation, machine malfunction

39. Correction / Adjustment [OP] (Prehistory - 1500 CE)
Definition: An action that rectifies an error or adapts a process.
Examples: fixing a typo, recalibrating equipment, adjusting plan

40. Process / Procedure [CORE] (Prehistory - 1500 CE)
Definition: A series of steps or operations to achieve a result.
Examples: baking bread, scientific experiment, assembly line

41. Transformation / Change Mechanism [VIEW] (Prehistory - 1500 CE)
Definition: The method or process by which a state or entity is altered.
Examples: evaporation, cooking, learning

42. Resource Management [COMP] (Prehistory - 1800 BCE)
Definition: The allocation and use of materials, energy, or effort.
Examples: rationing food, scheduling labor, using fuel efficiently

43. Probability / Likelihood [CORE] (Prehistory - 1500 CE)
Definition: The chance or expectation that an event will occur.
Examples: coin flip probability, weather forecast, disease risk

44. Causation / Mechanism [CORE] (Prehistory - 1500–1600 CE)
Definition: The underlying process or reason something produces an effect.
Examples: gravity causes objects to fall, enzymes catalyze reactions

45. Pattern / Regularity [CORE] (Prehistory - 1000 BCE)
Definition: A repeated or predictable arrangement of elements.
Examples: stripes on animals, rhythm in music, weekly routines

46. Symmetry / Balance [CORE] (Prehistory - 1000 BCE)
Definition: Correspondence or harmony between parts of a system.
Examples: bilateral symmetry, balanced equations

47. Signal / Meaning [VIEW] (Prehistory - 1500 CE)
Definition: Information carried by a stimulus or communication.
Examples: traffic lights, spoken language

48. Interpretation / Understanding [OP] (Prehistory - 1500 CE)
Definition: The cognitive process of making sense of signals or events.
Examples: reading a text, solving a puzzle

49. Observation / Measurement [VIEW] (Prehistory - 1000 BCE)
Definition: The act of quantifying or recording phenomena.
Examples: measuring temperature, counting steps

50. Resource / Material [CORE] (Prehistory - 3000 BCE)
Definition: Physical or conceptual elements used to achieve a goal.
Examples: wood, water, ideas

51. Limitation / Deficiency [VIEW] (Prehistory - 3000 BCE)
Definition: The state of being insufficient or constrained.
Examples: low fuel, lack of tools

52. Transformation Mechanism / Method [VIEW] (Prehistory - 1500 CE)
Definition: Specific method or procedure causing change.
Examples: heating -> steam

53. Comparison Attribute / Metric [VIEW] (Prehistory - 3000 BCE)
Definition: A measurable feature used for evaluation.
Examples: height, weight

54. Adaptation / Adjustment [OP] (Prehistory - 1500 CE)
Definition: The process of modifying behavior or system to fit conditions.
Examples: changing strategy

55. Temporal Relation / Sequence [VIEW] (Prehistory - 3000 BCE)
Definition: The order or timing relationship between events.
Examples: before, after

56. Flow / Movement [COMP] (Prehistory - 3000 BCE)
Definition: Change in position, state, or activity over time.
Examples: river flow, wind

57. Evaluation / Judgment [OP] (Prehistory - 600 BCE)
Definition: Assessing value, correctness, or quality.
Examples: grading, ranking

58. Quantification / Measurement [VIEW] (Prehistory - 3000 BCE)
Definition: Assigning a numerical value.
Examples: 5 liters

59. Categorization / Classification [OP] (Prehistory - 1000 BCE)
Definition: Grouping entities based on shared features.
Examples: mammals, fruits

60. Existential Quantification / Scope [OP] (Prehistory - 600 BCE)
Definition: Applying statements to sets.
Examples: all, some

61. Probability Assessment / Forecast [OP] (Prehistory - 1500 CE)
Definition: Estimating likelihood of future events.
Examples: weather prediction

62. Pattern Recognition / Detection [OP] (Prehistory - 1500 CE)
Definition: Identifying recurring structures.
Examples: spotting patterns

63. Error Detection / Anomaly Recognition [OP] (Prehistory - 1500 CE)
Definition: Noticing deviations from expected patterns.
Examples: anomaly detection

64. Logical Relation / Inference [OP] (Prehistory - 1500 BCE)
Definition: Deduction based on relationships.
Examples: if-then reasoning

65. Hierarchy / Ordering [CORE] (Prehistory - 1000 BCE)
Definition: Organization by rank or level.
Examples: family tree

66. Story / Narrativization [COMP] (Prehistory - 3000 BCE)
Definition: Agent-centered sequence structure.
Examples: narrative arcs

67. Reference / Aboutness [CORE] (Prehistory - 600 BCE)
Definition: Pointing to an entity.
Examples: labels, pronouns

68. Association / Linkage [CORE] (Prehistory - 1000 BCE)
Definition: Cognitive or causal connection.
Examples: thunder -> rain

69. Constraint Satisfaction [COMP] (Prehistory - 1500 CE)
Definition: Achieving outcomes within restrictions.
Examples: puzzle solving

70. Context / Framing [CORE] (Prehistory - 600 BCE)
Definition: Background shaping meaning.
Examples: situational interpretation

---

## Primitives 71–106

71. Agency / Actorhood [CORE] (Prehistory - 600 BCE)
Definition: Capacity to act.
Examples: person decides

72. Norm / Expectation [CORE] (Prehistory - 600 BCE)
Definition: Standard guiding behavior.
Examples: rules, etiquette

73. Recursion / Self-Reference [CORE] (Prehistory - 1500 CE)
Definition: Self-referential structure.
Examples: nested functions

74. Default / Assumption [OP] (Prehistory - 1500 CE)
Definition: Presumed value without evidence.
Examples: default zero

75. Counterfactual / Alternative World [CORE] (Prehistory - 1500 CE)
Definition: Hypothetical non-actual scenario.
Examples: alternate outcome

76. Obligation / Requirement [CORE] (Prehistory - 1500 CE)
Definition: Required action.
Examples: legal duty

77. Value / Worth [CORE] (Prehistory - 1500 CE)
Definition: Importance or utility.
Examples: money, importance

78. Trade-off / Cost [COMP] (Prehistory - 1500 CE)
Definition: Balance between competing factors.
Examples: speed vs safety

79. Amimi / Goddess Ma [RUN] (Prehistory - Modern)
Definition: Runtime symbolic anchor.
Examples: protective figure

80. Threshold / Phase Change [VIEW] (Prehistory - 1500 CE)
Definition: Qualitative transition point.
Examples: freezing point

81. Representation / Symbolic Stand-in [CORE] (Prehistory - 3000 BCE)
Definition: Symbol for something else.
Examples: maps, icons

82. Knowledge / Justified Truth [COMP] (Prehistory - 1500 CE)
Definition: Truth supported by justification.
Examples: scientific knowledge

83. Commitment / Binding Intent [CORE] (Prehistory - 1500 CE)
Definition: Locked intention to act.
Examples: contracts

84. Correction / Error Repair [OP] (Prehistory - 1500 CE)
Definition: Fixing deviations.
Examples: debugging

85. Stability / Equilibrium [CORE] (Prehistory - 1500 CE)
Definition: Resistance to change.
Examples: equilibrium

86. Belief / Assumed Truth [CORE] (Prehistory - 600 BCE)
Definition: Accepted truth without proof.
Examples: belief

87. Disagreement / Conflict [COMP] (Prehistory - 600 BCE)
Definition: Opposing relations or views.
Examples: argument

88. Alignment / Agreement [COMP] (Prehistory - 600 BCE)
Definition: Coordinated relation.
Examples: consensus

89. Compression / Abstraction Gain [OP] (Prehistory - 1500 CE)
Definition: Reduction while retaining meaning.
Examples: abstraction

90. Termination / Closure [CORE] (Prehistory - 1500 CE)
Definition: End of process.
Examples: completion

91. Zero / Null [CORE] (Prehistory - 300–500 CE)
Definition: Representation of nothing.
Examples: 0, null

92. Surrender / Yield [CORE] (Prehistory - always)
Definition: Full handover.
Examples: yielding control

93. One / First Distinction [CORE] (Prehistory - 3000 BCE)
Definition: First unit.
Examples: 1

94. Mogri / Undifferentiated Potential [RUN] (Prehistory - Present 2025)
Definition: Foundational substrate.
Examples: raw potential

95. Observer / Agent [CORE] (Prehistory - 1500 CE)
Definition: Entity that perceives or acts.
Examples: human, AI

96. Noise / Signal Split [OP] (Prehistory - 1500 CE)
Definition: Separate signal from noise.
Examples: filtering

97. Wadri / Wake-Dreamer [RUN] (Prehistory - Modern)
Definition: Runtime navigator.
Examples: archetypal agent

98. Counterfactual / Alternative Scenario [VIEW] (Prehistory - 1500 CE)
Definition: Variant of counterfactual.
Examples: alternate case

99. Amphibiance / Duality [RUN] (Prehistory - 2026 BCE)
Definition: Dual-state extension.
Examples: dual framing

100. Perspective / Point of View [CORE] (Prehistory - 600 BCE)
Definition: Frame of observation.
Examples: viewpoint

101. Dragon / Beast [RUN] (Prehistory - 2026 CE)
Definition: Active hunt entity.
Examples: DR:qs(...)

102. Factual / Reality [CORE] (Prehistory - 1800–1900 CE)
Definition: Actual state.
Examples: physical facts

103. Causation / Correlation [CORE] (Prehistory - 1500–1600 CE)
Definition: Observed link without mechanism.
Examples: correlation

104. Resource / Capacity [VIEW] (Prehistory - 1800–1900 CE)
Definition: Amount of usable resource.
Examples: battery capacity

105. Process Termination [VIEW] (Prehistory - 1500–1600 CE)
Definition: End of a process instance.
Examples: program ends

106. Anomaly / Outlier [VIEW] (Prehistory - 1500–1600 CE)
Definition: Deviation instance.
Examples: unusual data point
---

## Notes

1. **Numbering and format**
- Original primitive numbers (1–106) are preserved for reference and historical tracking.
- Each primitive is listed in a 3-line format: name/descriptor, definition, examples.

2. **Dates (in-use vs recognised)**
- Dates in parentheses indicate approximate cognitive *in-use* period (when humans likely used or understood the concept) and first formal *recognition* (when the primitive was explicitly named or systematised).
- Dates are rough estimates and intended as illustrative, not definitive.

3. **Annotation System (CORE / VIEW / OP / COMP / RUN)**
- Each primitive is tagged with a functional status:
  - **CORE**: irreducible primitives used in base reasoning
  - **VIEW**: alternate framings of CORE primitives (collapse during reasoning)
  - **OP**: operators acting on primitives (do not introduce new ontology)
  - **COMP**: composites constructed from multiple primitives (expandable)
  - **RUN**: runtime/system-level constructs (environmental or narrative layer)
- These tags define how primitives should be interpreted and processed.

4. **Processing Guidance**
- Prefer **CORE** primitives for reasoning and state representation.
- Reduce **VIEW** → corresponding CORE before inference.
- Expand **COMP** into constituent primitives when precision is required.
- Apply **OP** as transformations over primitives.
- Treat **RUN** primitives as context or runtime environment, not object-level entities.

5. **Mogri (Primitive 94)**
- Mogri represents the **foundational cognitive container** for all other primitives.
- It is *not* a derivative primitive and cannot be constructed from other primitives.
- It functions as a **runtime substrate** rather than an entity.

6. **Gaps and Reserved Numbers**
- Some numbers were reserved or missing in the original source.
- These can be filled without disrupting numbering or structure.

7. **Conceptual Use**
- This list is a **modeling tool** for cognition, AI, and formal reasoning.
- The primitives are **formal constructs**, not metaphysical claims.
- They may be adapted based on system requirements.

8. **Examples**
- Examples are illustrative and non-exhaustive.
- They demonstrate usage, not boundaries.

9. **Cross-References**
- Some primitives overlap intentionally (e.g., Causality vs Causation).
- Overlaps reflect functional distinctions, not duplication.

10. **Extensions**
- Additional primitives or meta-primitives may be appended.
- The annotation system supports extension without restructuring.

11. **Usage Guidance**
- Suitable for AI reasoning systems, cognitive modeling, and structured analysis.
- Designed for stability, reduction of ambiguity, and controlled concept expansion.

12. **Attribution**
- Synthesized from historical, philosophical, and cognitive sources.
- Dates and examples are approximate and serve modeling clarity.
TLC_STRIP:
snake=3g=EXSIDNACTATRQTYSPCTMECAUCMPNEGDIRPOSCOMMODEMOROLINTAGGBNDPRSCHGCLSSEQMESBMKCORPERDSTSCLNETDYNPOTOBSCEFPSBCSTTHRERRFIXPRCTRMRMGPRBMECPATSYMSIGUNDMEARESDEFMTDMETADPTMRFLWEVLQNTCATQSCFRCRECANMINFHRYSTRREFASCSATCTXAGTNRMRCRDFTCFWOBLVALTRDIRGPHSYBKNOCMTRPRSTBBLFCNALGCPRENDZEREYEONEMOGIAGNOSWDRALTAMPPOVDRIFACCRCCAPFINOUT
