# Synthesis: Coverage Across Families of Approaches

The previous pages analyzed major families of approaches using a shared analytical lens: the governance–knowledge matrix.  Each family was examined in terms of its dominant governance mode and the primary knowledge object it treats as governable.

This page aggregates those observations.  Its purpose is not evaluative.  It does not rank approaches or suggest superiority.  Instead, it consolidates patterns of structural emphasis and relates them to the recurring challenges identified in the upstream problem space.

Two complementary perspectives are used:

- an aggregated governance–knowledge matrix, and  
- a cross-family table mapping recurring challenges to typical coverage levels.


## Aggregated Governance–Knowledge Matrix

Figure 1 shows the aggregated coverage across families.  For each cell of the matrix, the highest level of coverage observed among the analyzed families is represented.  The aggregation rule is **maximum-based**, not additive: a cell appears dark only if at least one family strongly activates that configuration.

<p align="center">
  <img src="../../img/governance-knowledge-matrix-synthesis.svg"
       alt="Aggregated governance–knowledge matrix across families"
       width="720" />
</p>

<p align="center"><em>Figure 1: Aggregated governance–knowledge coverage across analyzed families of approaches.</em></p>

Taken together, the matrix distinguishes nine conceptually different governance configurations.  An approach may emphasize one configuration, combine several, or shift across them depending on context.  The purpose of the matrix is to provide a stable conceptual frame within which such patterns can be analyzed systematically.

### Observed Structural Patterns

Several structural concentrations become visible:

- **Strong coverage of Execution governance**, particularly in the Operational × Execution and Managerial × Execution cells.  Methodologies and scaled frameworks dominate this space.

- **Strong coverage of Managerial × Intentional governance**, especially through project, portfolio, and formal governance frameworks that articulate strategic objectives and investment intent.

- **Partial coverage of Structural governance**, especially in architecture-centric and documentation-heavy approaches, with emphasis in Epistemic × Structural and Managerial × Structural cells.

- **Limited concentration in Epistemic × Intentional governance**, where durable, inspectable articulation of system-level intent would reside.

This distribution does not imply weakness or deficiency in any family.  It reveals a structural asymmetry in how governance effort is distributed across knowledge objects and governance modes.


## Cross-Family Coverage of Recurring Challenges

The structural view above can be complemented by examining how families address the recurring challenges identified in the upstream problem space:

- implicit and unexamined decisions  
- loss of original intent and rationale over time  
- fragmentation of understanding of the software system  
- divergence between intent and realized structure  
- difficulty assessing and governing change  
- limited ability to revisit and re-evaluate past decisions  

The following table summarizes typical coverage levels based on dominant design intent and characteristic practice patterns.

| Recurring Challenge | Methodologies | Project & Portfolio | Architecture-Centric | Governance & Standards | Tool-Centric |
|---------------------|--------------|---------------------|----------------------|------------------------|--------------|
| implicit and unexamined decisions | Low–Medium | Medium | Medium | High | Medium |
| loss of original intent and rationale over time | Low | Low–Medium | Medium | Medium | Medium |
| fragmentation of understanding of the software system | Medium | Medium | High | Medium | Medium–High |
| divergence between intent and realized structure | Low–Medium | Low | Medium–High | Medium | Medium |
| difficulty assessing and governing change | Medium–High | High (initiative level) | Medium | High (compliance level) | Medium |
| limited ability to revisit and re-evaluate past decisions | Low | Low–Medium | Medium | Medium | Medium |

### Interpreting the Table

Several observations emerge:

1. **Execution-level change governance is well supported.**  
   Many families provide strong mechanisms for enacting and managing change within bounded scopes.

2. **Strategic or declared intent is frequently governed at a managerial level.**  
   Portfolio and governance frameworks articulate objectives, funding criteria, and compliance constraints.

3. **Structural coherence receives partial but uneven attention.**  
   Architecture-centric approaches emphasize structure explicitly, while others treat it as secondary.

4. **Durable intentional knowledge and systematic revisitability remain comparatively weaker across families.**  
   Mechanisms for preserving and re-evaluating assumptions, non-goals, and long-term rationale are rarely institutionalized as epistemic governance practices.

These observations align with the structural distribution visible in Figure 1.


## Structural Asymmetry in Governance

When the matrix and the challenge table are considered together, a structural asymmetry becomes visible:

- Execution is strongly governed.
- Investment intent is formally governed.
- Structure is partially governed.
- Durable, epistemically articulated system-level intent is comparatively underrepresented.

This asymmetry corresponds directly to several upstream challenges, particularly:

- loss of original intent and rationale over time,  
- limited ability to revisit and re-evaluate past decisions, and  
- divergence between intent and realized structure.

The pattern is not accidental.  It reflects how dominant approaches conceptualize what is governable and how governance should be exercised.


## Transition

The analysis above does not diminish the importance of existing approaches.  Each family addresses essential dimensions of software development and organizational control.

However, the structural pattern revealed by this synthesis suggests that certain dimensions of the upstream problem space require a form of governance that is not systematically foregrounded within current families of approaches.

The next part of this guidebook articulates **Upstream Software Engineering** as a discipline explicitly concerned with epistemic governance of software system intent and its relationship to structure and evolution.

Proceed to **Foundations**.