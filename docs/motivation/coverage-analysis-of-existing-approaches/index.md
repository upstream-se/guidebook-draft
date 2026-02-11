# Coverage Analysis of Existing Approaches

This part presents a coverage analysis of established approaches to software development, management, and governance with respect to the upstream challenges identified in the **[Problem Space](../problem-space.md)** and articulated as **[Recurring Challenges](../recurring-challenges.md)**.

The purpose of this analysis is to examine how existing approaches address different portions of the upstream problem space.  Each approach is considered in terms of how governance is enacted and which aspects of the software system are primarily treated as governable.  Taken together, these analyses make it possible to observe patterns of coverage across approaches in a systematic and comparable manner.



## How this analysis is structured

The pages in this part are organized in three stages:

1. Introduction of a comparative analytical lens,  
2. Application of that lens to different families of approaches,  
3. Examination of aggregate patterns across those analyses.

Rather than evaluating individual methods or frameworks in isolation, the analysis focuses on how different classes of approaches enact governance and what knowledge objects they explicitly govern.  This structured comparison provides a consistent basis for reasoning about coverage across approaches.



## On families and overlap

The families of approaches presented in this part are analytical groupings rather than mutually exclusive classifications.  They reflect dominant orientations within the governance–knowledge matrix, not rigid taxonomic boundaries.

Some approaches—particularly large-scale or enterprise-wide frameworks—engage multiple governance modes and target more than one primary knowledge object.  Because this analysis is organized by dominant governance configuration rather than by named frameworks, such approaches may be examined in more than one family.

When this occurs, the emphasis of the discussion changes.  In one context, an approach may be analyzed for how it governs execution through coordination mechanisms; in another, for how it structures portfolio-level decisions or architectural alignment.  The repetition reflects the multi-dimensional character of the approach within the governance–knowledge matrix, not a duplication of analysis.

This overlap is intentional.  It reflects the multi-dimensional nature of governance rather than inconsistency in categorization.



## A comparative lens: governance and knowledge

A central element of this analysis is a comparative lens that differentiates:

- **Governance mode** — how governance is enacted (operational, managerial, or epistemic),  
- **Primary knowledge object governed** — what aspect of the software system is governed (execution, structural, or intentional).

These two dimensions form a 3×3 matrix that serves as a typology of governance configurations.

This lens is introduced and explained in detail in **[A Comparative Lens: Governance and Knowledge](./governance-knowledge-matrix.md)**.  It provides the conceptual frame within which subsequent analyses are conducted.



## Pages in this part

This part of the guidebook is composed of the following pages:

- **[A Comparative Lens: Governance and Knowledge](./governance-knowledge-matrix.md)**  
  Defines the analytical instrument used throughout this part, including governance modes and primary knowledge objects governed.

- **[Methodologies and Process Frameworks](./methodologies-and-process-frameworks.md)**  
  Examines development methodologies and process-oriented approaches through the governance–knowledge lens.

- **[Project and Portfolio Management Approaches](./project-and-portfolio-managemnt-approaches.md)**  
  Analyzes initiative-centric and portfolio-level approaches using the same analytical frame.

- **[Architecture-Centric Approaches](./architecture.md)**  
  Discusses architectural practices and their characteristic governance configurations.

- **[Governance, Standards, and Compliance Frameworks](./governance-and-standards.md)**  
  Reviews formal governance and compliance-oriented approaches in terms of governance mode and knowledge object.

- **[Tool-Centric and Documentation-Heavy Approaches](./tools-and-documentation.md)**  
  Examines approaches that rely primarily on tools or documentation within the same conceptual frame.

- **Aggregate Coverage and Observed Patterns**  
  Synthesizes the preceding analyses to examine patterns across the governance–knowledge matrix.



## How to read this part

Readers are encouraged to begin with **[A Comparative Lens: Governance and Knowledge](./governance-knowledge-matrix.md)**, which establishes the analytical frame used throughout this part.

The subsequent pages apply this lens to different families of approaches.  After reading the individual analyses, the aggregate synthesis can be consulted to understand broader coverage patterns across governance modes and knowledge objects.